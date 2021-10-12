# AutonomousRC
Files for autonomous small-scale car build. Running DonkeyCar software.

Build Progress: 

Jetson requires 5V input, but I found that if I did supply 5V in, then the Jetson lights would flash. 
I turned the voltage up to around 5.35V on the DC-DC stepdown converter and this solved the problem. 
6V battery used as input for the PCA9685 so the steering servo doesn't take power from the Jetson. 

![IMG_3542](https://user-images.githubusercontent.com/19898100/137029283-b3ea7f79-b2c0-4c14-8b03-a61c2b6e6764.jpeg)


I went through a couple of build setups trying to incorportate the RC car body but it ended up being to difficult to access the components.

![IMG_3545](https://user-images.githubusercontent.com/19898100/137027568-5eb09e0d-838e-4793-bf79-9680dc1465d1.jpg)

Final Setup:

I used velco to attach some of the components and zipties elsewhere. I wanted things to be modular so I could use the parts on other projects. 
Also worth noting is that the IMX219 Camera module does have orientation corrections in the myconfig.py file, but they are limited to vertifical flipping or horizontal flipping, and not both. So I had to mount the camera in a rotated postion and then flip the orientation in myconfig.py.

![IMG_3547](https://user-images.githubusercontent.com/19898100/137028371-06907fa8-5678-487d-8f9d-8319922e3295.jpg)


Training soon!
