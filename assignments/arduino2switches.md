---
Week 9 - Digital & Analog Switch (arduino)
---

[Video Demo](https://youtu.be/Z4Zq916oZ88)


[Code](https://www.codepile.net/pile/yO7kDxOz)

Making this assignment was so frustrating but equally as satisfying. I found that with Arduino, my coding skills feel sharper, and I feel more confident since I can immediately see whether what I am doing is working or not. I decided to go off the suggestions since I had a hard time being creative and finding another way. If you turn the potentiometer and the value is above 500, the red LED will start blinking my name in morse code. If the value is anywhere above 500, if you click the button, it will increase the brightness by 20. It's capped out at 255 before it will turn off again, which gives you a lot of variety and enough clicks to see the difference. The brightness change is done with the blue led.

![PicMOntage](https://user-images.githubusercontent.com/98391104/161433480-7b37fdda-6360-4112-abc7-6bce2aa799ab.jpeg)

I tried to keep the wiring as clean as possible, with red for positive and black for negative. While creating this piece, I used yellow for one LED and black for another. This color contrast helped me see the different wires, and at first, I had them set on one side of the breadboard. So I honestly needed to be able to see the difference. I eventually realized that it would be both simpler and cleaner on the eye if I had them on opposite ends, so I did that, and that made me see a lot of the errors and quickly correct them. When coding, I decided to do both switches in2 different files and then combine them. It got too complicated with all the other variables and values, so I resorted to two separate files, and in the end, I merged them both. Keeping the wiring clean and organized helped me see my errors and quickly identify them.

I found myself confused about which resistor to use, so I need to look into it.

Creating this assignment was incredibly fun and, although time-consuming, worth it since I can see the product of my time and effort. I used two videos to help me along the way, one for either switch. Even with the help of these videos, it took e a long while to apply what it said in both of them. It was harder than I expected, but I look forward to doing it again. 

![IMG_1794](https://user-images.githubusercontent.com/98391104/161433727-55050993-6f03-488d-ae14-b0e8f76b384a.jpg)
The picture above is the wiring the pushbutton and the actual code can be found on lines 10-18 & 50-62. 

![IMG_1795](https://user-images.githubusercontent.com/98391104/161433750-5959c280-f35a-4b0c-b4ff-88f287ca13dc.jpg)
The picture above is the wiring the potentiometer and the actual code can be found on lines 2-8, 20-48 & 64-71. 
