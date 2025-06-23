# AI Voice Assistant
This project is an AI voice assistant robot that uses ChatGPT to respond to the user's voice inputted to a Raspberry Pi through a mic, and sends a response via a usb speaker. The robot has a servo for a neck and LED light rings for eyes, that give it a more desiarable appearance.
<!---You should comment out all portions of your portfolio that you have not completed yet, as well as any instructions:-->
```HTML 
<!--- This is an HTML comment in Markdown -->
<!--- Anything between these symbols will not render on the published site -->
```

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Mukhil S. | Monta Vista High School | Robotics Engineering | Incoming Senior

<!---**Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**-->

![Headstone Image](MukhilS.png)

<!---# Final Milestone

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
- What needs to be completed before your final milestone -->

# First Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/zLyGwpeoV1g?si=9J3Yrg0rfvxqdN8C" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

For my main project, I will be making an AI voice assistant robot. I will be using a Raspberry Pi to facilitate voice conversation with ChatGPT, using a mic and speaker. I will also be integrating a neck servo and led light rings for eyes, in order to give the robot a friendly complexion. For this milestone, I set up the Pi and downloaded OBS Studio on my computer to be able to access the PI. I attached an LED, that I programmed to blink using the Pi, to test if the Raspberry Pi can run code properly. 
A significant challenge I that still needs to be addressed is setting up SSH and VNC. Due to connectivity issues, I am not able to use SSH and VNC to send commands to the PI remotely, which has led me to have to use OBS studio to access the PI, making the project a little harder to work with. For my next milestone, I will be working on integrating a mic, speaker, and integrating th API key for ChatGPT, enabling the PI to facilitate voice conversation with ChatGPT.

<!---For your first milestone, describe what your project is and how you plan to build it. You can include:
- An explanation about the different components of your project and how they will all integrate together
- Technical progress you've made so far
- Challenges you're facing and solving in your future milestones
- What your plan is to complete your project

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
# Bill of Materials
<!---Here's where you'll list the parts in your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs. -->

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |

# Starter Milestone: Retro Arcade Console
<iframe width="560" height="315" src="https://www.youtube.com/embed/Fn082AnFBrs?si=fmU0VKUEW8ycNR5p" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

For my starter project, I chose the Retro arcade console. I chose it because it ivolved quite a bit of soldering, so I can get enough practice, and also because it would be a fun thing to have. It has four buttons, and a number of different games to choose from like tetris and snake. It also has a buzzer that can make sounds during games and during the startup screen. Now I will start working on my intensive project, the AI voice assistant robot.

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Retro Arcade Kit | Has all the arts to build it | $18.99 | <a href="[https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/](https://www.amazon.com/Electronic-Soldering-Practice-Comfortable-VOGURTIME/dp/B094QRRHC2/ref=sr_1_2?crid=2243TA8407LNY&dib=eyJ2IjoiMSJ9.mGDklexByNF7kCDxNu0TZ7cc60TrXXnTn9BjRFoKOcbSp_O5OT9Stw-qmtcGbvXOG9cJKwNGrWAJ8QmsHDapuoKgayg5b_K2I4y0cgUkgKudNTi7vv8NqKx2AzQ-JzkD5F3KCiwa_TkRCrh0A57FdUjvYxZtnchl11o6rEAeDolqaCzoeUQQG1q_VgTRL5kWJZ9U7Km8HzHwbw_FtNjZJX1-APH5kVh1Yhm2omZFXOqmB7soUF4rnxdsC-cApxhXyfI-zsPpIWaUTa8DOZYGO4r-9iUvz7qbYkCi62vXdBE.I1aJaN9KrzSK7cW5PG9_py9BInl57rOGzIL3BchV7W8&dib_tag=se&keywords=retro%2Barcade%2Bsoldering%2Bkit&qid=1750261647&sprefix=retro%2Barcade%2Bsoldering%2Bkit%2Caps%2C300&sr=8-2&th=1)"> Link </a> |

<!---# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)-->

<!---To watch the BSE tutorial on how to create a portfolio, click here.--> 
