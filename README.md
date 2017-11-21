<h4>Arduino</h4>
<h2>Ultrasonic Xylophone (A.U.X)</h2>
<h6>by Katharina Matheis</h6>
<img class=" wp-image-589 aligncenter" src="https://componto2017.edublogs.org/files/2017/11/profile-2nj5shr-1rlkcy6-300x169.png" alt="" width="486" height="274" />

Parts I used for this project:
<ul>
 	<li>Arduino Uno</li>
 	<li>Breadboard</li>
 	<li>a speaker</li>
 	<li>HC-SR04 Ultrasonic Sensor</li>
 	<li>Wires</li>
 	<li>Tape</li>
 	<li>Cardbord and paper</li>
 	<li>Soldering Iron</li>
 	<li>Scissors and Pencils</li>
</ul>
After assembling all the stuff and making a plan of things I had to do to finish this project it was fairly easy to follow through with it. There are a lot of people on the internet who made<a href="http://www.instructables.com/id/AUMI-Arduino-Ultrasonic-Musical-Instrument/"> similar projects</a> and I could follow their instructions for the most part.

I started out with writing the code. The tricky part was including the Ultrasonic Sensor. Since I have never worked with one before let alone understood how it worked. So I had to get familiar with it and did some research. <a href="http://howtomechatronics.com/tutorials/arduino/ultrasonic-sensor-hc-sr04/">This</a> site helped me a lot.

At the beginning of the code I defined where (what pin in the Arduino) the speaker, the trigger and echo of the sensor will be located. After that I had to make sure that sound would come out of the speaker at some point. I looked up how to do that and came up with this picture. I used it to establish the frequencies of every note on the scale.

<a href="http://www.sengpielaudio.com/KeyboardAndFrequencies.gif">
<img class="size-medium aligncenter" src="http://www.sengpielaudio.com/KeyboardAndFrequencies.gif" width="798" height="183" /></a>

The HC-SR04 is good for measuring distance so I build that into my code. I wanted every note to have a 3cm wide key. Additionally the scale had to start a few centimeters away from the sensor otherwise it would probably be hit every time someone played the xylophone. I defined the intervals of the notes in the code.

You can find my code on <a href="https://github.com/katham/componto-project-2017/tree/master">github</a>.

<img class="wp-image-591 alignright" src="https://componto2017.edublogs.org/files/2017/11/IMG_1617-110ztpm-2ftqiei-768x1024.jpg" alt="" width="463" height="617" />

This is how the circuit looked when it was finally completed and working.

In order to be able to play the instrument I build a "keyboard" where I drew the sections for every note from C to c'. Later on I realized that H is actually B in English. I am sorry if that caused some confusion.

To make the whole thing look more beautiful and sturdy I built a customized box in which the speaker and sensor would fit. After soldering the wires to the sensor and speaker I put all of it inside the box and secured it with tape. The box had to have two holes in the front so the sensor could actually sense when the ultrasound would be reflected. I wanted to also cut a hole for the speaker but I quickly found that it was still loud enough, even when in the box (especally when the high c was played).

What was supposed to be the fun part of this project quickly turned out to be quite disappointing and exhausting. Playing the xylophone is tricky and it takes practice time to master it. Finding a "stick" was not as easy as I supposed. It had to have a flat surface to play a clear note and be wide enough so that the sensor could detect it. In the end I used a piece of cardboard that my cats could spare. me.

To summarize the project I filmed most of the working progress. At the end of the video I give a short sample on what you can play on the A.U.X..

I apologize for the inconvenient perspective. But I only belatedly realized that filming with my phone upright was not the best idea.

<hr />

[embed]https://youtu.be/c6DZRo5mS80[/embed]

<hr />

I could extend the project by adding semitones to the scale or building a second instrument so that it would be possible to play with two hands.


