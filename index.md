# Smart Glasses
<!-- Replace this text with a brief description (2-3 sentences) of your project. This description should draw the reader in and make them interested in what you've built. You can include what the biggest challenges, takeaways, and triumphs from completing the project were. As you complete your portfolio, remember your audience is less familiar than you are with all that your project entails! -->
The Smart Glasses uses object recognition and text to speech which lets the user recognize the object without seeing it. The Raspberry Pi and camera module work together to recognize the object using a pretrained models. Then the Raspberry Pi reads the object into earbuds attached to the Raspberry Pi and glasses.


| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Derek Y | Los Gatos High School | Electrical Engineering | Incoming Junior


<img src="DerekY.png" width="300" height="400">
  
<!--# Final Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE



# Second Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VAmNlER5Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your second milestone, explain what you've worked on since your previous milestone. You can highlight:
- Technical details of what you've accomplished and how they contribute to the final goal
- What has been surprising about the project so far
- Previous challenges you faced that you overcame
- What needs to be completed before your final milestone --->

# First Milestone


<iframe width="560" height="315" src="https://www.youtube.com/embed/Oe47YTd77uI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

### Components:
My project is the Smart Glasses and there are many different parts that work together to make the glasses function. The Raspberry Pi and camera module will run the object recognition. The Raspberry Pi will get information from the camera and process it, turning the pictures into text. Then the text will be read through the earbuds which will allow the user to hear it. Finally, this technology will be attached to the glasses, allowing the user to look at an object and get audio feedback.

### Challenges
The most reccurent challenge I have faced is the remote connection not working. Normally, I would run SSH and TigerVNC, and I can directly connect to the Raspberry Pi without needing a HDMI cable. Sometimes, the connection doesn't work and it forces me to use OBS, which is highly inefficient because I need to use a different keyboard and mouse to control the Raspberry Pi. By using TigerVNC and getting the SSH to work, I can directly control the Raspberry Pi from my computer without needing external devices. This challenge can be fixed by power cycling, but it only works sometimes. 

### Build Plan
First, I set up my Raspberry Pi which was what I did for this milestone. I got the camera working and took a picture with the Raspberry Pi. Next, I have to install Tensorflow and other programs for object recognition. I will make the Raspberry Pi convert the object recognized into text to speech, which will be played through the earbuds connected to the Raspberry Pi. The audio allows the user to recognize the object without needing to see the object. This feature will be especially useful for blind people, who I am building this project for. Lastly, I will attach all the technology to the glasses and power bank to power the Raspberry Pi. This will allow the device to be portable. For my modifications, I want to add voice control. Voice control will allow the user to take a picture when the command is given, and recognize an object when prompted. Also, I can add music to the Smart Glasses.


<!--
# Schematics 
Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser. 

# Code
Here's where you'll put your code. The syntax below places it into a block of code. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize it to your project needs. 

```c++
void setup() {
  // put your setup code here, to run once:
  Serial.begin(9600);
  Serial.println("Hello World!");
}

void loop() {
  // put your main code here, to run repeatedly:

}
```
-->

### Bill of Materials

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Power Bank | Powers the Raspberry Pi | $17.99 | <a href="https://www.walmart.com/ip/INIU-10000mAh-Power-Bank-Slimmest-15W-Portable-Charger-Compatible-with-iPhone-Samsung-High-Speed-Charging-Battery-Pack-USB-C-Cables-Black/3506821403"> Link </a> |
| Respberry Pi 4 | Runs the camera module and object recognition | $55.00 | <a href="https://www.canakit.com/raspberry-pi-4-4gb.html"> Link </a> |
| Earbuds | Allows user to hear TTS feedback of an object | $14.01 | <a href="https://www.amazon.com/Earbuds-Headphones-Cancelling-Microphone-Smartphones/dp/B0CB7LM12K"> Link </a> |
| Raspberry Pi Camera Module | Lets the Raspberry Pi see for object recognition | $6.99 | <a href="https://www.arducam.com/arducam-ov5647-standard-raspberry-pi-camera-b0033.html"> Link </a> |
| Glasses | Base which the Raspberry Pi and camera is going to be mounted on | $6.99 | <a href="https://www.arducam.com/arducam-ov5647-standard-raspberry-pi-camera-b0033.html"> Link </a> |

<!--Here's where you'll list the parts in your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs. -->

### Other Resources
- https://learn.adafruit.com/running-tensorflow-lite-on-the-raspberry-pi-4/tensorflow-2-setup


# Retro Arcade Console
<iframe width="560" height="315" src="https://www.youtube.com/embed/sGJGCwsERHg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

### Summary
The Retro Arcade Console is my starter project and has many games ranging from tetris to slots. There are 5 games in total. While playing the games on the console, different sound effects play that matches up to the game. I can use 7 buttons-up, down, left, right, pause, start, and on/off-to control the console. My favorite game is space invaders, because I can shoot beams of lasers with cool sound effects. To play tetris, you can use the left and right buttons to control the orientation, and the down button to make the block go down faster. The LED display shows the game and the display board counts the score for each game. To build the Retro Arcade Console, I had to solder many parts to the PCB. 

### Challenges
Some challenges I faced were soldering and a bug in the console. Soldering was difficult for me and sometimes I would get a cold joint. The joint would be flaky and not concave. After practicing many joints on the console, I was able to solder with good joints. Another challenge I faced was a bug in the console. When I fully assembled my game console, the button's controls were flipped, so when I would start it would pause, and if I would pause it would start. I thought this was a soldering error, so I unassembled everything to resolder my joints. Even after that, it wasn't fixed and I realized the code was wrong in the board. This would explain why only on some games the pause button would work, but on others it wouldn't do anything. Because I took apart my console many times trying to fix this, it took away a lot of time and was one of my biggest challenges.

### Bill of Materials

| Part | Quantity |
|:--:|:--:|
| Buzzer | x1 |
| Electric Capacitor | x1 |
| Digitron Display | x1 |
| Self-Switch | x1 |
| Button | x6 |
| PCB | x1 |
| LED dot matrix module | x2 |
| Battery Case | x1 |



### Schematics/Images
<img src="schematics-_WNfuLqZO8t.jpg" width="80%">
<img src="71JXmf0iqKL._AC_SX679_.jpg" width="60%">


