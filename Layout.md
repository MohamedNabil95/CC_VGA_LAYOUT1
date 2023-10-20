<div align="center">
  <h1>VGA Layout</h1>
</div>

# Schematics and Diagrams 

## Lower level schematic and diagram

![Lower level Schematic](https://github.com/MohamedNabil95/CC_VGA_LAYOUT1/assets/90795738/b2a7c521-f9b9-473a-8ad1-f1578e649649)


![Diagram Lower Level](https://github.com/MohamedNabil95/CC_VGA_LAYOUT1/assets/90795738/a563563b-00ae-4ff7-8852-d3032aa18633)


## Top Level schematic and diagram

![TOP level Schematic](https://github.com/MohamedNabil95/CC_VGA_LAYOUT1/assets/90795738/3ee6393a-ced0-4402-b2bf-b252bc2a40e8)

![TOP LEVEL Diagram](https://github.com/MohamedNabil95/CC_VGA_LAYOUT1/assets/90795738/04bb9004-a9fc-4539-be38-bbdc4e12ea8c)

Note : in this design the capacitors and resistors used in normal design for VGA are implemented by transistors .

# floorplan

![Full Layout](https://github.com/MohamedNabil95/CC_VGA_LAYOUT1/assets/90795738/5a3539a0-c179-4e0d-9b2d-7c06de349ad4)

This is the full layout of the circuit 

![image](https://github.com/MohamedNabil95/CC_VGA_LAYOUT1/assets/90795738/0173c1f1-61a3-4f8b-ace3-bdbf8187ba83)

we divide it to top and bottom parts to make it easier to explain floor plan and patterns .

## Top Part

![image](https://github.com/MohamedNabil95/CC_VGA_LAYOUT1/assets/90795738/4f81b6ae-af33-41ef-8347-8fcae3ae45d5)

 
1. decaps on both sides to fill unused area
2. capactior devices of the second stage interdigitated both sides
3. resistor devices of the second stage interdigitated both sides
4. CM PMOS load with dummies surronding
5. Input PMOSs Devices of the second stages interdigitated .

## Bottom Part

![image](https://github.com/MohamedNabil95/CC_VGA_LAYOUT1/assets/90795738/ceb8795c-0e2a-4215-bae0-e9c2eff843cc)

1.	Diffrential Input of CMFB Circuit and its load .
2.	Capactior devices of sensing unit interdigitated on both sides.
3.	Resistor devices of sensing unit interdigitated on both sides.
4.	Current mirror pattern.
5.	Diffrential pair pattern suroonded by dummies.

# Patterns 

## Top Part Patterns

### Current Mirror PMOS LOAD

![image](https://github.com/MohamedNabil95/CC_VGA_LAYOUT1/assets/90795738/63f0b47e-5fea-4ba2-a13a-4d9b50945330)

 

![image](https://github.com/MohamedNabil95/CC_VGA_LAYOUT1/assets/90795738/6bebe84e-2922-49e5-b06e-d0b3fa64dfb3)

Note : D Stands for Dummy 

### PMOS second stage input devices 
![image](https://github.com/MohamedNabil95/CC_VGA_LAYOUT1/assets/90795738/2f1e6bc3-14d4-4709-8336-e9bf08a54298)
![image](https://github.com/MohamedNabil95/CC_VGA_LAYOUT1/assets/90795738/55fcf1be-0bcf-44fe-8e79-7fbed12de8de)
![image](https://github.com/MohamedNabil95/CC_VGA_LAYOUT1/assets/90795738/91e679a3-c3fc-4052-a4a7-8e41fa4bb89c)
Note : Each unit in the excell pattern is 5 transistors 

### Resistor and capacitor Devices 
#### Resistors 
![image](https://github.com/MohamedNabil95/CC_VGA_LAYOUT1/assets/90795738/fdaf70ab-8b7a-403d-a5f9-0e9fd07cff81)
#### Capacitors
![image](https://github.com/MohamedNabil95/CC_VGA_LAYOUT1/assets/90795738/c46f82c6-a2db-41fe-9273-2e2b374fc69d)
#### Pattern
![image](https://github.com/MohamedNabil95/CC_VGA_LAYOUT1/assets/90795738/cddd187e-d8a2-4a27-8061-05ed2b0c430e)
Note : THis pattern is same for both but for capacitor devices it has no guard rings .

## Bottom part Patterns 
### Differntial Pair First Stage
![image](https://github.com/MohamedNabil95/CC_VGA_LAYOUT1/assets/90795738/c3b53de3-818d-490f-9a4e-012a8a88227b)
![image](https://github.com/MohamedNabil95/CC_VGA_LAYOUT1/assets/90795738/23dca6c2-1007-4265-8da4-8bf5f9c2249c)


### Current Mirror Devices
![image](https://github.com/MohamedNabil95/CC_VGA_LAYOUT1/assets/90795738/9a46bbc6-0731-4478-93ce-6589de67a96c)
![image](https://github.com/MohamedNabil95/CC_VGA_LAYOUT1/assets/90795738/37464c21-9894-42f2-b5b4-805ffd6f0ef5)

### CMFB PMOS Load
![image](https://github.com/MohamedNabil95/CC_VGA_LAYOUT1/assets/90795738/75c42bc9-e478-4a09-a5cb-de7a336886b5)
![image](https://github.com/MohamedNabil95/CC_VGA_LAYOUT1/assets/90795738/480fa8d4-d36c-4c2f-bd17-c66e152fcbab)

### CMFB NMOS input Devices
![Highlihgt Layout](https://github.com/MohamedNabil95/CC_VGA_Layout/assets/90795738/dcf87f28-6d2b-48cf-b425-13f7640ef9b7)
![Highlight Schematic](https://github.com/MohamedNabil95/CC_VGA_Layout/assets/90795738/5bad59d5-e55e-4c6d-9642-d4a4ebfd0795)

* Note : in this 2nd stage CMFB devices I have used matching by placement and not interdigitation as the previous patterns 
Since its a half circuit and the surrondings on sides are most likely same .

### Resistive and capacitive devices in 2nd stage sensing unit
#### Resistive devices 

![Resistor Layout Higlight](https://github.com/MohamedNabil95/CC_VGA_Layout/assets/90795738/86121612-97bd-4ca1-a88b-27e685fbe47b)
![Resistor Sch Highlight](https://github.com/MohamedNabil95/CC_VGA_Layout/assets/90795738/e8b533b1-fb00-4f45-b239-fdd20855d139)

* here I used interdigitation like the top one
#### Capacitive Devices 

![Cap Highliht Sch](https://github.com/MohamedNabil95/CC_VGA_Layout/assets/90795738/95be7e58-cf6a-4c25-b6a6-c8de24c1246c)
![Cap Highlight Layout](https://github.com/MohamedNabil95/CC_VGA_Layout/assets/90795738/c6de5004-8ea5-45e2-8f22-97af8b98536f)

* Same as resistive devices

## Some Highilighted Nets 

### Vb In current mirror (Input Current Node )
![VB In Current Mirror Layout](https://github.com/MohamedNabil95/CC_VGA_Layout/assets/90795738/66dc831a-2640-470b-a516-33a4cc4076f3)

### Input signals in input pair 1st stage
![vin_1stage](https://github.com/MohamedNabil95/CC_VGA_Layout/assets/90795738/c37745d1-cb61-41f9-8dec-8b1dd2f2b1bd)

### Output signals 1st stage
![Vouts_1stage](https://github.com/MohamedNabil95/CC_VGA_Layout/assets/90795738/cf965d5e-e277-41e6-918f-13c5857491ef)

### Output of the cricuit overall
![Overall output](https://github.com/MohamedNabil95/CC_VGA_Layout/assets/90795738/e98e9391-ef6b-4cf0-a760-f142d7e4bf63)

### VCMFB
![VCMFB](https://github.com/MohamedNabil95/CC_VGA_Layout/assets/90795738/71899644-feef-44da-82a4-0daadb06b498)

## Verification 
### DRC
![DRC CLEAN TOP](https://github.com/MohamedNabil95/CC_VGA_Layout/assets/90795738/1b7d96ab-05f8-4155-8685-f47f85d05d7b)

### LVS 
![LVS Matched 1](https://github.com/MohamedNabil95/CC_VGA_Layout/assets/90795738/8653226b-e771-4f97-aff6-ebb2cee3a187)
![LVS Matched 2](https://github.com/MohamedNabil95/CC_VGA_Layout/assets/90795738/ad1cab5b-9df3-44d9-b2c1-1f07cf29cf3e)
