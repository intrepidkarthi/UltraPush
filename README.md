UltraPush notification receiver based on Ultrasound 
===================================================

Usecase:
You are rushing to a busy railway station in India to catch your train. But unfortunately your train was delayed by 30 minutes. You are just walking around the platform. You just crossed a advertisement kiosk/TV over there. And for your surprise, you received a notification on your phone saying "You are at Bangalore Railway Station. Go and have a coffee at Cafe Coffee Day 25 metres ahead from here. Use this coupon: Happy50 and get 50Rs discount. Enjoy your coffee!". This is awesome. How is it even possible? 

How?
We generate ultrasound frequencies above 16KHz which is above the audible range for a human. Our servers will do spectrum allocations for advertisements and map it to frequencies and offers. And whenever you see the advertisement at a kiosk, it will play the advertisement and also the inaudible audio. On the other side, you already have paytm, flipkart, snapdeal, myntra or Amazon apps on your mobile. They have our SDK integrated inside their app already. When ever you pass by the kiosk or TV, you will get the offer that is mapped to the particular adertisement. 


Thanks for this awesome library which was really useful for this experiement. 

>  A fork of [Audio spectrum Analyzer for Android](https://code.google.com/p/audio-analyzer-for-android/) (See README.old for its original readme)

  This software shows the frequency components' magnitude distribution (called spectrum) of the sound heard by your cell phone.

  This software, [Audio Spectrum Analyzer for Android](https://github.com/bewantbe/audio-analyzer-for-android), is released under the Apache License, Version 2.0.


Installation Requirements
-------------------------

* >= Android 2.2 (API Level 8 and above)
* External storage (e.g MicroSD card), if you want to record the sound.


Development
-----------

git clone then open it use Android Studio. Install the SDK platform if requested (e.g. rev 116 need API level 20), or tune the android:targetSdkVersion to the value that fit your needs.

