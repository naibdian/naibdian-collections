![iris_full](https://user-images.githubusercontent.com/91549230/135595760-15185970-d97e-43dc-8786-d754c128095e.png)

## NaibdiaN Iris Collection

[Naibdian Iris on Opensea](https://opensea.io/collection/naibdian-iris-l2)

Iris is 1st collection out of my biomorphic studies based on dynamic large particle systems. You're not acquiring just a static image but a realtime simulation of an evolving microbiome. You can replay/start/stop same evolution (by left click or space touch).

![Clock to see a video of one the microbiome evolution found in NFT collection](https://user-images.githubusercontent.com/91549230/135596123-dadf0e63-da98-40eb-9b84-8be120850548.mp4)

Iris is inspired by Physarum mold transport and named after eyes' iris. Iris microbiome consists in a small population of 16K organisms spread in a circle on a 2K (1920x1080) sized field. I chose Physarum mold transport because I like Sage Jenson's post https://sagejenson.com/physarum and Jeff Jones's paper, _“Characteristics of pattern formation and evolution in approximations of Physarum transport networks.”_. (And also for the joke mold -> fungi -> fungible -> NFT 👏). Then, the idea is to explore possible microbiomes and find the most beautiful or peculiar ones evolving very fastly or very slowly through remarkable transitions and to very stable or unstable final state.

### Technical details 

#### Running Environment
- Better run on PC/Mac with medium GPU. You can run on small window up to full screen on 2K screen (1920x1080, 1 pixel = 1 particle position). Higher resolution will run with black borders around. For first iteration, I chose a relatively small microbiome on standard 2K screen. The aliased aspect of particles spread on full-screen is due to the relatively small number of particles (16K only) that let you see particles spread but also my color coarse spread choice that focused on super-exposition to make it look like an explosion.
- On some computers with not powerful GPU, it could lag (specially when the number of particles will increase later) but rendering is correct.
- On mobile, rendering is wrong (see Disclaimer below) and a video alternative is proposed but you can click on the link under the video to try full feature system on your mobile (see warning above)

> **DISCLAIMER on bad rendering on mobile or low power GPU**:
> These experimentations are both an attempt to explore cool graphical visualisations but also a technical exploit trying to push current graphical system up to their limits to produce cool visuals. In this software, everything runs in a web browser but is actually computed mostly on GPU and those large particle systems require high float precision or you start to see weird graphical issues like screen drifting on one side or very coarse particle stacks. Unfortunately, many mobile phones are currently limited in this WebGL precision scope due to WebGL implementations focusing on performance optimisation. So on most mobile (except maybe the most recent) rendering is not good. Sorry about that, it should run later in future on mobile ;)

#### Available user actions on NFT

- replay the same whole evolution by simply reloading the page.
- stop/restart animation at one point by clicking left-mouse or space bar if you like it and want to observe.


#### Blockchain

Iris is delivered on _Polygon blockchain_ because gas fees are much lower than Ethereum (despite other lagging issues). My aim is to produce & sell graphical experiments, not to feed miners. If enough people request it, I could mint some NFT from this collection on Ethereum or other chains.


### Owner Perks

These NFT are 100% independent of any NFT/Blockchain platform and autonomous. The idea is that as long as you have the software package and a web browser, you should be able to run the software linked to the NFT in the future. If some people request it, I could build a mechanism to deliver the NFT packaged in an autonomous archive with a blockchain certification that you acquired it.


### Future collections


We'll release soon new cool graphical unique collections based on the same concepts but exploring other microbiomes with peculiar or beautiful emerging behaviors, transitions or final state.

We'll also release much more complex particles systems (hundreds of thousands of particles and millions) that will require push your GPU a bit further but bring also much more complex, fine & cool visuals.

If you like these concepts/visuals, have issues, special request, don't hesitate to contact on twitter [@naibdian](https://twitter.com/naibdian).

Enjoy yourself while it evolves!

NaibdiaN
