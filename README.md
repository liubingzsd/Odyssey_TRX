

<p>The source code for Odyssey TRX project.</p>

<p>Was compiled with Altera Quartus II 13.1 Web Edition for EP4CE22F17.</p>

<p>For changing IP-address edit the ethernet.v 100-103&#39;s lines. The second receiver's IP will IP + 1.</p>

<p>Since version 1.3.3 IP and MAC adress possible to change without reprogramming board using  the  <a href="http://www.sdr-deluxe.com/load/0-0-0-30-20" target="_blank" title="Odyssey Key Master 1.1 ">Odyssey Key Master 1.1 </a> </p>

<p>For programming the board use <a href="https://drive.google.com/file/d/0BzuiSb2tJSbzZFNFWmpxTUFkUHc/view?usp=sharing" target="_blank" title="Altera Quartus Programmer ">Altera Quartus Programmer </a>(185Mb) and <a href="http://www.aliexpress.com/wholesale?catId=0&amp;initiative_id=SB_20160110085258&amp;SearchText=usb+blaster" target="_blank" title="Altera Byte Blaster hardware ">Altera Byte Blaster hardware </a></p>

<p>Version history:<br />
1.0.0&nbsp;&nbsp; &nbsp;&ndash; 11.08.15 - First base version<br />
1.1.0&nbsp;&nbsp; &nbsp;&ndash; 11.09.15 - Added automatic key and expanded protocol to support key control that work with Odyssey Key Master<br />
1.1.1&nbsp;&nbsp; &nbsp;&ndash; 03.10.15 - A few bugs fixed:<br />
&nbsp; &nbsp; &nbsp; &nbsp;-&nbsp;&nbsp; &nbsp;Incorrect work of PTT in straight key mode<br />
&nbsp; &nbsp; &nbsp; &nbsp;-&nbsp;&nbsp; &nbsp;Incorrect work of the Demo mode<br />
1.1.2 &ndash; 22.10.15 - PTT control signal is now straight, not inverted; control connector pinout was also changed&nbsp;<br />
1.2.0 &ndash; 26.10.15 - openHPSDR protocol is supported<br />
1.2.1 &ndash; 28.10.15 - openHPSDR protocol bug fixes, SNDP support has been removed<br />
1.2.2 &ndash; 19.11.15 &ndash; was added stereo output in Headphones<br />
1.3.0 &ndash; 6.12.15 - &nbsp;was added the second independed receiver <br />
1.3.1 &ndash; 12.03.16 - &nbsp;CW and SSB output level balanced, Demo mode blink indication added<br />
1.3.2 &ndash; 26.04.16 - &nbsp;Sound and TX buffer were enlarged twice and combined. The self-monitoring in SSB mode doesn't work now.<br />
1.3.3 &ndash; 06.06.16 - &nbsp;Possible to change IP and MAC adress trough OKM 1.1 or higher <br />
1.3.4 &ndash; 25.07.16 - &nbsp; Bug-fix, critical error with PTT mode <br />
1.3.5 &ndash; 19.09.16 - &nbsp; numerous changes for keying, second receiver only up to 192k <br />
</p>
