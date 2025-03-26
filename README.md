# BME280-Sensor
| Qty | Part # | Part Name        | Link | 
|-----|--------|------------------|------|
| 1  | RIP0W  | Raspberry Pi Zero |         
| 1  | GY-BME280-3.3 | BME280 |      
| 4  | F-F Jumper Wire | 22   | [Amazon](https://www.amazon.com/bociloy-Dupont-Breadboard-Multi-Color-Connector/dp/B0D9NCD1Z3/ref=sr_1_5?crid=1J7F6YFM2GHLC&dib=eyJ2IjoiMSJ9.tjHxIQLJsk16_0YVtUGN6UHyUBKSnfs7IU4zkjBWId7Hk_j28yKTWV9mmPFZoTaaZWAnLq_sDOQ91JV_2O45DVl4rr3Lo_jsvNU7q5msuNQWYyim7KhYvVa-Q7pck_X8zNphLbTSxEr8oHSjWpI7Awsm7C-4_2cV1iIJYQnn4hKfIpmBQVFAxPIc8FNr3khi_BeFrly2xmA7e8bcVCJ_VRInGnanZaZGy-JTOlpconf2zh4RiAue6Iu5epbywykLzf6fYNpMmYXHrGj98QyFNCVtjwzqvcPdUpSGnx_9XYYFgQu3paXWToZKha0lbRRYVrE2QvN1YO_Et3JjSQ9WfCIcRME2NRtAFTNyPdSOykU.HbmkX0xOJvBCqzOU0uE8UKlMOyydG1nX9nZlETuXckg&dib_tag=se&keywords=female%2Bto%2Bfemale%2Bjumper%2Bwires&qid=1742940209&s=industrial&sprefix=female%2Bto%2Bfemalejumper%2Bwires%2Cindustrial%2C127&sr=1-5&th=1)            


## Steps
1. Assemble raspberry pi and sensor with jumper wires. Refrence youtube video for step-by-step directtions 

<img src="./images/pinout-table.png" alt="Pinout Table" width="300">

Pin #1 -> VCC
Pin #3 -> SDA
Pin #5 -> SCL
Pin #6 -> GROUND

| Raspberry Pi Pin | | BME280 Pin | Connection |
|----------|----|---------------|-------------|
| 3.3V - Pin 1       | -> | VCC       | Power      |
| GND        | -> | GND       | Ground     |
|SDA (GPIO3) | -> | SDA | Serial Data Line |
| SCL (GPIO5) | -> | SCL | Serial Clock Line |