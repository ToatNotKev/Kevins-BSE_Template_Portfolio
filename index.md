# Magic Mirror!
My project is the magic mirror which has a two-way plastic mirror with a monitor behind connected to a Raspberry Pi with the magic mirror software downloaded onto it, it will be in my bathroom and it has features like showing my calendar or the time, also at the bottom it displays news. Some big hurdles I have encountered were mostly on the software side of things but the mirror I had was damaged when heat was applied to it whilst trying to fix some scratches so a new one was needed. But now a protective plastic will be put in front of it to prevent any damage to the new one.

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Kevin M | Eastside College Prepatory | Electrical Engineering | Rising Softmore

<!--**Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.** -->

![Book logo](/least-github-pages/assets/logo.png)

# Final Milestone
 
 <iframe width="560" height="315" src="https://www.youtube.com/embed/s9gNZv4vyJo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For my final milestone, I added three modules: a remote module that lets you remotely change the Magic Mirror's appearance and brightness using a web page in your browser; a moon module that tells you what state the moon is in; and a stock module that uses the Yahoo api to display the stock prices of my four favorite stocks. The Raspberry Pi's IP address is used in this, and it is added to the IP WhiteList in the configuration file that is located in the Magic Mirror file. The IP address is then set to "0.0.0.0" in the cofig.js file. Once this is finished, a link will appear on the Magic Mirror program, which you may copy and paste into your browser to operate the mirror. My preferred price for firm shares is paid for my second module, the stock module. As an illustration, I included Apple, Microsoft, Amazon, and Tesla. The price of the stock changes from red to green depending on whether it has increased or decreased in value. It also displays the % change in price and lists the name of the company to the right of the price.You can increase the capability of the Magic Mirror software and alter the data shown on your smart mirror by adding modules to it. Because Magic Mirror is an open-source software built on Node.js, you may add new modules or use ones that are already available to improve the user experience. You can get these different modules from the community of third-party modules on github. Here is a step-by-step tutorial on adding a module.

Prerequisites:

Make sure the Magic Mirror program is installed and activated on your device. Follow the installation instructions listed on the Magic Mirror website if you haven't already done so.
Basic understanding of JavaScript JavaScript proficiency is required to comprehend and change the modules.

Step 1: Select a Module:
Choose the module you wish to add first. On GitHub, you may find a variety of modules developed by the Magic Mirror community. attempting to find modules that meet your requirements and choices.

Step 2: Download the Module:
Once you've chosen a module, download it from the repository or the source provided by the module's creator. Usually, you can find the module's GitHub repository and download it as a ZIP file.

Step 3: Install the Module:
Extract the contents of the ZIP file into the Magic Mirror's modules folder. The path to the modules folder is typically ~/MagicMirror/modules/.

Step 4: Configure the Module:
Each module comes with its own configuration options, allowing you to customize its behavior. Navigate to the Magic Mirror's config folder, and open the config.js file in a text editor.

Step 5 : Add the module code onto the config file 
Locate the modules array in the config.js file. This array contains the configuration settings for all the modules you have installed. Then add the code provided by the creator in git hub onto the config.js file. 

Step 6: Install Module Dependencies (if any):
Some modules might have additional dependencies required for them to function correctly. If that's the case, follow the instructions provided in the module's documentation to install those dependencies.

Step 7: Restart Magic Mirror:
After adding the module and making necessary configurations, save all your changes and restart the Magic Mirror application. You can usually do this by stopping and then starting the Magic Mirror server.

Step 8: Customize the Module (Optional):
Once the module is up and running, you can further customize it according to your preferences. Check the module's documentation to explore the available customization options.

Step 9: Troubleshooting:
If you encounter any issues during the installation process, refer to the module's GitHub repository or the Magic Mirror forums for troubleshooting tips. You can also seek help from the Magic Mirror community.

Congragulations! You have know added a modules to your Magic Mirror software!

# Second Milestone     

 <iframe width="560" height="315" src="https://www.youtube.com/embed/NBVdRB1cJaQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

  I assembled the mirror for my second milestone, and I faced a lot of hurdles along the way. To assemble the mirror, I had to cut a piece of wood to the dimensions of the mirror frame which was 18 by 24 inches with a jigsaw. To fit the monitor in the piece of wood, a rectangular hole was to be made by cutting holes on every corner of the rectangle with a drill bit whose diameter was the same as the length of the jigsaw blade, you can't just stick the jigsaw into the wood and expect it to cut the wood, that's why the holes were needed. If it was not cut with the right drill bit the hole could be excessively big or too small for the jigsaw blade to fit. After those holes were made, an instructor cut everything with a jigsaw for me. After this step, I painted the wood black so almost no light would be reflected the user of the mirror. Because I was working with a double-sided mirror which means it is reflective on both sides and semi-transparent. This was a problem that had to be dealt with if I wanted the finished mirror to look presentable. 

  Finally, I got to add the LEDs which would look like a strip of light glowing through the mirror. These LEDs were placed on the opposite sides of the mirror vertically. A routing tool was used to make the crevices into the wood so the LEDs could be put in place, and a drill was used to make holes so the USB cable could be routed to the back of the mirror and connected to a power brick. I later sautered the two usb wires coming from the LEDs. After turning both the LEDs on, I noticed that hot spots could be seen through the mirror. To defuse these hot spots I tried countless items ranging from paper to hot glue sticks, item after item- none of them achieved the level of diffusion I was looking for. After some time, an instructor suggested using white electrical tape and black electrical tape to cover the excess white tape that would be seen through the mirror. It worked a lot better than I anticipated so I decided to keep the tape on the wood. Now attaching the display to the wood and the wood to the mirror frame was a problem. The mirror was not difficult to install because it sat snugly between the wood and the frame. Everything else though would have been a headache, if I wasn't the first person making this. Lucky for me, a tutorial was provided in the student resources folder. After watching the tutorial, I screwed the frame onto the wood and attached the display to the wood via nylon straps looped through the display's VESA mount. To attach the nylon straps to the wood I used a grommet tool to apply grommets (little metal rings if you will) to the holes on the nylon straps. This was a one-step process with the tool. Then, it was just a matter of screwing the little metal holes into the wood. 
  
  A challenge that I faced was the Raspberry Pi not fitting on the back of my display, so I took it out of its casing which also served the purpose of a keyboard and taped it onto the monitor with double-sided tape, PCB exposed, and everything. The PCB was too exposed, so I had to cut the bottom half of the keyboard casing to serve as a protective shield for the Raspberry Pi.

# First Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/ZpdhrvoJoVc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

I succeeded in getting the code to run the magic mirror software on my Raspberry Pi 4. But before this, I had to install the thirty-two-bit raspberry pi os onto a micro sd card and a student named Hari downloaded the os on the micro sd card so props to him.  After installing the os I ran some commands on the raspberry pi terminal to download the files to install the magic mirror software. These commands were the following, 

~~~
git clone https://github.com/MichMich/MagicMirror
~~~
which retrieves all the file data from git hub and then after running the command 
~~~
cd MagicMirror/
~~~
to store all that information onto a file with that name. Then you tell the computer to install all that data by saying 
~~~
npm run install-mm 
~~~
After this, you have all this data on your Rasberry Pi you have to get it from the configuration file which contains all Magic Mirrors software code. That is done by entering 
~~~
cp config/config.js.sample config/config.js
~~~
finally you tell the computer to use all that data and make something of it, in other words, we tell the computer to boot up the software by entering 
~~~
npm run start
~~~
and the magic mirror software boots up! Now after it boots up it shows the current time on the top left of the display and under that is a list of American holidays on a Google calendar I am hoping to connect my Google calender to it so when I wake up and go to the bathroom and can see how the day ahead of me is going to look like. There is a weather feature as well on the top right corner of the software but that still needs to be set up that the moment. Getting the actual software to boot up was not that difficult, the most time-consuming part was getting the Raspberry Pi os up and running and making an account on the Raspberry Pi. I hope shortly during my time at Bluestamp I can add more modules like the stage of the moon and stock prices for different companies. I also hope to add a sensor to detect motion so the mirror isn't on all the time-wasting light, I don't think my parents would be happy if the light bill skyrockets because of me.  

# Starter Project 

<iframe width="560" height="315" src="https://www.youtube.com/embed/mjSBqs2uI4M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For my starter project, I chose the useless box. A device whose sole purpose is to turn itself off is referred to as a useless machine or useless box, in which the object’s only purpose is to turn itself off by activating its own “off” switch when powered. I chose the useless box because it looked interesting and I wanted to figure out how the little arm came out of the box and turned the switch off. There is a little led that turns green when the arm is coming out and red when it flips the switch off. Inside the box, there is a servo that is attached to the arm powered by three triple A batteries. The arm has extra material at the end which hits a switch when in its off position so the led only turn on when the arm is in motion . Some challenges when making the useless box were getting all the box walls is aligned with the top of the useless box. 

<!---# Code 

```c++
void setup() {
  // put your setup code here, to run once:
  Serial.begin(9600);
  Serial.println("Hello World!");
}

void loop() {
  // put your main code here, to run repeatedly:

}
```-->

# Bill of Materials

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Sceptre Monitor 22in | Will be used as display for magic mirror | 80$ | <a href="https://www.amazon.com/Sceptre-E225W-19203R-Monitor-Speakers-Metallic/dp/B07774L6TT/ref=sr_1_2_sspa?crid=3MJ0X4FK9FMA4&keywords=scepter+22+in+monitor&qid=1687448462&sprefix=scepter+22+in+moti%2Caps%2C629&sr=8-2-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1"> Link </a> |
| Two way Mirror | Will serve as the mirror for the project and is key becasue it is a two way mirror wich will let the display be noticable through the mirror | $36 | <a href="https://www.amazon.com/0-04-Acrylic-See-Through-Mirror-Transparent/dp/B01CZ35XWY/ref=asc_df_B01CZ35XWY/?tag=hyprod-20&linkCode=df0&hvadid=216545230264&hvpos=&hvnetw=g&hvrand=7657619439256980177&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9032183&hvtargid=pla-350616698391&psc=1"> Link </a> |
| Rasberry Pi 400 | Its the brains/computer of the project and will run the magic mirror two software on the display | $100 | <a href="[https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/](https://www.amazon.com/Raspberry-400-Computer-Kit-RPI400-US/dp/B08MYVQW1S/ref=sr_1_3?keywords=raspberry+pi+400&qid=1687448757&sr=8-3)"> Link </a> |
| Full Motion TV wall mount | Will hold the display and mirror in place on the wall | $16 | <a href="https://www.amazon.com/Mounting-Dream-200x200mm-Articulating-MD2465/dp/B08QD61K9N/ref=sr_1_3?crid=2PGD931YN36XV&keywords=tv+wall+mount+MD2465&qid=1687448921&sprefix=tv+wall+mount+md2465%2Caps%2C146&sr=8-3"> Link </a> |
| Triple outlet triple USB power strip | Is attached to the back of the mirror and all cables will be attached to it, serves as a power strip| $12 | <a href="https://www.amazon.com/Extension-Outlets-Braided-Listed-Compact/dp/B07WJG8K85/ref=sr_1_5?crid=28I8LBFK25F2V&keywords=mifaso%2Bpower%2Boutlet&qid=1687449088&sprefix=mifaso%2Bpower%2Boutlet%2Caps%2C219&sr=8-5&th=1"> Link </a> |
| Mirror frame | Will hold the acrylic two way mirror in place and the wood surounding it  aswell as the monitor| $23| <a href="https://www.amazon.com/MCS-Industries-63737-Gallery-Woodgrain/dp/B0817D3QS8/ref=sr_1_6?crid=FR9CP0BDVF8A&keywords=mcs+studio+gallery+frame+18+x+24&qid=1687449737&sprefix=mcs+studio+gallery+fram+18+x+24%2Caps%2C161&sr=8-6"> Link </a> |
| Led light strip | Will be used as backlight for mirror and will appear through the mirror in two parallel lines to iluminate your face if your awake at late at night and do not want to turn on the bathroom lights | $15| <a href="https://www.amazon.com/Flexible-Density-Kitchen-Bedroom-Decorations/dp/B09W8TPFHD/ref=asc_df_B09W8TPFHD/?tag=hyprod-20&linkCode=df0&hvadid=579642592239&hvpos=&hvnetw=g&hvrand=9887275762133190748&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9032183&hvtargid=pla-1652547000160&th=1"> Link </a> |

<!---# Other Resources/Examples

- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here.-->
