Stream Setup
============

Hardware
--------

Gaming PC
	AMD 3600 X
	Gigabyte B450M
	EVGA 3090 FTW3
	Corsair Dominator Platiunm 32GB
	Corsair HX1200i

Streaming PC
	Intel i7-7820X
	Gigabyte X299 AORUS Gaming7
	Gigabte 1080Ti Waterforce
	GSkill 64GB Quad Channel
	Corsair HX1000


`ESP32s <https://www.aliexpress.com/item/4000093185394.html?spm=a2g0o.order_list.order_list_main.91.55fd1802Bvx6FJ>`_
	Just a bunch of ESP32s running various lights setup around the office to do the effects triggerd by chat

`Heart Rate Monitor <https://amzn.to/47eSrey>`_ *referal link*
	I chose the COOSPO Heart Rate Monitor as it was both affordable, available and well recommended by the folks running Pulsoid, more on them in the Software section below

Software
--------

`Home Assistant <https://www.home-assistant.io>`_
	I use Home Assistant to help make the stream feel more alive! Many of the channel rewards have effects that take place in the real world, and HA is how that is possible. Through various smart plugs, custom ESP32 LED modules and Chromecasts we can make all manner of things happen!

	I also just low key love HA and making my own smart home with $10 smart lights from walmart.

`OBS Studio <https://www.home-assistant.io>`_ 
	The streaming software of choice, between the open source nature of the project and all the plugins the are available as a result there really is no other choice

`SAMMI <https://sammi.solutions>`_
	Used to do scene changes and effects that happen on stream. This also enabled the Channel Point interactions to happen automatically

`Streamer.bot <https://streamer.bot>`_
	Used to do automation with stream interactions and IRL effects and others.

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

OBS Plugins
-----------

`3D Effects <https://obsproject.com/forum/resources/3d-effect.1692/>`_
	Adds the ability to edit a source in 3D space

`Advanced Scene Switcher <https://obsproject.com/forum/resources/advanced-scene-switcher.395/>`_
	As the name states, will automatically change scene based on different conditions

`Ashmanix Countdown Timer <https://obsproject.com/forum/resources/ashmanix-countdown-timer.1610/>`_
	Adds a countdown timer that can be triggered via websocket

`Closed Captioning via Google Speech Recognition <https://obsproject.com/forum/resources/closed-captioning-via-google-speech-recognition.833/>`_
	Provides live Closed Captions to the stream. They are added using Twitches built in CC so it is not forced in the stream and does not require a Twitch Extension

`Composite Blur <https://obsproject.com/forum/resources/composite-blur.1780/>`_
	Adds a blur filter with many options

`Face Tracker <https://obsproject.com/forum/resources/face-tracker.1294/>`_
	Add a filter that does live face tracking

`Freeze Filter <https://obsproject.com/forum/resources/freeze-filter.950/>`_
	Adds the ability to live freeze a source for different effects

`Move Transition <https://obsproject.com/forum/resources/move.913/>`_
	Adds the ability to both move sources but also change values for another filter for gradual changes

`Replay Source <https://obsproject.com/forum/resources/replay-source.686/>`_
	Adds the ability to replay a specific source instead of the whole scene for clean replays

`Source Screenshot Filter <https://github.com/synap5e/obs-screenshot-plugin>`_
	Adds the ability to save a screenshot of just a source

`Source Clone <https://obsproject.com/forum/resources/source-clone.1632/>`_
	Adds Source Clone as a source type

`Source Record <https://obsproject.com/forum/resources/source-record.1285/>`_
	Adds the ability to record a source

`Multiple RTMP outputs plugin <https://obsproject.com/forum/resources/multiple-rtmp-outputs-plugin.964/>`_
	Adds the ability to output to multiple RTMP endpoints for 1 stream

`Waveform <https://obsproject.com/forum/resources/waveform.1423/>`_
	Adds a audio wave form to the stream when we speak as a cool feature

`VBAN Plugin <https://obsproject.com/forum/resources/vban-audio-plugin.1623/>`_
	Adds VBAN as a source item to directly connect an audio source using VBAN
