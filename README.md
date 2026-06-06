# Renders


<img width="600" height="400" alt="v3_assembly" src="https://github.com/user-attachments/assets/6c34d943-806a-4dd2-b535-f821117a488b" />
<img width="600" height="400" alt="assembly v3 Drawing 1" src="https://github.com/user-attachments/assets/faebf138-ec4d-4ded-a293-24e0c7ce13bb" />

# Steering-wheel-controller
A steering wheel controller to play driving games on the go 

# Controller features
The steering wheel controller has multiple features, including a steering wheel in the middle. Multiple buttons on the interface for QOL. The buttons include two buttons for shifting one to shift up and one to shift down. There are also three different buttons for light control in-game. These buttons include 2 turn signals and 1 hazard light button 

# Future things 
In the future, I hope to add a H-pattern shifter and a hand brake for drifting games or a more realistic experience. I also hope to add more things, like customizable buttons that you can program to your liking or gaming style 

# How does it all work 
The main steering component is a rotary encoder with a push button. This will send analog input to the ESP32, which will then send that input to the device it's connected to. The shifting and turn signal controls are just simple buttons, which will also go to the ESP32. The gas and brake pedals are linear potentiometers with a travel of 20mm. This will allow you to control the speed of acceleration and braking as if you were using actual brake and gas pedals. 

# Current progress 
currently its just in its development phase because I need to get the grant for hardware, but when I get the grand i will start to 3d print the parts and make a prototype from there. I will begin to make changes as necessary 
