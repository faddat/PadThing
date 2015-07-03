# PadThing

The Native Pad for the Future.

[![Join the chat at https://gitter.im/PadThing/PadThing](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/PadThing/PadThing?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)


## Inspiration

This draws inspiration from text-editors like HackPad, Google Docs, iCloud, Evernote, Quip, as well technologies for the future of the internet. Decentralization, p2p, self hosting, containerization, transparency, are all proposed topics of discussion.

## Road Map

- Razor down the concepts into a succinct set of core functionality.
- Build an agile architecture that can be extended.
- Engineer interfaces and foundation for the community.
- Implementation

### Discourse from Gitter
UpToDate->https://gitter.im/PadThing/PadThing/archives/2015/07/03 

**@ds0nt**

Hey faddat

hey Nguyen




**@faddat**

and @thanhson1085. There we go.




**@thanhson1085** are you the Coreos / Docker meetup organizer here in Hanoi?

TeknoShamin 19:55

+1 for the fork.

almereyda 22:06

I'm in. How do we proceed? First evolving the strategy document; then looking at selected implementations, extracting milestones of wished feature sets and then implementing?

faddat 22:11

well

Okay for me, I used to be a teacher-- US History, high school level. Anyway, I'm a startup geek now. Here's the point though: Quip is weak sauce

and closed

it eats your docs in the long term

Then there's Google docs, which you may as well forget about in China, and therefore by extension increasingly large swathes of the economy

but-- if one had a secure P2P, native to the desktop, native to android native to ios

ds0nt 22:13

hey, people are here!

faddat 22:13

collaborative editing tool

ds0nt 22:13

Hi all

faddat 22:13

well, it would more or less rock.

ds0nt 22:13

I wrote http://forky.io

To give a bit of background

faddat 22:14

I'll lay out a rough list of requirements that I suspect that you'll find in all academic environments

ds0nt 22:14

mindmapping, so know a bit about rt collaboration.. well.. but fresh start is needed

tech is all changed in 8 months

sweet

where should it go?

I just had a brilliant idea:

1 sec

almereyda 22:30




*@ds0nt** : is there a source for forky? does it have oauth2 adaptors (to twitter/github/google+/persona/...) ? could you please serve it over https, if you request users to trust you 

with their passwords? ;)

ds0nt 22:36




**@almereyda** Yep, it's either itdawns/forky or ds0nt/forky

Ahh, it sortof doesn't work very well at the moment

Because I make a mess out of nodejs backends, every time.

I have discovered that, if I code it all in one long .js file, things become much nicer... koajs is short enough for me to get away with it for small/medium things

oauth2 adapters, nope. I'd be interested in porting it into Golang

If I had a collaborator or two

Or, there is also that.. thing with all the oauthing.. grake ? hmm

ds0nt 22:42

https://github.com/simov/grant

thats the 1

almereyda 03:16

Okay, I'll have a look. I also have some notes about the comparison I've mentioned above. Can take a week until I find them ...

ds0nt 04:11

Ok so let

I'm going to put my thoughts down so that we can get discussing.

So here's what collaborative text editor looks like to me...

as a whole, genre of apps.

ordered from used most to least extensively (which also happen to be best to worst experience.

quip (also, the best)

hackpad

google docs

OneNote (microsoft)

ds0nt 04:18

How I use them

I always am using these docs in order to communicate with my team, and jot things down.

Topics include: business, development roadmaps, product ideas, recording as I research (ux screenshots, lists of urls, etc.)

and Quip wins out completely on that

because, well, there's a freaking chat

it's not even that good

but @faddat and I still use it to communicate with our vietnamese investorish guy, and it works... lol

Key Point: Collaboration is first citizen (or w/e)

Next up: Mobile needs to be there

Apps that don't get on at least 2 of my devices don't stick around.

Because I end up using evernote, and then I have to meditate cause I feel all green and useless

Key Point: 1) App goes on -> Website & Desktop, and mobile... I say..

ds0nt 04:23

I don't see how one project can span across three languages and actually be maintained correctly across the board, so it's sorta impossible to do anything other than webviews.... but hey...

webviews work well :)

Android App: SocialAgent.me mine from when I thought what I designed looked cool... haha, it's done in cordova/phonegap

pretty easy to do really, just a nuisance to deal with the edge cases

like the status bar on an iphone6 takes up 60 pixels that overlap the web view, so you have to add body padding to the top after checking for IOS

This message was deleted

ds0nt 04:30

erm.. where am I going here...

faddat 04:30

the right directiion

undoubtedly

ds0nt 04:31

Collaboration is important

Apps on all devices

Real-time

A foundation for community growth

4 is a hard one

faddat 04:32

the frameworks change too fast

in general

ds0nt 04:32

There are a lot of programs with horrible plugin ecosystems. Take for example... atom IDE

half the shit broken, nodebb forums same thing

dockerhub, half the shit is broken.... even lol

faddat 04:33

I cant stand dockerhub

it needs community cuation

ds0nt 04:34

me neither, I end up in some github repo tree with too many choices

I think that golang did an incredible job

and I think we can learn from them

http://talks.golang.org/2014/organizeio.slide#4

the whole deck is good, not just slide 4, oopsies

iOS also did it well

ios made sure that all their apps were this way or that, and though it pisses me off... they sortof are doing well.

ds0nt 04:39

Golang changed things up to make it super collaboration friendly, the whole language. Go looks sharable by design, at least from looking at those slides. (I have a hello.go)




**@faddat** yeah, it does.




**@faddat** dockerhub needs a new hub.

:p

I think also... polymer might be designed with that somewhat in mind. My only problem with polymer is... I don't put my code in google-prison

but it's ok! because I will free the html prisoners!!

http://i.imgur.com/cRnPL1V.png

lol

I want their paper elements :)

ds0nt 04:45

We might need to gather more troops to execute this

if anyone has troops, get em into this discussion, and anyone you think

has wisdom for us

So guys, please follow up with more brainstorming and we can start to form something of a plan. :)

ds0nt 04:51

Also let's all follow eachother on twitter, for wins. im twitter: ds0nt

I think we should steer this for open source and not really enterprise, because open source is better, going to win, and I want to be part of the team that won in five years

ds0nt 04:56

 the right directiion

thanks @faddat :P

I'm going to poke some quip dudes and see what they do

ds0nt 05:10

well I hope they stop by.
