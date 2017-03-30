# ecosystem-pi
A closed-system ecosystem managed with a Raspberry Pi 3 monitoring system.

## Why I Started This Project

I work at a pharmaceutical manufacturer and was dismayed when I heard about their "one and done" policy regarding some of the (expensive) glassware; after only one use in some cases, it is sent to landfill.  Since I'm into saving the planet, I thought I'd recycle some of this glassware. This is one of the projects related to that recycling.

Each new carboy costs from $300-$750 before shipping/taxes and I just snagged four of these from work before they made it to the dumpster. They're rugged, heavy, solidly-made and ready for this first project.

![19L-carboy](https://cloud.githubusercontent.com/assets/15971213/24085463/f3ac3efe-0cb9-11e7-9af1-9f3ba0c62e58.png)

## Closed Ecosystem Aquarium
A closed ecosystem is one which doesn't require any maintenance or feeding from the owner. The entire ecosystem survives because it's in balance—the flora-to-fauna ratio is matched so that carbon dioxide produces by the animals matches the needs of the plants and vice versa with respect to the oxygen.

The animals feed from the plants and the plants get organic nutrients leftover by the animals. The plants convert carbon dioxide into oxygen using the power of light through photosynthesis.

## Raspberry Pi 3
Ultimately, I intend to dedicate a Raspberry Pi 3 single-board computer to monitor that delicate balance during the setup phase. It's important to monitor the carbon dioxide and nitrogen levels in order to confirm that the system can maintain itself.

I intend to first monitor and graph the carbon dioxide levels over time and use this to adjust the number of shrimp to be added to the ecosystem.

The next step then would be to use the Raspberry Pi 3 to monitor the changes in carbon dioxide to adjust the amount of time that light is added. The more light, the faster the plants produce oxygen. Too much oxygen results in algae. Too little oxygen results in the shrimp dying off.

![raspberry-pi-3](https://cloud.githubusercontent.com/assets/15971213/24085956/26739ce8-0cc3-11e7-8adb-4602a9a873a9.jpg)

## Parts List
Here's the quick-and-dirty parts list so far. I'll add prices when things get a little further on.

1. <s>Raspberry Pi 3</s> Raspberry Pi Zero W with 16GB micro-SD card, Raspian operating system and power adapter
2. One 19-liter Corning Pyrex carboy
3. One glass stopper which fits it
4. One RhyzoMat subsurface root mat
5. One 20# bag of CaribSea Eco-Complete Planted Aquarium substrate
6. Optionally, one container of Seachem Flourish Excel
7. Two coathangers
8. A quart-sized measuring cup, a large spoon and a funnel plus some clingwrap and a sturdy pair of scissors
9. Three gallons of distilled water
10. A roll of paper towels to cleanup
11. Two tall, freshwater plants (I chose *Aponogeton ulvaceous* as seen in later photographs)
12. Two tiny female shrimp
13. A 10g packet of shrimp food
14. Optionally, one container of Ecological Laboratories Nite-Out II nitrifying bacteria
15. Four NeoPixel quarters to form a 60-LED ring
16. A CO<sup>2</sup> sensor with relative humidity and temperature built-in

### RhyzoMat
You'll need to buy a square of RhyzoMat for the base. the plants will send their roots down and anchor into it.

![rhyzomat-step2](https://cloud.githubusercontent.com/assets/15971213/24085690/7cb55c3c-0cbd-11e7-99d8-8ef5c84026fd.png)

### Cut It Into a Circle
It doesn't have to be perfect, noting that we're only adding two plants into the system initially so anything close will do.

![rhyzomat-step3](https://cloud.githubusercontent.com/assets/15971213/24085713/effccd74-0cbd-11e7-8b2f-958fca65d19e.png)

### Curl It, Push It Through the Top
You'll next need to tightly curl up the RhyzoMat so that it will fit through the approximately 3" inner diameter of the top. It will help if you have a dowel or bathroom curtain rod (or both) for the next step.

![rhyzomat-step4](https://cloud.githubusercontent.com/assets/15971213/24085718/0ac6be62-0cbe-11e7-87f0-bb222d23eda1.png)

### Tamp It Down
Using something long enough, tamp down the RhyzoMat and if necessary, stretch it back out into a circle.

![rhyzomat-step5](https://cloud.githubusercontent.com/assets/15971213/24085749/8dec523e-0cbe-11e7-9ecd-ac4ad462a1b7.png)

### Coathangers
You'll want to bend two coathangers as I've done so that they can be used later to hold down the plants just above the root area.

![coathangers-step6](https://cloud.githubusercontent.com/assets/15971213/24085755/b1715c0e-0cbe-11e7-9cb4-f316e73cb079.png)

### Add Coathangers With Plants
Gently lower each coathanger and plant and guide them to one side. It helps to next put the carboy partially on a towel so that it's tilted and the substrate then will fall to the opposite side and not on the leaves.

![coathangers-step7](https://cloud.githubusercontent.com/assets/15971213/24085766/e8806294-0cbe-11e7-9325-4be17ad88b33.png)

### Add Six Cups of the Water From the Substrate
The substrate comes with about eight cups of water with the 20-lb bag. I'm using the [CaribSea Eco-Complete Planted Aquarium Substrate](https://www.caribsea.com/caribsea_ecoplanted.html).

### Add the Substrate Slowly
Add about eight cups of substrate slowly using a spoon. It helps to tilt the carboy so that the substrate falls to one side. Add a little, adjust the location of the plants, tilt the carboy differently and add more substrate until you've covered the bottom.

![substrate-step8](https://cloud.githubusercontent.com/assets/15971213/24085790/74f58f9c-0cbf-11e7-9208-304eefcdf278.png)

### Add Water
Move the carboy to its final location near sunlight but not in direct sunlight. It's important to get some sun but not too much. The intent is to later programmatically add just enough extra artificial light to keep everything in balance. So begin by finding a spot that can support a heavy carboy plus lots of water. It will be heavy after filling, about 40 pounds.

Add about three gallons of distilled water to bring the water level to the 4 gallon/15 liter mark on the graduated side of the carboy, noting that it has a 19-liter capacity in my case.

![distilledwater-step9](https://cloud.githubusercontent.com/assets/15971213/24085845/73f4a460-0cc0-11e7-8204-00de90320ca7.png)

### Optional Step
I added a half-capful of [Seachem Flourish Excel](http://www.seachem.com/flourish-excel.php) which adds bioavailable carbon for the plants. This is probaly unnecessary, to be honest.

### Anchor Each Plant For a Week
Smooth out the substrate. You'll want to guide the plants back toward a spot somewhere in the middle of the RhyzoMat and then bend the coathangers so that they hold the plants at the surface level. We're hoping that the roots will grow down and latch into the RhyzoMat over the period of a few days.

![aponogeton_ulvaceus](https://cloud.githubusercontent.com/assets/15971213/24334869/93e79658-1227-11e7-9a03-5a91a4bcbb3a.png)

Next, I prepared a square of clingwrap and just before covering everything I blew into the top of the carboy to add some carbon dioxide.

![anchoringplants-step10](https://cloud.githubusercontent.com/assets/15971213/24085867/cb34a3ec-0cc0-11e7-8c23-b95c2c29a871.png)

## Let Everything Sit For a Week
Give the plants a chance to root into the RhyzoMat so leave it in-place near a window that doesn't get too much direct sunlight.

### Rock Polishing Side-Project
Since it takes several days to polish gemstones in a rock tumbler, I'm doing this during the first week of settling for the ecosystem. Once polished, these will be added to the bottom of the carboy on top of the substrate.

## Review Things a Week Later
The water cleared up within 24 hours, as expected. I have re-arranged the coathangers so that instead of surrounding the top of the plant bulb in each case, it's now just weighing them down. There isn't a substantial amount of rooting going on yet so I'll need to let the coathangers remain until that happens.

### Algae Growth
After a week, it looks like a healthy amount of algae has now peppered the sides of the *Aponogeton ulvaceous* but I anticipate that the shrimp will feed off this as a food source.

![algae](https://cloud.githubusercontent.com/assets/15971213/24334849/315ea0b2-1227-11e7-8480-183723d4685d.png)

### Adding Two Female Shrimp
A trip to the local [D&K aquirium supply store](https://www.facebook.com/DK-Aquarium-n-Pet-446298812057525/) netted me two shrimp for the habitat.

As expected, the shrimp immediately began eating the algae on the plant leaves so this is a good sign.

![thumb_img_1410_1024](https://cloud.githubusercontent.com/assets/15971213/24334884/dd28d7d2-1227-11e7-8091-b387b242bdd3.jpg)

Interestingly-enough, I've discovered a tiny snail that appears to have come from either the plants themselves or perhaps managed to arrive with the shrimp this morning.

### Initial Feeding
I added about ten tiny pellets of [Hikari Tropical Shrimp Cuisine](http://www.hikari.info/tropical/t_29.html) shrimp feed.

### Optional Step
I added a half-capful of [Ecological Laboratories Nite-Out II](https://www.microbelift.com/products/home-aquarium/bacterial-products/nite-out-ii/) which reduces nitrates and ammonia. This is probably unnecessary, to be honest.

## Status - Three Days Later
Everything's looking great. The two shrimp have nicely eaten the algae from the two *Aponogeton ulvaceous* cleaning them thoroughly.

I've added a batch of tumbled gemstones to the bottom for a little color.  The roots have now taken hold enough so that I can remove the coathangers which held them down.

I've ordered additional parts: a programmable NeoPixel light ring, a CO<sup>2</sup> sensor with relative humidity and temperature built-in and a Raspberry Pi Zero W in the hopes that all this will work on the cheaper platform.

### Website Interface
I've been working on the website interface. At the moment, everything is mocked up for the readings but a fair amount of research went into making sure that the shrimp would be in a comfortable setting.

![ecosystem-pi](https://cloud.githubusercontent.com/assets/15971213/24483385/a40e702e-14ac-11e7-8b44-012858172cf0.png)
