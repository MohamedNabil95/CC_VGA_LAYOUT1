<div align="center">
  <h1>VGA Layout</h1>
</div>

# Schematics and Diagrams 

## Lower level schematic and diagram

![Lower level Schematic](https://github.com/MohamedNabil95/CC_VGA_Layout/assets/90795738/24382f93-9f20-4158-9fe6-3ce3db0df5ca)

![Diagram Lower Level](https://github.com/MohamedNabil95/CC_VGA_Layout/assets/90795738/f5142038-915b-4897-8ee9-d185f294b202)


## Top Level schematic and diagram

![TOP level Schematic](https://github.com/MohamedNabil95/CC_VGA_Layout/assets/90795738/2da64689-2b87-47c7-bc01-108f744ac451)

![TOP LEVEL Diagram](https://github.com/MohamedNabil95/CC_VGA_Layout/assets/90795738/0aabc6a5-aa2d-4bd6-acff-6a6160954370)

Note : in this design the capacitors and resistors used in normal design for VGA are implemented by transistors .

# floorplan

![Full Layout](https://github.com/MohamedNabil95/CC_VGA_Layout/assets/90795738/53c155fb-907a-4a64-ad7f-441c0cab8527)

This is the full layout of the circuit 

![Floorplan Top and Bot](https://github.com/MohamedNabil95/CC_VGA_Layout/assets/90795738/ba8e479b-c8a2-4970-b333-0117d52b5f18)

we divide it to top and bottom parts to make it easier to explain floor plan and patterns .

## Top Part

![Top View](https://github.com/MohamedNabil95/CC_VGA_Layout/assets/90795738/2bffc604-dde8-402d-9074-cad43b7abce5)

 
1. decaps on both sides to fill unused area
2. capactior devices of the second stage interdigitated both sides
3. resistor devices of the second stage interdigitated both sides
4. CM PMOS load with dummies surronding
5. Input PMOSs Devices of the second stages interdigitated .

## Bottom Part

![Bottom View](https://github.com/MohamedNabil95/CC_VGA_Layout/assets/90795738/4dcabc59-a204-406e-9288-c99af51439a3)

1.	Diffrential Input of CMFB Circuit and its load .
2.	Capactior devices of sensing unit interdigitated on both sides.
3.	Resistor devices of sensing unit interdigitated on both sides.
4.	Current mirror pattern.
5.	Diffrential pair pattern suroonded by dummies.

# Patterns 

## Top Part Patterns

### Current Mirror PMOS LOAD
![Diffrential Pair PMOS LOAD](https://github.com/MohamedNabil95/CC_VGA_Layout/assets/90795738/e0d1346b-d641-4ec1-ac79-c714d130fdc0)

 

![Excel Pattern](https://github.com/MohamedNabil95/CC_VGA_Layout/assets/90795738/0b99a2b3-0022-4cd1-9afe-17aab47e48e8)

Note : D Stands for Dummy 

### PMOS second stage input devices 
![Layout](https://github.com/MohamedNabil95/CC_VGA_Layout/assets/90795738/fa46fc2c-9652-46c9-96d2-760d9575ee0f)
![Transitors in schematic](https://github.com/MohamedNabil95/CC_VGA_Layout/assets/90795738/f25a6c61-73e1-4618-a493-95bab58446d0)
![Pattern](https://github.com/MohamedNabil95/CC_VGA_Layout/assets/90795738/ff716802-032d-4be1-b52b-f2382b603380)
Note : Each unit in the excell pattern is 5 transistors 

### Resistor and capacitor Devices 
#### Resistors 
![Resistor Layout](https://github.com/MohamedNabil95/CC_VGA_Layout/assets/90795738/2fb3770a-b42e-4558-946f-56b049bf8164)
#### Capacitors
![Capacitor Layout](https://github.com/MohamedNabil95/CC_VGA_Layout/assets/90795738/dc224482-3edc-4a58-8cd1-5fc5e0da6904)
#### Pattern
![Resistor Excel Pattern](https://github.com/MohamedNabil95/CC_VGA_Layout/assets/90795738/d80eca8d-f5e5-47e3-aab3-170a05e4811c)
Note : THis pattern is same for both but for capacitor devices it has no guard rings .

## Bottom part Patterns 
### Differntial Pair First Stage
![Layout Diff Pair](https://github.com/MohamedNabil95/CC_VGA_Layout/assets/90795738/590feff4-0253-4cb0-8469-047307411e62)
![Excell Pattern](https://github.com/MohamedNabil95/CC_VGA_Layout/assets/90795738/1d687197-f623-4f37-8ac9-a0babe671b49)

### Current Mirror Devices
![Layout](https://github.com/MohamedNabil95/CC_VGA_Layout/assets/90795738/ff4a2a74-c1e9-41cb-ad32-8d429469b7ec)
![Pattern in EXCEL](https://github.com/MohamedNabil95/CC_VGA_Layout/assets/90795738/3c0567b5-05a4-4edd-9713-833ad6341d03)

### CMFB PMOS Load
![Highlight Schematic](https://github.com/MohamedNabil95/CC_VGA_Layout/assets/90795738/6406045e-d6d9-4f05-9e39-2f31d6eb0944)
![High light Layout](https://github.com/MohamedNabil95/CC_VGA_Layout/assets/90795738/fb91283c-846a-4ef7-9aaa-d00cad5301d5)

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
