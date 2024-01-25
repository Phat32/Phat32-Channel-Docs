Stream Setup
============

Hardware
--------

Gaming PC
	- AMD 3600 X
	- Gigabyte B450M
	- EVGA 3090 FTW3
	- Corsair Dominator Platiunm 32GB
	- Corsair HX1200i

Streaming PC
	- Intel i7-7820X
	- Gigabyte X299 AORUS Gaming7
	- Gigabte 1080Ti Waterforce
	- GSkill 64GB Quad Channel
	- Corsair HX1000
	- AverMedia Duo Capture cards
	- AverMedia Live Gamer HD

`ESP32s <https://www.aliexpress.com/item/4000093185394.html?spm=a2g0o.order_list.order_list_main.91.55fd1802Bvx6FJ>`_
	Just a bunch of ESP32s running various lights setup around the office to do the effects triggerd by chat

`Heart Rate Monitor <https://amzn.to/47eSrey>`_ *referal link*
	I chose the COOSPO Heart Rate Monitor as it was both affordable, available and well recommended by the folks running Pulsoid, more on them in the Software section below

Software & Services
-------------------

`blerp <https://blerp.com>`_
	Various sound effects are played via blerp

`Crowd Control <https://crowdcontrol.live>`_
	Adds interactivity with the audience to have a direct impact in various games. Not all games support it, but many do

`Frosty Tools <https://frostytools.com>`_
	Adds an AI interactive element to the stream, makes shoutouts dynamic and recaps of chat

`Home Assistant <https://www.home-assistant.io>`_
	I use Home Assistant to help make the stream feel more alive! Many of the channel rewards have effects that take place in the real world, and HA is how that is possible. Through various smart plugs, custom ESP32 LED modules and Chromecasts we can make all manner of things happen!

	I also just low key love HA and making my own smart home with $10 smart lights from walmart.

`OBS Studio <https://www.home-assistant.io>`_ 
	Kinda obvious, but the streaming software of choice around here

`SAMMI <https://sammi.solutions>`_
	Used to do scene changes and effects that happen on stream. This also enabled the Channel Point interactions to happen automatically

`Streamer.bot <https://streamer.bot>`_
	Used to do automation with stream interactions and IRL effects and others.

`PhatBot <https://phatbot.phat32.tv>`_
	The chatbot I made and use to add several common chatbot features

`Pulsoid <https://phat32.tv/pulsoid>`_ *referal link*
	Connects various Heart Rate Monitors to a phone and send the heart rate data to their servers where they provide widgets that display the current heart rate in real time. There is a paid tier but it is not required to use the service at all

`VDO.Ninja <https://vdo.ninja>`_
	Turns any device with a camera and a browser into a camera you can add via browser source. Control the cameras from the PC in 1 location. Optional for self hosting as it is totally free

	I would suggest creating a room you can be the director for from your PC and control your phones camera settings from there

	There are also a number of URL Parameters you can utilize to get it working just how you want, but I would encourge adding this to the URL on your phone for better performance and reduce the heat created

	.. code-block::

		&consent&nopreview

	&consent adds the ability to control your camera settings without prompting
	&nopreview disables the preview on the screen which reduces heat generated
