# CW-SC-Flag

SC-Flag is a SimHub-compatible racing flag display designed and developed by **Lee Chiwon** and **Park Sechan**.

This project was created to provide a reliable and responsive hardware flag system for sim racing enthusiasts.

## Credits

- **Design:** Lee Chiwon & Park Sechan
- **Development:** Lee Chiwon & Park Sechan


<p align="left">
<img src="Image/3.png" width="373" > 
<img src="Image/4.jpg" width="320" >
</p>


## 🎥 Video

[![SimHub Flag Video](Image/199.png)](https://github.com/user-attachments/assets/7d14d26c-3a42-4807-9c75-b652e139227d)
[![SimHub Flag Video](Image/211.png)](https://github.com/user-attachments/assets/e2a3c3b5-973f-4d26-be92-bc1587555317)

---

# Hardware Wire

<p align="left">
<img src="Image/14.png" width="700">
</p>

| Function    | Arduino | 8X8 LED Matrix | 8 LED Bar |
| ----------- | ------- | ------- | --------- |
| 5V                 | 5V       | 5V       | 5V          |
| GND                | GND      | GND      | GND         |
| 8X8 LED Matrix     | D3       | IN       |             |
| 8 LED Bar          | D6       |          | IN          |
 
---

# Part List 

|   Name              | EA | Site | Note | 
| ------------------- | ------ | --- | ------ |
| Arduino Nano   | 1 |  [Buy](https://smartstore.naver.com/misoparts/products/5779944205)| 
| 8X8 LED Matrix    | 1 |  [Buy](https://smartstore.naver.com/misoparts/products/13199208576)| 
| 8 LED Bar    | 1 |  [Buy](https://smartstore.naver.com/misoparts/products/9434328063)| 

# 3D Print

| Name |  EA  | Note |
| --- |  ------ |------ |
| <p align="left"><img src="Image/15.png" width="300"></p>  |  1EA  | 
| <p align="left"><img src="Image/16.png" width="300"></p>  |  1EA  | 
| <p align="left"><img src="Image/17.png" width="300"></p>  |  1EA  | 

# Simhub Arduino Setting
<p align="left">
<img src="Image/18.png" width="700">
</p>

 * 8 LED Bar *
1. WS2812B RGB leds Count  = 8
2. Data(DIN digital pin number = 6
3. encoding = RGB encoding


 * RGB Matrix *
1. Enable WS2812B 8x8 matrix = ON
2. Data(DIN digital pin number = 3





