# 1701QCA Making Interaction - Assessment 2 workbook

You will use this workbook to keep track of your progress through the course and also as a process journal to document the making of your projects. The comments in italics throughout the template give suggestions about what to include. Feel free to delete those instructions when you have completed the sections.

When you have completed the template, submit the link to the GitHub Pages site for this repository as a link in Learning@Griffith. The link should be something like [https://qcainteractivemedia.github.io/1701QCA-Assessment2/](https://qcainteractivemedia.github.io/1701QCA-Assessment2/) where `qcainteractivemedia` is replaced with your GitHub username and `1701QCA-Assessment2` is replaced with whatever you called the repository this template is contained in when you set it up.

## Project working title ##
Slow Growth

## Related projects ##
*Find about 6 related projects to the project you choose. A project might be related through  function, technology, materials, fabrication, concept, or code. Don't forget to place an image of the related project in the appropriate folder and insert the filename in the appropriate places below. Copy the markdown block of code below for each project you are showing.*

### Related project 1 ###
Blooming Paper Art

https://www.haufig.com/blooming-paper-art-interactive-installation/


![blooming paper art](https://user-images.githubusercontent.com/62362612/79829460-7d87f400-83e6-11ea-946d-33ff0b4b9ce6.png)


This project is related to mine because of the idea of blooming and they essentially use similiar processes, using motion to trigger a blooming flower through motors. I love the mix of beautiful art and mechanics in this project.

### Related project 2 ###
Touch me not

https://www.youtube.com/watch?v=5Tt0xLZ7c-g

![Touch me not](https://user-images.githubusercontent.com/62362612/79829428-68ab6080-83e6-11ea-9a82-bec29a4f8392.png)

This project is related to mine because they have a similiar idea of blooming, instead they use touch to trigger the motion, which gives it a more tactile experience.

### Related project 3 ###
Diffusion Choir

https://www.youtube.com/watch?v=XnYCaprdqTY 

![diffusion choir](https://user-images.githubusercontent.com/62362612/79829439-71039b80-83e6-11ea-8279-670cde40d293.png)

This project is related to mine because this project they are inspired by nature, conveying it through technology and created something beautiful as a result.

### Related project 4 ###
*Insert name of project*

*Insert URL to project*

![Image](missingimage.png)

This project is related to mine because *insert reasons here*.

### Related project 5 ###
*Insert name of project*

*Insert URL to project*

![Image](missingimage.png)

This project is related to mine because *insert reasons here*.

### Related project 6 ###
*Insert name of project*

*Insert URL to project*

![Image](missingimage.png)

This project is related to mine because *insert reasons here*.


## Other research ##
*Include here any other relevant research you have done. This might include identifying readings, tutorials, videos, technical documents, or other resources that have been helpful. For each particular source, add a comment or two about why it is relevant or what you have taken from it.*

### *Brief resource name/description* ###

*Provide a link, reference, or whatever is required for somebody else to find the resource. Then provide a few comments about what you have drawn from the resource.*

## Conceptual progress ##

### Design intent ###
A device that conveys the beauty/simplicity of plants that makes us think how we look at plants to shape our lives.

I wanted to draw from some characteristics of plants; their slow growth, simple processes/beauty and limited elements to live.

![IMG_6873](https://user-images.githubusercontent.com/62362612/79945188-a07eda80-84b0-11ea-95a3-afc1c4285755.JPG)

### Design concept 1 ###
My first design concept was to create a flower/plant that grew when a light turned on and a watering can was moved towards it. I would create this with a light sensor catching the light going to a motor to lift the flower out of a hole. As well as a radio embedded in the watering can to lift the flower or make it spread out more. 

### Design concept 2 ###
My second design invloved a flower bed and the 3 stages of a plant growing; seeds, seedlings and flowers. Light sensors over certain areas would trigger the different stages of growth to appear from the flower bed, showing the beauty in each stage of growth. This could be done in a smaller scale to compensate for the lack of resources. 

### Final design concept ###
My final design is to create a flower that blooms with light. It involves a light sensor recieving light which triggers a motor to pull open the flower. My design would be simple and beautiful to reflect the simplicity of nature. 

![IMG_6874](https://user-images.githubusercontent.com/62362612/79945167-94931880-84b0-11ea-8a2a-05e310222c70.JPG)

![IMG_6875](https://user-images.githubusercontent.com/62362612/79945124-83e2a280-84b0-11ea-8924-952087bdd326.JPG)

### Interaction flowchart ###

![IMG_6876](https://user-images.githubusercontent.com/62362612/79945370-f2276500-84b0-11ea-8435-879060d7081a.JPG)

## Physical experimentation documentation ##

I started my experimentation with making the coding. To let the phototransistor recieve the light to go through the micro bit and trigger a servo motor move to push open the flower. So I started with combining the code from my previous project, the self waterer plant and the phototransistor experiment in the book. I took the end of the code of the self plant waterer, where it makes the motor move and the start of the code using the transistor to recieve the light. 
I wasn't sure whether it would work at the begining, but I started to experiment with this. 

![Image](missingimage.png)
![Image](missingimage.png)
![Image](missingimage.png)

Making small adjustments, I figured out that the code worked through the microbit, using the inbuilt light sensor rather than the one I attached it to. I managed to find the right timing for the motor to spin, fast when the light was first recieved and a large gap before it moved back so the flower bloomed for at least 10 seconds. I also found out through my different tests that it didn't work as well when it was connected to my computer, but better when I connected it to the battery.

I added a moon when there wasn't any light present and a sun when there was, so I could see what was happening. 

By test no.6, I realised that the smallest amount of light I had for the motor to move wasn't right, it was too low. So I played around with it, as I didn't fully understand how it made a different. I found that 200 was too low, after changing it to 500, I found it was too high. 300 was the golden number, It worked with my torch on my phone as well as some bright house lights. 

![Image](missingimage.png)

At this point, I was close to finally cracking the problem, I still hadn't worked out if it could work with my phototransistor yet, it was working when I made contact with pin 1 though. I connected my light sensor and played around with the positioning of the aligator clips on the pin and the microbit. I figured out that it worked when the shorter side of the pin was connected to pin 1 and the other to 0. 

My circuit had finally worked and operated swiftly. The phototransistor recieved the light from my torch then successfully madde the motor move 1 sec after then stay at that angle for 10 seconds then move back to its original position.

![IMG_6868](https://user-images.githubusercontent.com/62362612/79945215-affe2380-84b0-11ea-9a17-182f2c9ecd73.JPG)

My next objective was to look into the design of the flower. I found a video of someone making an origami flower, similar to a cocktail umbrella. I saw that this design could work for mine, with the motor pulling the bottom tab that pulled the petals of the flower, therefore making it bloom. 

https://www.youtube.com/watch?v=61_Bm20XjMU

I then created a protoype of it to make sure I understood how it could work with my flower. 

![IMG_6867](https://user-images.githubusercontent.com/62362612/79945291-cdcb8880-84b0-11ea-9827-3a45d1ec2ba1.JPG)

It worked theoretically, I just had to find a way of making it work practically, connecting the bottom tab to the servo motor. I saw a flaw with the fragility of the paper compared with the rapid movement of the motor an considered using a stronger material so it could move with the motor and withstand the force that it gave.

I then looked to other designs to see their processes, I saw a project that was very similar to mine and after some feedback from others, I decided to chnage my design and interaction of my project, but leaving the coding, using it in a different way.

## Design process discussion ##
I started my deign process with looking at what interested me so that it could inspire me throughout the project. I had been using plants in my previus project and I had seen many other projects using plants, I thought it would be interesting to see what i could learn from plants too. 

From there I came up with a few ideas of how I could convey my design intent, how I could get people to understand what I am trying to tell them, as well as create a experience through interaction. I had a couple yet there was one that I was drawn to more than the rest. 

I then started to think about how I could develop this idea, practically. How I could fabricate and code it. After figuring out the proper code and started thinking through the frabrication, I found that I needed to change my design and the way I was presenting it. i could still use my code though.

This required me to go back to defining my challenge, seeing the different ways I could change it, as well as to still suit my design intent. 

## Next steps ##
My next step is to think creatively about how I could present my project, to make a list of any ideas that I have or can do with what I have done already, maybe see the other ideas that I had previously. Then to start to think of ways I could practically make it work as a simple prototype.
