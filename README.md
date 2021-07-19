# Squats-Counter

> This Arduino BLE Sense based Squats counter can count number of Squats performed by an individual using the Accelerometer readings and TinyML based Machine learning model.
  
# Demonstration
> The Squats counter can detect squats by meaasuring the accelerometer readings and prints it on the Serial monitor.
> The device is to be attached on the individual's thigh and can be powered using a Power bank or a battery.

<p align="center">
<img align="center" src="https://github.com/Manasmw01/Squats-Counter/blob/main/images/gifs/Look.gif">
</p>

<p align="center">
<img align="center" src="https://github.com/Manasmw01/Squats-Counter/blob/main/images/gifs/Squats.gif">
</p>


# Things used in this project
>I am using this complementary Google IO kit from Sparkfun which includes the Arduino Nano 33 BLE Sense which is capable of running TinyML projects with ease. 
<p align="center">
<img align="center" src="https://github.com/Manasmw01/Squats-Counter/blob/main/images/SSs/kit.jpg">
</p>

# Steps to follow
## 1. Upload the > [tf4micro-motion-kit code to the Arduino Nano 33 BLE Sense](https://github.com/googlecreativelab/tf4micro-motion-kit/releases/tag/v005)  

## 2. After uploading the code, open the [Tiny Motion Trainer Experiment](https://experiments.withgoogle.com/tiny-motion-trainer) by Google and pair the Bluetooth device with the laptop.

<p align="center">
<img align="center" src="https://github.com/Manasmw01/Squats-Counter/blob/main/images/SSs/pair.png">
</p>

## 3. Select the appropriate settings for training the model
<p align="center">
<img align="center" src="https://github.com/Manasmw01/Squats-Counter/blob/main/images/SSs/settings.png">
</p>

## 4. Capture the data required to train your model
<p align="center">
<img align="center" src="https://github.com/Manasmw01/Squats-Counter/blob/main/images/SSs/capture%20data.png">
</p>

## 5. Train your model
<p align="center">
<img align="center" src="https://github.com/Manasmw01/Squats-Counter/blob/main/images/gifs/Training%20model.gif">
</p>

## 6. Test your model
<p align="center">
<img align="center" src="https://github.com/Manasmw01/Squats-Counter/blob/main/images/gifs/Tinyml%20test.gif">
</p>

## 7. Download the Arduino code and upload it in the Arduino BLE Sense Board
<p align="center">
<img align="center" src="https://github.com/Manasmw01/Squats-Counter/blob/main/images/SSs/download.png">
</p>

## 8. Test the model by using the Serial monitor
<p align="center">
<img align="center" src="https://github.com/Manasmw01/Squats-Counter/blob/main/images/gifs/Test%20serial.gif">
</p>

## 9. Update the code as per your requirements or use mine:  [BLE_Sense_Arduino_Code](https://github.com/Manasmw01/Squats-Counter/tree/main/src/BLE_Sense_Arduino_Code)

## 10. Place the device on your thigh using a Hook and Loop fastener (Velcro tape)
<p align="center">
<img align="center" src="https://github.com/Manasmw01/Squats-Counter/blob/main/images/gifs/Look.gif">
</p>

## 11. Done!
<p align="center">
<img align="center" src="https://github.com/Manasmw01/Squats-Counter/blob/main/images/gifs/serial.gif">
</p>

<p align="center">
<img align="center" src="https://github.com/Manasmw01/Squats-Counter/blob/main/images/gifs/Squats.gif">
</p>
