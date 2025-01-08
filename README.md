
SoundWire Audio Communication System


Turn your Android device into wireless headphones / wireless speaker. Stream any music or audio from your PC to your Android phone, tablet, or other PCs. 
SoundWire does audio mirroring (audio cast). You can use any music player on your PC or laptop like Spotify, YouTube, or iTunes and stream low-latency live
sound over WiFi directly to your Android device. Also works over 3G/4G cell networks or WAN.


First install the SoundWire Android app from Google Play Store.


Then install the SoundWire Server on the Windows or Linux computer which is your source of music, web audio streaming, or other sounds. Click on
the appropriate version below to download. After downloading run the installer. You must answer yes ("Allow access") to the Windows Firewall prompt 
(select both private and public networks). For the Linux versions right-click on the image and choose "Save Link As", then untar and see the README.txt 
file for instructions. SoundWire Server download click below:


Alternate download site:   Win7/8/10/11    WinXP    Linux (all)   
If you have trouble with version 3.0 for 64-bit Linux and Qt5 then try the older version 2.1.2 for 64-bit Linux and Qt4.
** Download the official SoundWire Server software only from this site or directly linked sites


Touch the coiled wire image in the Android app to connect. For additional instructions and help information please see the SoundWire User's Guide.


You can use SoundWire to transmit sound from any PC to other PCs running Windows or Linux, see these instructions.


You may want to use an Android remote control app together with SoundWire to control music playing from your Android. Some good choices include: Unified Remote, VNC Viewer


Recent Server Updates
Version 3.1 2024-02-20 for Raspberry Pi with 64-bit support:
-GUI version of SoundWireServer for 32 or 64-bit Raspberry Pi OS versions, uses Qt5. Command-line-only version 2.1.2 still available.
Windows releases now include LAME MP3 encoder lame_enc.dll


Also on Android


Music VU Visualizer Widgets, view your music beautifully on your home screen.
Music VU documentation and help info



SoundWire Audio Communication System


 

SoundWire lets you stream any music from your Windows or Linux PC to your Android mobile devices. Use it as:

*  A wireless extension of your PC-based music or home theatre system

*  A remote speaker or wireless headphones

*  A way to listen to music and movies from your computer anywhere in your house or out on your deck



SoundWire does audio mirroring. You can use any music player on your PC or laptop like Spotify, YouTube, or iTunes and send the sound directly to your Android device. SoundWire lets you listen to the free version of Spotify on your phone.

 

SoundWire has low latency (audio delay), which means it can even be used to listen to the soundtrack of a movie or YouTube video while you watch. (Note you must adjust the buffer size in app settings for low latency, see below.) 
There are other uses too... SoundWire can work as a baby monitor or listening device with any Windows computer such as a netbook that has a built-in microphone. Or hook up turntables to your computer's line input and stream a live DJ 
set to another part of the house or anywhere else over 3G/4G/5G.

 

Features


*  Real-time audio capture and streaming to multiple clients

*  Excellent sound quality (44.1 / 48 kHz stereo 16-bit, PCM or Opus compression)

*  Low latency

*  Audio equalizer

*  Easy to use

*  Compression option greatly reduces network usage

*  Stream music from PC to PC running x86 virtualized app

*  Save everything you hear to a file (MP3 or WAV)

    

SoundWire Server Setup

Before using SoundWire on your Android device you must install and run the SoundWire Server application on the Windows or Linux PC/laptop/tablet which is your source of music, web audio streaming, or other sounds.

 

1.  Download SoundWire Server at georgielabs.net. Depending on your PC operating system choose the Windows 7/8/10, Windows XP, or Linux version as appropriate. Raspberry Pi is also supported. Do not obtain the server from any other web site.
2.   Open the ZIP file and run the installer inside. You must answer yes ("Allow access") to the Windows Firewall prompt (select both private and public networks). For the Linux version see the README.txt file for instructions.


3.  Open your favorite PC music application or web site like YouTube, Spotify, or iTunes


4.  Run the SoundWire Server program and select the audio source. On Windows 7/8/10 the default settings should capture what you hear now (“default multimedia device”). On Windows XP you should select the audio source named “Stereo Mix”, “Wave Out Mix”,
5.   “What U Hear”, or a similar name. On Linux follow the instructions in the README file. You can send any audio source to your phone, including speaker output, microphone, line input etc.


6.  When music is playing check the SoundWire Server level meter. This shows the volume level of sound being transmitted to your Android device. You may adjust the level using the volume control of your music player. If an Audio Input slider is shown
7.  on the SoundWire server use it as well. On Windows 7/8/10 you can also use the SoundWire server Audio Output slider, but this should normally be set to maximum. On Linux use Pulse Audio Volume Control to show and control volume levels. On Windows XP
8.  the Audio Output slider controls your PC speaker volume, not the transmitted audio level.

 

SoundWire Android App Setup

When the server is running and the level meter shows music playing, start the SoundWire Android app.


1.  Press the "Connect" button (coiled wire image) to connect to the server and begin listening. If the server address box is blank SoundWire will automatically locate the server. When the wire glows you have a good connection.


2.  If auto locate doesn’t work, or you have more than one server, enter your server address in the text edit box before connecting. The server address (IPv4) is shown on the upper left of the SoundWire Server window, for example: 192.168.1.201.
3.  In some situations the address shown by the server may not be correct, you can hover your mouse over the address to see other possible addresses (on Linux use ‘ifconfig’). Note that the SoundWire Server does not choose or control its IP address,
4.   that’s determined by your network configuration.


You can long-press on the connect button at any time to do auto locate, even if the address box is not blank. If you don’t hear any sound check that the level meter on the server shows audio being played and that the status is “Connected”. 
If the server connection is lost for more than a few seconds you may have to press the connect button again (use the “Auto reconnect” settings option to do this automatically). If you have trouble please see Troubleshooting Tips, below.

 

Recently Used Server History

Press the “triangle” button beside the server text box to choose from a list of up to four recently used server addresses. This may be useful if you run more than one SoundWire server, or your server address changes frequently
and you don’t use auto locate. After selecting the desired address press the connect button. To clear the server history long-press the triangle button. If you run DNS on your network or connect over a WAN you can enter any alphanumeric
host name by turning on "Enter alpha server name" in app settings.

 

Equalizer (Graphic Equalizer, eq)

You can improve the sound of your music using audio equalizer and bass boost/surround controls. Press the menu button (three dots) and select “Equalizer”. Turn it on, then adjust as desired. Note: Headphones/Bluetooth must be connected to 
adjust Bass Boost. Turn the equalizer off to hear the sound without any effects or eq. If the equalizer doesn’t work, see Troubleshooting below.

 

SoundWire Full Version and Multiple Connections

The full version of SoundWire fully enables Opus audio compression and supports up to 10 connections at once, allowing many different Android devices to receive audio from the server at the same time. It also has a special Pro Mode to set and 
display buffer latency precisely in milliseconds. SoundWire full version has no ads and no identification voice. For best use of wireless network bandwidth when running several connections you should turn on compression in each Android device 
and connect the SoundWire Server computer to your network using a cable, not wireless.

 

Changing SoundWire Settings

Press the menu button (three dots) and select “Settings” to change SoundWire settings. Some setting changes require SoundWire to reconnect, so you may hear a momentary audio gap.

 

Audio buffer size: This setting controls audio latency. Small buffer sizes give lower latency (shorter audio delay), but can cause choppy sound. Large buffer sizes help eliminate choppy sound, but increase latency. At low buffer sizes 
SoundWire is fast enough to play audio from movies while watching in real time, although you will need a good WiFi signal and may still notice minor audio glitches. Some Android devices may not handle very small buffers well, if so then 
increase the buffer size. Don’t use a Bluetooth speaker/headset when you want low latency because Bluetooth often has terrible latency. When you don’t need very low latency select a larger buffer size like 128k. With the SoundWire full 
version app you can set the buffer size precisely in milliseconds when Pro Mode is enabled. Note that some Android devices place a fairly high limit on the minimum buffer size when not using native audio, so you may want to set native 
audio to “Auto” in app settings if you haven’t already. Phones and tablets which support Android low-latency audio should also have native audio set to “Auto” for best latency performance, with the correct audio sample rate set at the server. 
See “Android Native Audio” below for additional tips on latency.

 

Audio compression: By default SoundWire sends uncompressed audio (PCM) over the network. Turning on audio data compression greatly reduces the required network bandwidth by 90% or more, with virtually no increase in latency. The default bit
rate is 128 kbps but may be changed to 256 or 64 kbps (VBR target rate). SoundWire uses the advanced Opus codec which has excellent sound quality at 128 kbps, so you should not normally need to change the bit rate. For voice-only audio a 20 kbps rate
is provided, but be careful not to use this setting for music since it results in low-quality monophonic sound. Turn on compression whenever reduced data usage is desirable, e.g. weak WiFi signal or with cell networks. Compression can reduce audio
dropouts and make latency more consistent if your WiFi performance is poor. SoundWire may use slightly more battery power when compression is on. Compression requires the full version of SoundWire, in the free version compression will work for a 10 minute 
trial period.

 

Connect on start: Connect to the server as soon as the app starts. Uses the last server address entered, or auto-locate if the server address box is blank.

 

Auto reconnect: Keeps trying to reconnect continuously if the server connection is lost. This may help if you have a poor WiFi connection. Use the “Disconnect” button Ⓧ to stop trying to connect. Note that when this option is on you should
always exit SoundWire when you’re finished using it, or disconnect, otherwise your phone will stay awake and run down the battery.

 

Auto reconnect on settings change: Normally on, turn this off to prevent audio interruptions when changing settings. If turned off you’ll have to disconnect Ⓧ and reconnect manually to make certain setting changes take effect (as indicated by a brief message).

 

Enter alpha server name: The server address entry field normally uses a numeric on-screen keyboard for convenience when entering IP addresses. If you’d like to enter host names (alphanumeric) then enable this setting. You may also need to enable this
setting in rare cases if your numeric keyboard doesn’t include a dot. 

 

Android Native Audio: This option is provided because on some phones native audio works better and on some phones the regular audio path works better. Native audio is an alternate internal audio path (OpenSL ES) which may perform better 
(e.g. fewer dropouts) or have lower latency on some devices. There are three possible settings as follows:
     Auto – Use native audio with small buffer sizes (32k / 190 ms or less), and standard audio with larger buffer sizes. Recommended for normal use on devices that support low-latency audio.
     Standard audio – Do not use native audio. Recommended for devices that don’t support low-latency audio or devices for which native audio does not work well. The standard audio path is usually more reliable in this situation.
     Android native audio – Always use native audio. Select if the native path performs better on your device even at larger buffer sizes, for example if Auto/Standard have problems like dropouts not caused by network issues or buffer size.

 

On modern devices that support low-latency audio the low-latency support only works at a specific audio sample rate (44.1 or 48 kHz) that depends on your device. A message indicating whether your device supports low-latency and the required sample 
rate will be displayed when you click on this option. To minimize latency set your server audio configuration to match the displayed sample rate (see Selecting 48 kHz / 44.1 kHz Audio under Advanced Settings, below) and ensure the Android Native Audio 
setting is set to ‘Auto’ or ‘Android native audio’. (If you don’t see this option your phone doesn’t support native audio.)

 

Disable fast Android audio path: When low-latency audio is active your Android device routes audio using the “fast audio path”. In this situation non-essential audio processing is bypassed, including the audio equalizer. If you would like the 
equalizer to keep working when low-latency audio would normally be active use this option to disable the fast audio path. May increase latency slightly. If the equalizer is not needed keep this option off. (If you don’t see this option your phone 
doesn’t support low-latency audio.)

 

Mute audio on calls (Android 7 and lower): Normally on, turn this off to continue hearing SoundWire audio during phone calls.

 

Pro Mode: Turning on Pro Mode lets you set the buffer size precisely in milliseconds, and displays the current buffer latency in real time while connected. This is useful in situations where a specific latency is desired. A new Latency Steering 
setting appears in the settings menu to control how aggressively SoundWire attempts to achieve the target latency (approximately buffer size divided by 2). Note that the actual audio latency will be higher than the indicated audio buffer latency 
because many other factors contribute to latency, such as your Android device’s internal audio path and server-side buffering. Use your ears, not the displayed numbers, as the final judge of latency performance. Note: Pro Mode requires the full version of SoundWire.

 

Server port number: See Advanced Settings, below.

 

PC to PC Sound Transmission

You can run the SoundWire Android app on any PC under Windows or Linux using virtualization. This lets you send sound from one PC to one or several other PCs. See our simple instructions on how to run Android and SoundWire on a PC.

 

Low Latency Audio

SoundWire performance and audio latency depend on the software & hardware capabilities of your phone or tablet. Follow these steps for lowest audio latency.

·       Make sure you have a good WiFi signal with no interference, and that your wireless network infrastructure (router etc.) is working well. For example, restart your router before a SoundWire listening session.

·       Don’t use a Bluetooth speaker/headset when you want low latency because Bluetooth often has terrible latency or latency that builds up or changes arbitrarily. Used a wired speaker/headset.

·       Set a small buffer size (8 - 16k, or with pro mode on 40 - 60 ms). If you notice audio glitches then increase the buffer size or turn on compression.

·       Turn compression off in SoundWire app settings, unless you need compression on for other reasons like network performance.

·       Check whether your Android device supports low latency audio by clicking the Android Native Audio option in app settings. If a message appears which says “Your Android device supports low-latency audio at 44.1/48.0 kHz” then ensure 
native audio is set to “Auto” (or native always). If the indicated audio sample rate is not the same as being used by your SoundWire server (44.1 or 48.0 kHz) then in Windows 7/8/10 change your playback device (speaker) sample rate using the 
Windows Sound control panel. On Linux or RPi set the SOUNDWIRE_SERVER_SAMPLE_RATE environment variable to 44100 or 48000. See Selecting 48 kHz / 44.1 kHz Audio under Advanced Settings, below, for more information.

·       If your phone or tablet does not support low latency audio, try the Android Native Audio option set to Auto or Standard and choose whichever setting appears to give lower latency according to your ear (not numbers shown on screen). 
If you do not see the Android Native Audio option under Device settings then native audio is not supported on your device.

For more information see the descriptions of the Audio Buffer Size and Android Native Audio settings, above.

 

Constant Latency

Under normal conditions SoundWire allows the latency to vary over a fairly wide range for a given buffer size. This is done to minimize audio artifacts. If you need more consistent latency, for example when listening from more than one 
Android device, do the following:

·       Use SoundWire full version on all Android devices

·       Turn on Pro Mode, then set the latency steering option to "Very Tight" on all Android devices (this will make SoundWire try to maintain a specific latency)

·       Set your audio buffer size in milliseconds to 500, resulting in a target buffer latency of 250 ms. Use a lower value if you require lower latency.

You may hear more audio artifacts when using SoundWire in this way. When done you should change latency steering back to “Normal”.

 

Using SoundWire Over Cell Networks (3G/4G/5G)

It’s possible to use SoundWire over cell data networks instead of WiFi. We recommend using SoundWire full version with compression turned on. You'll need at least 150 kilobits/sec consistent download speed on your phone and should have an 
unlimited data plan. You must configure your router to forward UDP port 59010 to your PC. When connecting, enter the correct IP address or host name (don’t use auto locate). To enter a host name turn on the “Enter alpha server name” option 
in the app (otherwise you can only enter numbers). Unless your PC is connected directly to the internet, don’t use the IP address displayed by the Soundwire server. Use the IP address obtained by your router instead. You can find this address 
by by typing "what's my IP" into a Google search on your PC. If SoundWire warns that WiFi is not enabled you can ignore this warning when connecting over cell networks. Select the largest buffer size (512k) in the Android app settings, and check 
that compression is on. You might need to set an even larger buffer if you get dropouts, if so turn on Pro Mode and try a buffer size of 4000 or 5000 ms. If you set a large buffer size and see the message “Could not initialize audio playback” then 
the buffer size is too large and should be reduced, or turn on the Android Native Audio setting to allow large buffers up to 8000 ms.

 

Note that some cell providers block certain types of data like UDP or certain port number ranges, so if you have trouble try changing the port number to an unused port in a lower range (both server and client). If you're using a VPN check that it
is configured correctly or disable it.

 

Using SoundWire Over WAN

To use SoundWire over a Wide Area Network follow the same steps as for cell networks above. For example, your phone may be connected to WiFi at work or at a friend’s house and communicate with the SoundWire Server running at your home.

 

Recording Audio to a File          

On SoundWire Server press the round red button to start saving audio to a file in MP3 or WAV format. When done, press the stop button. Does not require an active connection. Note: This feature is not available on the Linux versions of the server, 
we suggest using Audacity to record audio on Linux. If you need to edit or change levels in your saved MP3 music without reencoding try the excellent mp3directcut.

 

Using SoundWire With Bluetooth Tethering

It's possible to use SoundWire over a Bluetooth tethering network connection. This may be useful if you have a poor WiFi signal, or no WiFi access point. Follow these steps.

·       Set up Bluetooth tethering between your PC and Android device (phone) in the normal way.

·       To test that it's working, disable the regular network/WiFi on your PC and check that the PC can access the internet through your phone's internet connection (if phone has one).

·       Auto-locate won't work, so you'll need to enter the correct IP address in the SoundWire app. The Bluetooth IP address may not be displayed by the server, to find the address do this: In Windows open a command window (cmd). Type 
'ipconfig' and look for "Bluetooth Network Connection", IPv4 Address. Use this address in the SoundWire app.

·       If the address starts with 169.254 then your Bluetooth tethering connection did not obtain an IP address properly, disconnect Bluetooth and try again.

·       If sound is choppy your Bluetooth tethering connection may be too slow, turn on compression or increase the audio buffer size.

It’s also possible to use SoundWire over WiFi tethering or USB tethering using a similar procedure.

 

How to Stream Both Microphone (Headset Mic) and Speaker Audio From Your PC to SoundWire

In SoundWire Server make sure your speaker output is selected (normally “Default multimedia device”). Then in Windows,

 

1.  Right click on the small speaker icon 🔊 in the bottom right of your PC screen. Select Recording devices tab.


2.  Select your microphone in the list, click Properties (or double click on the microphone entry).


3.  Switch to the “Listen” tab, check “Listen to this device”. Click Ok.

 

While Listen is checked your microphone will be audible through your speakers so you may want to turn down your speakers. You should hear both your microphone and your speaker output in SoundWire. If you mute your PC speakers this might 
block microphone audio, so unmute and turn your speaker volume very low. 

 

Other Useful Apps

You may want to use an Android remote control app together with SoundWire to control PC music software from your phone. Some good choices include: Unified Remote, VNC Viewer

 

Troubleshooting Tips

*  Can’t connect/locate server: Check the network connections on your phone and PC. Auto locate may not work in some cases, so enter the correct server address. In some cases the server might not display the correct address, e.g. multiple network interfaces,
*  or server is behind a router. On Windows hover your mouse over the displayed address to see all network addresses (IPv4). Check your firewall settings on the PC. When you first start SoundWire Server it should ask you to allow a firewall exception
*  ("Windows Firewall has blocked some features of this app"), you should answer yes ("Allow access"). You can uninstall & reinstall the server to get this question again (if it doesn’t appear the exception is in place). You may need to manually
*  open a firewall port -- the default port number is 59010 UDP, and 59011 UDP for auto locate. Depending on your network configuration, you may need to open or forward ports in more than one place (e.g. multiple routers/firewalls). In rare cases
*  you may need to change the port number used by SoundWire. To change the port number see Advanced Settings, below. Ensure that the server level meter shows sound being played. If the server reported an error such as “unable to activate audio device”
*  and the level meter isn’t moving then connections will fail until you successfully select an audio input.

*  Audio is choppy: First try restarting your wireless router. Try selecting a larger buffer size in the SoundWire app settings. Also try turning on audio compression. If this doesn’t help you probably have a poor WiFi connection. You will need a
*   fairly good WiFi signal (2 to 4 bars out of 4) to avoid choppy sound and dropouts. SoundWire shows a warning if you have 2 bars or less out of 4. Heavy network use by other computers on your home network, or high CPU use by other programs
*   running on your PC or phone can also cause choppy sound. Some network problems like interference can cause choppy audio even with a strong WiFi signal. Try setting your wireless access point to a different channel. If your access point has
*    simultaneous dual band try disabling one band. Try changing the Android Native Audio setting (see above under Changing SoundWire Settings).

*  Volume level is too low: Try turning up the volume in your PC music player software and on your phone. On Windows 7/8/10 ensure the SoundWire Server “Audio Output” level is all the way up and unmuted. If the server shows an “Audio Input”
*  slider try turning it up. On some phones you may need to use a different audio path – try setting Android Native Audio to “Standard” in settings, then set it to “Android Native Audio” and see which one sounds best (if there is no difference
*  keep it on “auto”). If volume is still too low on Windows 7/10 open the volume mixer by right-clicking the small speaker icon 🔊 on the bottom right of your screen and selecting “Open Volume Mixer”. Find the volume control for your music player
*   software or web browser and turn it up to the line (not higher, because that may mess up other levels). On Linux try adjusting levels in Pulse Audio Volume Control.

*  Volume level is too high (level meter shows red frequently or sound is distorted): Turn down the volume in your music player software. If the server shows an “Audio Input” slider adjust it first.

*  Equalizer doesn’t work: The equalizer may not be supported on older Android devices. In this case the Equalizer menu option won’t appear. If the equalizer option appears but doesn’t seem to work at certain times, turn on the “Disable fast Android
*   audio path” option in app settings. If it still doesn’t work try setting Android Native Audio to “Standard” in settings.

*  Can’t turn down PC speakers without losing SoundWire audio: Your PC may not allow you to turn down or mute the speaker output without affecting the sound transmitted by SoundWire. If muting the speaker also cuts out SoundWire audio then you
*  must keep the main speaker volume turned up and unmuted. In this case you can silence laptop or tablet PC speakers by plugging something into the headphone jack like a connection cable or spare headphones. On Linux you can silence speakers by
*  selecting profile “off" in the Pulse Audio Volume Control configuration tab.

*  Latency (audio delay) is long: See the section on Low Latency, above.

*  Audio is smooth but quality is bad or not enough bass (server on laptop or tablet): Your PC may be processing audio in an undesirable way, for example laptops may reduce bass to avoid overloading tiny built-in speakers. To fix it go into the
*  Windows Sound control panel, playback device properties, and turn off all sound effects and enhancements like SRS, e.g. Realtek Audio Manager. Also if compression is enabled in the SoundWire app make sure the bit rate is set to 128 kbps or higher.
*  If you've ever turned on the Android equalizer/bass boost/surround in SoundWire then open the equalizer controls (menu > Equalizer) and turn it off. On some phones you may need to use a different audio path – try setting Android Native Audio to
*   “Standard” in settings, then set it to “Android Native Audio” and see which one sounds best (if there is no difference keep it on “auto”).

*  Can't enter a server address/name with letters or dots in it: Turn on the "Enter alpha server name" option in app settings.

*  Message “Could not initialize audio playback” appears when trying to connect after setting a large buffer size: This can be caused by buffer size limits on certain Android devices when using the “standard” audio path. Reduce your buffer size setting.
*  If you really need a very large buffer then go to the Android Native Audio setting and change it to “Android Native Audio”, this enables buffer sizes up to 8000 ms. 

*  Audio gets choppy or stops when screen turns off: This is a known problem with WiFi on some older Android devices when on battery power. You might be able to fix it by changing WiFi settings: Go to WiFi preferences > Advanced. If you see the option
*   “Keep Wi-Fi on during sleep” change it to “Always”. If this doesn’t help, enable the SoundWire “Screen On Wake Lock” option, or plug in your phone.

*  Can’t capture speaker output, Stereo Mix not available (Windows XP only): Some PC sound hardware doesn't support capturing speaker audio from Wave Out Mix / What U Hear / Stereo Mix. You may be able to activate the stereo mix option in settings.
*   Alternatively use a short patch cord with two 1/8" stereo plugs to connect your PC audio output to the input, then select “Line In” or “Microphone” in SoundWire Server. More information and pictures here. Consider upgrading to Windows 7 or later
*    since these versions of Windows do not need Stereo Mix to monitor the audio output.

*  Can’t capture audio from a Windows 7/8/10 application: Some professional music applications on Windows access the audio hardware in “exclusive” mode, or use third-party audio drivers like ASIO. This prevents SoundWire from capturing their audio.
*   Try the patch cord trick described above. This problem can also be caused by DRM music material.

 

About SoundWire Audio Communication

Capturing and streaming audio in real time with low latency is not easy. Even minor network communication dropouts can make audio sound choppy. SoundWire communicates with the server using an optimized reliable network protocol, and uses concealment 
techniques to make dropouts hard to notice if they occur and can’t be corrected in time. Increasing your buffer size setting will make audio smoother but also increases latency. Turning on audio compression can also reduce dropouts by reducing network load.

 

Advanced Settings

Multichannel Audio / Surround:    

Your Windows speaker outputs may be configured for 5.1 or 7.1 surround sound, or some other multichannel configuration using the Sound control panel (if supported by your audio hardware). In this case you can choose which pair of channels to send 
to your Android device using controls which appear in the SoundWire Server window. Depending on the number of surround channels available you can choose between the following options:

·       Front L/R – front left and right channels

·       Fr C/LFE – front center and LFE (low frequency sounds)

·       Side L/R – side left and right channels

·       Back L/R – rear left and right channels

Normally you should choose Front L/R, which is the default setting.

 

Selecting 48 kHz / 44.1 kHz Audio: To switch between 48 kHz and 44.1 kHz sample rate audio you must configure your SoundWire Server computer appropriately. On Windows 7/8/10 set the sample rate for your speaker output to 48000 or 44100 in the Windows
Sound control panel (right click on the small speaker icon 🔊 in the bottom right of the screen, select Playback devices, find your speakers in the list, click Properties, Advanced). When done restart SoundWire Server. On Linux and Raspberry Pi define 
environment variable SOUNDWIRE_SERVER_SAMPLE_RATE giving it the value 48000 or 44100. Make sure to configure the Linux Pulse Audio sample rate to match, otherwise sample rate conversion will be required, reducing audio quality and placing extra load on
the CPU (see Linux README.txt). When done restart Pulse Audio and SoundWire Server. Note that using the 48 kHz setting may reduce sound quality for typical audio sources like web sites and MP3 files because sample rate conversion from 44.1 to 48 kHz is 
required. However some Android devices may need 48 kHz audio to enable low-latency audio support. Unless you know your audio source material is 48 kHz you should use 44.1 kHz audio with SoundWire Server (the server may warn you about this when it starts,
one time only). An exception to this rule is if your Android device supports low-latency audio at 48 kHz and you want to minimize latency, then you should configure the server for 48 kHz (see the description of the Android Native Audio setting above for details).

 

Network Port #: To change the network port number used by SoundWire Server set the environment variable SOUNDWIRE_SERVER_PORT to the desired number and restart SoundWire Server (see instructions for setting environment variables in Windows here). 
You must then set the same port number in the SoundWire Android app, under advanced settings. You can also enter the port number after the server address separated by a colon or comma, e.g. 192.168.1.149:50000 or 192.168.1.149,50000. Soundwire also 
uses the next port number (one higher) for auto locate. You can use command line parameters to set the port number when starting SoundWire Server instead of the environment variable, see “Multiple Audio Channels Using Multiple Network Ports” below.

 

Multiple Audio Channels Using Multiple Network Ports: SoundWire Server normally lets you run only one instance of the program, allowing you to stream one stereo audio channel from that PC. Under Windows and Linux it’s possible to run multiple servers, 
each set to a different network port number. Then by selecting a different audio source for each server instance you can stream multiple stereo audio feeds (or different surround channel pairs) to different Android devices. You must start each instance 
of SoundWire Server using the -p command line option to set its port number, for example

         SoundWireServer –p 59010

         SoundWireServer –p 59020

         SoundWireServer –p 59030

This runs three instances of the server set to use the indicated port numbers. In the Android app set the desired port number under advanced app settings, or enter the port number after the server address separated by a colon or comma. Change the port 
number to listen to a different audio source. Don’t forget to open the additional ports in your firewall(s). An easy way to specify the -p command line option is to add it in the target string of a desktop shortcut. Create multiple desktop shortcuts for
the SoundWire Server program, then edit shortcut properties to make each target string specify a different port number. When using SoundWire Server in this way each server instance shows its port number in the title bar for identification. On Linux use 
Pulse Audio Volume Control to select different audio sources for each SoundWireServer instance.

 

Browsable Intent: Use the following HTML link to open SoundWire:

         <a href="soundwire.georgielabs.net:">

This will open the SoundWire full version app if present, otherwise it will open the free version.

 

Music Level Meters and Visualizers

The SoundWire Android app has a minimal user interface with no audio level meters or visualizers. We expect that you’ll switch away from the app as soon as music starts playing. Instead, SoundWire sends accurate stereo metering data to GeorgieLabs Music 
VU Visualizer Widgets app (if installed). Music VU can be used to display audio level meters, spectrum graphs and waveform visualizers on your home screen while listening to SoundWire. Music VU visualizers also work with other music players on your Android device.

 

User Feedback

Please rate the app and submit comments on Google Play to let us know what you think of SoundWire, or send email to soundwire@georgielabs.net. If you’d like a response you should use email. Possible future SoundWire features include:

Mac OSX version of the server
Phone to server / phone to phone sound transmission (currently limited by Android OS)
 

Let us know what features you'd like to see, or if you have a bug to report. If you enjoy using SoundWire please consider supporting the developers by purchasing the full version. Note there is no iOS version of the app – we have good evidence that 
SoundWire would be rejected by Apple.

 

Go to the GeorgieLabs main page.

 

SoundWire free version privacy policy.

SoundWire full version privacy policy.
