# AutonomousRC
Files for autonomous small-scale car build. Running DonkeyCar software.

Build Progress: 

Jetson requires 5V input, but I found that if I did supply 5V in, then the Jetson lights would flash. 
I turned the voltage up to around 5.35V on the DC-DC stepdown converter and this solved the problem. 
6V battery used as input for the PCA9685 so the steering servo doesn't take power from the Jetson. 
![IMG_3542](https://user-images.githubusercontent.com/19898100/137029491-17c7d0a1-c9de-4544-8538-43bfd6ecb6c9.jpeg)

I went through a couple of build setups trying to incorportate the RC car body but it ended up being to difficult to access the components.
![IMG_3545](https://user-images.githubusercontent.com/19898100/137029520-05b46ac0-54f4-43fb-bbe9-a587bf274a69.jpg)

Final Setup:

I used velco to attach some of the components and zipties elsewhere. I wanted things to be modular so I could use the parts on other projects. 
Also worth noting is that the IMX219 Camera module does have orientation corrections in the myconfig.py file, but they are limited to vertifical flipping or horizontal flipping, and not both. So I had to mount the camera in a rotated postion and then flip the orientation in myconfig.py.
![IMG_3547](https://user-images.githubusercontent.com/19898100/137029551-9436df35-5c2b-41f2-9dd9-149cdccb4a60.jpg)

Training soon!
