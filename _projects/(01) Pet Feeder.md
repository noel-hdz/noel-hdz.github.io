---
name: Eco-Friendly Pet Feeder
tools: [CAD, Arduino,]
image: ../assets/images/Feeder/finalProductCrop.gif
description: Designed a pet feeder that uses plastic bottles for kibble storage.
---

# Eco-Friendly Pet Feeder

This project aimed to solve the challenge of feeding pets automatically while reducing plastic waste.

## Situation

The motivations for this project were as follows:
1. Often had to leave 1 family member out of trips to stay and feed cats
2. Feeding cats at the right time and the right amount of food is tedious
3. Lots of plastic water bottles in room
4. Possibility to scale up in the future to build something to feed 10+ outdoor cats

## Task

When planning this project out, I collaborated with the main user of this device (my sister) to map out all the things I wanted to accomplish:
1. Repurpose plastic bottles for kibble storage
2. Create a feeder cheaper than current market options
3. Include automated scheduling funtionality for ease of use

## Action

I started by developing the code in the Arduino IDE. I created some HTML code to host on the microcontroller which would enable access to control the device from a local IP address. HTTP methods handled communication with the servo motor and the scheduling of the feeding times.
<img src="../assets/images/feeder/htmlControlPage.jpg" alt="Feeder Webpage" width="500"> 

Next I focused on designing the CAD of the housing for all the components. I really focused on the modular aspect of the bottle holder. I wanted bottles to screw in like normal so I did some research and found that most bottles follow the ASTM D2911 Standards for finishes for plastic bottles with screw-type closures. Once I created a successful version I made it modular by making it a separate piece from the main housing so that it could be swapped out to use any size bottle (up to 50mm diameter) with any thread. I also added four small holes at the bottom to allow a stand to be attached using 4 M3 screws.
<img src="../assets/images/feeder/AllThreeCAD.png" alt="Three Isometric Views of Feeder CAD"> 

## Result

In the end I had a mostly functional pet feeder. Once I started testing, I realized that using a 16.9 fl oz water bottles would not work because their neck was too small which would cause kibble to get stuck. However, because of the modular design this issue can easily solved by using a bottle with a bigger neck. 

<img src="../assets/images/feeder/finalProduct.gif" alt="GIF of final working feeder" width="500"> 