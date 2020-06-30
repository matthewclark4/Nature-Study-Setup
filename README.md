# Nature-Study-Setup
Code to run for tutorial on setting up data plants. This video gives an idea of how it works. https://vimeo.com/421002507

Nature Study is a project that explores the benefits of engaging with environmental and civic issues in the local area. Generative visuals are created with various plants which are then presented in a publication.

To create the visuals, electrode pads were placed on the leaves which measure the electrical activity in the plant using Arduino. This data was then visualised using code in Processing. This guide will hopefully show you how to set it up yourself. Much of the initial setup was based on Robbie Barrat's guide which you can find here https://github.com/robbiebarrat/plant-art

![](https://uploads-ssl.webflow.com/5d7246f37e4c7924f8a71b18/5eef5e9a79b530a4f03c05b7_Nature%20Study.jpg)

![](https://uploads-ssl.webflow.com/5d7246f37e4c7924f8a71b18/5eef5e9a299cb9804be82824_Nature%20Study2.jpg)

![](https://uploads-ssl.webflow.com/5d7246f37e4c7924f8a71b18/5eef5e9a69925c84c9be6014_Nature%20Study3-p-800.jpeg)

# Making generative visuals with plants

The images were all generated using the electrical signals of four different plants. This is a quick guide on how you can set it up yourself. It will show you how you can measure the electrical noise found in houseplants and make generative art with the processing language. 

# You Will Need:

•An arduino board (any with analogue wires) and wires that fit.

•Electrode pads

•3.5mm cables with 2 snap connectors •Cables with a female 3.5mm end

•Any plant with big leaves.

# Setting up the hardware

Take the cable with the 3.5mm female end and cut it in half, you only need the female end. 

Splice it and attach wire to your 2 Arduino wires. 

Your Arduino wires should go into the "GND" port and the "A1" port.

Next, plug the 3.5mm cable for the electrodes into the female 3.5mm port that you just spliced, and attach both snapping button ends to two pads. 

Place the pads on a plant. For best results, place them on different or nearby leaves. If they are on the same leaf, the results aren't very interesting. 

Do not leave the electrodes on the leaves for more than several hours, it will hurt the plant.

# Setting up the software

* Download and install the Arduino IDE. Start by running the voltage code on your board. 

* Normally you have to ensure the correct board is selected to the right serial port. The voltage code should look something like this:

* Next, download and install the Processing 3 IDE. Use read_voltage.pde to help you read and graph the voltage from processing. If it's working, you should see a slightly noisy function that hangs around a constant value for the most part. 



