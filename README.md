Download Link: https://assignmentchef.com/product/solved-ecgr4161-lab2-downloading-installing-configuring-the-tools
<br>
<h1>Part 1:  Downloading/Installing/configuring the tools</h1>

We are going to be programming an embedded systems board using the tool “Energia” – it is an Arduino-like tool.  This board, the TI MSP-EXP432P401R, has the MSP432P401R microcontroller as its main processor.

You should go to <a href="https://energia.nu/download/">https://energia.nu/download/</a> to download the Energia tool (Mac, Windows, and Linux!).  On the page, below the link for the download are links for installing and setting up the tool.

Hint:  When you extract the files – USE THE DEFAULT PATH OFFERED!

The general steps are:

<ol>

 <li>Download the Energia software tool</li>

 <li>Download the MSP432 board drivers</li>

 <li>Unzip (extract) the MSP432 board drivers</li>

 <li>Load MSP432 drivers (see Energia instructions)</li>

 <li>Unzip (extract) Energia</li>

 <li>I suggest you create a shortcut to the Energia tool on your desktop</li>

 <li>Attach board</li>

 <li>Open Energia application (IDE)</li>

 <li>Download board package (MSP432P401R) (pull down from “Tools-&gt; Board -&gt; Boards manager”)</li>

 <li>Set board to MSP432 (pull down from “Tools -&gt; Board -&gt; Red Launchpad w/msp432p401r EMT (48 MHz)”)</li>

 <li>Set port (pull down from “Tools -&gt; Port -&gt; COMxx”)</li>

</ol>




Setup is complete and you are ready to program

<h1>Part 2:  Programming the MSP432 board</h1>

In this part you will run the Energia tool and program it to light the RGB LED with the following pattern:

Off -&gt; red -&gt; blue -&gt; green -&gt; red&amp;blue -&gt; red&amp;green -&gt; blue&amp;green -&gt; red&amp;blue&amp;green -&gt; Off (repeat) Each of these light patterns (or off) should take 0.5 seconds.  See the file on Canvas “blink.txt” for an example of turning on/off one of the colors of the RGB LED.

The video you record should be no more than 30 seconds, and should capture from the moment you start the compile operation and end after showing two cycles of the changing LED colors.