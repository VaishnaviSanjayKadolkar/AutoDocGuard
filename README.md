# AutoDocGuard
A semi-automatic, portable smart compartment system controlled via an Android app with password protection for secure document handling.
# 1.PROBLEM DEFINITION
## NEED STATEMENT
###    Company needs smart portable compartment system
### 1.1 QUESTIONS AND ANSWERS

      Table 1:Questions and answers
|Sl.No | Questions | Answer | Objective/Function/Constraint|
|------|-----------|--------|------------------------------|
|1. | Should the compartment be semiautomatic or fully automatic? | The Machine should be semiautomatic | Objective
2 | What should be the cost of  compartment? | Around 3500|Constraint
3 | What should be the size of compartment? | Dimensions:1 ft   *1 ft *1 ft| Constraint
4 | The system should be fixed or portable? | Portable| Objective
5 | Which locking system would you like to have? | Password| Function
6 | What should be the   weight holding capacity of the compartment? | It should sustain around 500-700gm weight| Constraint
7 | What should be the   weight of system? | It should not exceed 4 kg| Constraint
8 | Should the machine be user friendly? | Yes| Objective
9 | For what purpose you   want the smart trolley? | To maintain the document safety| Function
10 | Do you want   any additional features? | It should move automatically| Function
11 |The system should work on DC or AC supply| AC supply| Constraint
12 |Which type of instruction would you like to have(App guided or LCD)?|Android app| Function

***

## 1.2 BASIC SURVEY AND REQUIREMENTS
      
    Table 2:Observations from a literature survey
Sl.No |Observations from surveys| Requirements|
------|-------------------------|------------|
1.|Weight of system| It should be easy to move|
2.|No. of operations| The password system should have 9 numbers key|
3.|Cost|It should built within 3500 budget|
4.|No. of directions of movement| It should move in all 4 directions| 
5.|Materials to be used| DC motors, Adapters, Wheels, Arduino, Bluetooth connectivity|

***


## 1.3 IDENTIFYING CLIENT'S OBJECTIVES
step 1:Prepare a list of design objectives
      
   Table 3:Identified objectives
Sl.No |Objectives|
------|----------|
1.|Machine should be semi-automatic|
2.|System should be portable|
3.|System should be user-friendly|


## PROBLEM DEFINITION VERSION 1.1:-
Design a semi-automatic smart compartment system  which will help to enhance the document security. It should be portable and user-friendly.

***

## 1.4 IDENTIFY CONSTRAINTS
Step1:Prepare a list of design constraints
    
     Table 4:Identified constraints
Sl.No |Constraints|
------|-----------|
1.|The weight of system should be less than 4kg.
2.|Dimensions 1 cubic ft
3.|The password system should have at least 9 numbers key.
4.|It should sustain at least 500-700gm weight.
5.|The system can work on AC supply.
6.|Cost of the system should be less than 3500Rs.

## PROBLEM DEFINITION VERSION 1.2:-
Design a semi-automatic smart compartment system  which will help to enhance the document security. It should be portable and user-friendly. Machine should not exceed the volume of 1 cubic ft, It should be able to sustain at least 500-700gm of documents, production cost should not more than 3500 Rs, it can work on AC supply.

***

## 1.5 ESTABLISH FUNCTIONS:-
Step 1:Prepare list of design functions
    
    Table 5:Identified functions
Sl.No |Functions|
------|---------|
1|Move the system according user's instruction.
2|Ask for a password.
3|Open the compartment only when password is correct.


## PROBLEM DEFINITION VERSION 1.3:-
Design a semi-automatic smart compartment system  which will help to enhance the document security. It should be portable and user-friendly. Machine should not exceed the volume of 1 cubic ft, It should be able to sustain at least 500-700gm of documents, production cost should not more than 3500 Rs, it can work on AC supply. Instruct the machine using android app .Enter correct password to open the compartment.


# CONSEPTUAL DESIGN AND PRODUCT ARCHITECTURE 
## 2.1 ESTABLISHING FUNCTIONS

Table1:List of all identified functions
Sl.No.|Functions|
------|---------|
1|Place the documents in compartment.
2|Close the system.
3|Move the system according to user's instruction.
4|Stop the system.
5|Ask for password.
6|Enter the password.
7|Check the password.
8|Notify if password is incorrect.
9|Open the compartment if password is correct.
10|Take out the documents.
11|Close the compartment.

***


## 2.2 FUNCTION TREE
![function chart](https://github.com/CEER-G/G6/assets/131332002/d858b3f3-c13e-4d3f-ba94-166e33703472)

## 2.3 FUNCTIONAL CLUSTERING
![function clustering](https://github.com/CEER-G/G6/assets/131332002/dd485d35-d4a0-46de-84aa-d046e4fbaf80)

## 2.4 SUBSYSTEMS IDENTIFIED
#### 1.Document status.
#### 2.Moving unit.
#### 3.Password system.
#### 4.Notification system.

## 2.5 ESTABLISHING MEANS-MORPHOLOGICAL CHART
Sl.No.|Function|Mean 1|Mean2|Mean 3|Mean 4
------|--------|------|-----|------|------
1|Project body|![image](https://github.com/CEER-G/G6/assets/131332446/e3f3511f-15e2-4b2c-a983-a0ee5b1562c3)Plywood|![image](https://github.com/CEER-G/G6/assets/131332446/3864f44c-8f25-423d-a58d-877cad5c041d)Cardboard|![image](https://github.com/CEER-G/G6/assets/131332446/53b9f5dd-4f08-45a5-ac82-7ad0ab2cc20e)Foamsheet|![image](https://github.com/CEER-G/G6/assets/131332446/ddccaa11-ede5-40fc-bbc6-8e726a2c1a46)Acrylicsheet
2|Motor|![image](https://github.com/CEER-G/G6/assets/131332446/4dc6ced2-985f-4c86-a53c-7b9dc4eaa46a)servomotor MG995|![image](https://github.com/CEER-G/G6/assets/131332446/372a10c1-c731-4a74-ad46-559dbf549d97)Servomotor SG90|![image](https://github.com/CEER-G/G6/assets/131332446/39dec871-b982-4ad3-9b52-0a18d7c7b988)Stepper motor|![image](https://github.com/CEER-G/G6/assets/131332446/e64d0c92-6d66-41f4-9790-e21cd3084410)DC motor
3|Opening the door|![image](https://github.com/CEER-G/G6/assets/131332446/493d83ad-057b-4301-8294-c98e7a2abfc1)Pass word|![image](https://github.com/CEER-G/G6/assets/131332446/89abb117-7f99-4632-b7fc-6d5fed5bf8dc)Fingerprint|![image](https://github.com/CEER-G/G6/assets/131332446/1be68810-06e0-4db2-a458-932f44704afa)RFID Reader|![ee44](https://user-images.githubusercontent.com/131332002/235991591-724d4334-b9d2-4d93-b162-e5e9d5bf2cee.jpeg)Serial No. scanner 
4|Mechanism to be used|![image](https://github.com/CEER-G/G6/assets/131332446/92699f43-ca4d-45c2-9795-1dd07f9c636a)Linkage mechanism|![image](https://github.com/CEER-G/G6/assets/131332446/eb9f57b6-02e4-48f8-8f5d-b59fabd61a92)Rack and pinion|![image](https://github.com/CEER-G/G6/assets/131332446/dd296707-5476-497b-84b3-0ba337b08598)Belt drive|![ee34](https://user-images.githubusercontent.com/131332002/235988761-80b67f52-eaeb-4fb4-bc9d-5c0c8c52b157.jpeg) Conveyor belt
5|Indication|![ee51](https://user-images.githubusercontent.com/131332002/235994069-0e38b7e1-88bb-4576-803e-9283898eb6df.jpeg) LCD display|![ee52](https://user-images.githubusercontent.com/131332002/235994323-50799048-7ab7-41c1-80eb-41947ec9c7fb.jpeg) LED|![ee53](https://user-images.githubusercontent.com/131332002/235994443-1d4b6d11-77ae-4a8e-94e0-3026d1605c92.jpeg) Buzzer|![ee54](https://user-images.githubusercontent.com/131332002/235994649-e851af5e-f736-47d5-a022-fdc168cac2c4.jpeg) Flashing alarm
6|Power source|![ee71](https://user-images.githubusercontent.com/131332002/236000505-1f6a729d-4bc9-4999-a885-74c170dca486.jpeg) Primary battery(DC)|![ee72](https://user-images.githubusercontent.com/131332002/236000673-e161075d-e3dd-438b-8872-92eec34a7faa.jpeg) Secondary battery(DC)|![ee73](https://user-images.githubusercontent.com/131332002/236000845-6dd17c48-2ccb-45ee-9035-6eeddb9065f4.jpeg) AC source|![ee74](https://user-images.githubusercontent.com/131332002/236000920-fb9e2464-4f77-44e7-b989-0a427dcb2b3d.jpeg) Solar panel

## 2.6 CONSEPT GENERATION
### 2.6.1 Concept 1: Vaishnavi 
![WhatsApp Image 2023-07-25 at 10 44 36 AM](https://github.com/CEER-G/G6/assets/131332002/afb9fff2-5581-4c91-bd5a-b09ae181fc64)

### 2.6.2 Concept 2: Shivalingappa 
![WhatsApp Image 2023-07-25 at 10 45 58 AM](https://github.com/CEER-G/G6/assets/131332002/88030d8d-ab76-46e4-8027-e364b7f9fec7)

### 2.6.3 Concept 3:Ratan
![WhatsApp Image 2023-07-25 at 10 50 39 AM](https://github.com/CEER-G/G6/assets/131332002/ab397ad6-73db-4358-bf7e-b0aaee1f3e22)


### 2.6.4 Concept 4: Ranjita 
![WhatsApp Image 2023-07-20 at 4 11 46 PM (2)](https://github.com/CEER-G/G6/assets/131332002/33bdb6a7-d147-4dfe-850c-fc3f97a7d127)

## CONCEPT SELECTION



Task 2 : Write Pugh chart for the 4 alternative designs 
--
Design Objectives | Weights | Design 1 | Design 2 | Design 3 | Design 4
------------------|---------|----------|----------|----------|---------
 |  |  |![WhatsApp Image 2023-07-25 at 10 44 36 AM](https://github.com/CEER-G/G6/assets/131332002/f191c540-da6f-4c8f-a636-8f45bcd5ea41)|![WhatsApp Image 2023-07-20 at 4 11 46 PM (2)](https://github.com/CEER-G/G6/assets/131332002/ce4258b4-988d-4c95-9a1e-95f5388f0113)|![WhatsApp Image 2023-07-25 at 10 50 39 AM](https://github.com/CEER-G/G6/assets/131332002/8abcea1c-8d74-46f2-9b3d-7ad37aa98ca0)|![WhatsApp Image 2023-07-25 at 10 45 58 AM](https://github.com/CEER-G/G6/assets/131332002/e5c5b0f2-ae1a-4727-9e65-42b72265d3aa)
Effective locking | 7 | + | Datum | + + | +
Ease of use | 8 | + | Datum | + + | -
Aesthetic | 2 | + + | Datum | + | -
Maintainance | 4 | + + | Datum | - - | +
Cost   effective | 9 | + + | Datum | + | -
Size | 6 | - - | Datum | + + | -
Portability | 7 | - | Datum | + + | - -
Safety | 5 | + + | Datum | - - | +
Score(+) |   | 55 |   | 67 | 16
Score (-) |   | 26 |   | 18 | 39
Total |   | 29 | Datum | 49 | -23


***

## JUSTIFICATION CHART
|          | Objective|Score Allocated|Justification for the Score|
-------------------|----------|---------------|--------------------------|           
 Design 1 |Effective locking|7|Fingerprint can accessible by that perticular person only |
|  |Ease of use|8|Sometimes finger gets rubbed and inappropriate
| |Aesthetic|4|Design is simple  and looking good
| |Maintenance|8|It is easy to the maintenance because only one DC motor is used
||Cost effective|18|It will be around 1500
||Size|-12|Design Exceeding required dimensions
||Portability|-7|Movement is human guided
||Safety|10|Fingerprint is safest locking system
Design 2 |Effective locking|Datum|
|  |Ease of use|Datum|
| |Aesthetic|Datum|
| |Maintainance|Datum|
||Cost effective|Datum|
||Size|Datum|
||Portability|Datum|
||Safety|Datum|
 Design 3|Effective locking|14| Password can be accessible by multiple people
|  |Ease of use|16|Password can be changed at any time
| |Aesthetic|2|Design is having single motor two door opening mechanism
| |Maintainance|-8|Maintaining 3 DC motor is complecated
||Cost effective|9|It will be around 2500
||Size|12|Design fits within dimensions
||Portability|14|Having wheels and app guided movement
||Safety|-10|Chance of electrical damages
 Design 4 |Effective locking|7|Anyone can open having key
|  |Ease of use|-8|Sometimes key get suck inside and difficult to remove
| |Aesthetic|-4|Due to complex structure
| |Maintenance|4|It will be having less maintenance
||Cost effective|-9|Cost will be more due external locking system.
||Size|-6|Exceeding the required dimensions.
||Portability|-14|It will be having less portability because of large size
||Safety|5|Anyone can easily get the key

***

##  SELECTED CONCEPT


![WhatsApp Image 2023-07-25 at 10 50 39 AM](https://github.com/CEER-G/G6/assets/131332002/2f5af162-10fe-4864-889c-31fb69effc7a)


***

## 2.4 SUBSYSTEMS IDENTIFIED
#### 1.Handling compartment system.
#### 2.Password system.
#### 3.Notification system.
#### 4.Document status.

***

##  INTERACTION DETAILS

|SUBSYSTEM 01|SUBSYSTEM 02|SUBSYSTEM 03|SUBSYSTEM 04
|-----------|------------|------------|------------
|Data|No|Yes|No|
|Spatial|Yes|No|No
|Material|No|Yes|No

|SUBSYSTEM 02|SUBSYSTEM 01|SUBSYSTEM 03|SUBSYSTEM 04
|-----------|------------|------------|------------
|Data|No|Yes|Yes
|Spatial|Yes|Yes|No
|Material|Yes|Yes|No

|SUBSYSTEM 03|SUBSYSTEM 01|SUBSYSTEM 02|SUBSYSTEM 04
|-----------|------------|------------|------------
|Data|Yes|Yes|Yes
|Spatial|Yes|No|No
|Material|Yes|No|No

|SUBSYSTEM 04|SUBSYSTEM 01|SUBSYSTEM 02|SUBSYSTEM 03
|-----------|------------|------------|------------
|Data|No|Yes|Yes
|Spatial|No|No|No
|Material|No|No|No


## 5.1 3D MODEL
***
|||
|-|-|
|![image](https://github.com/CEER-G/G6/assets/131332446/30957ae2-65f8-4d0f-b7e4-6c3c755e3a0a)|![link1](https://github.com/CEER-G/G6/assets/131332002/45c56454-5a87-4987-898e-031a289d09e9)|
|![link2](https://github.com/CEER-G/G6/assets/131332002/cd273b12-b5a4-4344-9590-ea6f5f71f715)|![moving unit](https://github.com/CEER-G/G6/assets/131332002/175191ae-9f7c-4ef8-8fda-64e260f8170b)|





## 5.2 FLOWCHART
***
![FLOWCHART SPRINT3](https://github.com/CEER-G/G6/assets/131332002/a32c9d0c-9c43-4d3b-9c74-4061bd18505c)


***
## 5.3 CRCUIT DIAGRAM
![circuit](https://github.com/CEER-G/G6/assets/131332002/6b19e790-db90-4628-bbea-5bcc46719ede)



## MECHANISM:
***

####     The doors fixed on compartment will move to open and close the compartment using linkage mechanism. It will take the input from MIT app. i.e. after entering the correct password compartment will open.
## 


***
## MATERIAL LIST
***
#### 1. Acrylic sheets
#### 2. Links
#### 3. Hinges
#### 4. DC motors
#### 5.Bluetooth module
#### 6. Wheels
#### 7. L-clamps
#### 8. Nuts & bolts
#### 9. Adapter
#### 10. Breadboard
#### 11. Wires
#### 12. Arduino uno
#### 13. Power jack
#### 14. Relay
***

  
## 6.1 MOTOR SIZING
***
## MOTORS FOR MOVING UNIT
#### Assume motor mass=300 gm
#### Mass of links=150 gm
#### Selected material is acrylic sheet
#### There is no load placed on sheet

#### Density of acrylic sheet=1.15 gm/cm^3
#### Density of foam sheet=0.35 gm/cm^3

#### Given dimensions are,

#### Length of sheet A=30 cm
#### Width of sheet A=30 cm
#### Thickness of the sheet A=0.4 cm
#### Length of sheet F=30 cm
#### Width of sheet F=15 cm
#### Thickness of the sheet F=0.4 cm
***

#### Volume of sheet A=30 * 30 * 0.5
> ### v(A)=360cm^3
#### Mass of sheet A=Density*Volume
> ### M(A)=0.414 kg
#### Volume of sheet F=30 * 15 *0.4
> ### v(F)=180cm^3
#### Mass of sheet F=Density*Volume
> ### M(F)=0.063 kg
***

#### There are 5 acrylic sheets of same dimensions
#### There are 2 foam sheets of same dimensions
***

#### Total load=2 * Motor mass+4 * M(A)+2 * M(F)+Mass of links
> #### L=0.600+2.07+0.126+0.150
> ### L=2.946 kg
***

#### Force=mg*u
> #### F=2.946*0.25
> ### F=0.7365 kg
***

#### Torque=Force*Radius
> #### T=0.7356*4
> ### T=2.964 kg-cm
> #### Torque * FOS=2.964*1.5=4.419 kg-cm
### We are using two motors
> ### Torque on one motor=2.2095
## We can choose 2 motor of 60 rpm each can sustain torque up to 3.6 kg-cm
***
## MOTOR FOR LINKAGE MECHANISM
#### Assume motor mass=300 gm
#### Mass of links=150 gm
#### Selected material is acrylic sheet

#### Given dimensions are,
#### Length of sheet F=30 cm
#### Width of sheet F=15 cm
#### Thickness of the sheet F=0.4 cm
#### Volume of sheet F=30*15*0.4
> ### v(F)=180cm^3
#### Mass of sheet F=Density*Volume
> ### M(F)=0.063 kg

***

#### There are 2 foam sheets of same dimensions
#### Total load=Motor mass+2 * M(F)+Mass of links
> #### L=0.300+0.126+0.150
> ### L=0.576 kg

***

#### Force=mg*u
> #### F=0.576*0.25
> ### F=0.144 kg

#### Torque=Force*Radius
> #### T=0.144 * 12.5
> ### T=1.8 kg-cm
> #### Torque * FOS=1.8 * 1.5=2.57 kg-cm
## We can choose 1 motor of 60 rpm WHICH can sustain torque up to 3.6 kg-cm
***
|Motor(DC)|Torque(kg-cm)|Speed(rpm)|
|-|-|-|
|Motor 1|2.2095|60|
|Motor 2|2.2095|60|
|Motor 3|2.57|60|

***

***


## 6.2 ADAPTER SELECTION
### For DC motor
> #### Operating voltage=12V
> #### Current required=300 mA
> #### Multiplying with factor of safety
> #### Total current is
> #### 0.300 * 1.2=0.36 A
#### For 3 DC motors
#### Total current=3*0.36=1.08A
## 12V and 1.5 A adapter can be choose to operate a DC motor
***
### For Arduino
> #### Operating voltage=9V
> #### current required=20mA
> #### No. of pins to be used=8
> #### Total current is
> #### 0.20 * 8 * 1.2=1.92 mA
## 9V and 2A adapter can be choose to operate an Arduino
***
***
## 6.3 POWER CALCULATION
### FOR MOTOR
> ####  current required=300mA=0.3A
> #### Operating voltage=12V
> ###  Power=V * I=1.08 * 12
> ### Power=12.96 W
### FOR ARDUINO
> ####  current required=300mA=0.3A
> #### Operating voltage=9V
> ###  Power=V * I=1.92 * 9
> ### Power=17.28 W
### TOTAL POWER=30.24 w
***



***

***


|CONSUMABLES|  SPECIFICATIONS AS PER BOM   |QUANTITY  |TOTAL|UNIT EMBODIED ENERGY|TOTAL EMBODIED ENERGY|
|-----------|-------------------------------------|----------|-----|--------|------|
***

|CONSUMABLES|LENGTH|WIDTH|THICKNESS|VOLUME|WEIGHT|QUANTITY|VOLUME|WEIGHT|MJ/m^3|MJ/kg|TOTAL EMBODIED ENERGY|
|-----------|----|--|--|--|--|----|-----|----|---|---|-----|
|Acrylic sheet|0.30|0.30|0.004|0.00036|0.432|5|0.008|2.16|-|117|252.72|
|Foam sheet|0.30|0.15|0.004|0.00018|0.17298|2|0.00036|0.34596|-|85|29.4066|
|Wheel|-|-|-|-|0.250|4|-|1.0|-|153|153|
|L-clamps|-|-|-|-|0.2|8|-|1.6|-|153|244.8|
|Nut & bolts|-|-|-|-|0.5|-|-|0.5|-|153|76.5|
|Links|-|-|-|-|0.150|-|-|0.150|-|117|17.55|
|||||||||||Total|773.9766||



# 1. NEED STATEMENT

 Company needs a smart portable compartment system.

# 2. PROBLEM DEFENITION

Design a semi-automatic smart compartment system which will help to enhance the document security. It should be portable and user-friendly. Machine should not exceed the volume of 1 cubic ft, It should be able to sustain at least 500-700gm of documents, production cost should not more than 3500 Rs, it can work on AC supply. Instruct the machine using android app. Enter correct password to open the compartment.

# 3. Sprint 1:
### Work carried out :
 
3D modelling and virtual implementation of circuit.

### Scrum master:
 
Ratan badiger

### Modules utilised during scrum:

Mechanism and resource specifications

![image](https://github.com/CEER-G/G6/assets/131332446/cf9f8856-05be-4f95-bcb0-8182f2c3b7de)

![circuit](https://github.com/CEER-G/G6/assets/131332002/158ec654-0a2b-4433-8bc9-203e23a39c74)

# 4. Sprint 2:

### Work caried out:

Laser cutting of acrylic sheet and  its assembly

### Scrum master:

Ranjita Nayanegali

### Modules utilised during scrum

Engineering design

![image](https://github.com/CEER-G/G6/assets/131332446/15a2637d-9458-4568-8876-448a0cc8d257)
![image](https://github.com/CEER-G/G6/assets/131332446/5c746a03-59fb-41d4-9fac-74609b49515d)

# 5. Sprint 3:

### Work carried out :

coding

### scrum master:

Vaishnavi Kadolkar

### Modules utilised during scrum:

Problem based development

![image](https://github.com/CEER-G/G6/assets/131332446/a0c03531-12e2-4c83-9bee-c07ac69fd2f4)

# 6. Sprint 4:

### Work carried out:

Final assembly of circuit and its testing

### Scrum master

Shivalingappa

### Modules utilised during scrum :

Sustainability

![image](https://github.com/CEER-G/G6/assets/131332446/bfddca85-3a16-4304-948c-31d7e297c2e4)

# 7. Final Model

## Title of the project : Safekeep

## Abstract
####       Engineering exploration is an exciting learning process which allows us to explore the engineering world. It is not just about the technology it is the process in which we can acquire the knowledge about problem solving strategies, practical executions and utilize these to serve the society in various aspects. As well as this process never forget to remind us about the engineering ethics and values. In this learning cum exploring process we got the chance to work upon the need statement as ’smart portable compartment system’.
 ####       As we know safety is the prominent factor in day to day life. Everyone is very specific about their privacy. Similarly document safety and transportation without human interruption is such an important task. There are number of cases we can see where companies are unable to get the tenders due to leak of confidential information. There are many industries in which the safeguarding of sensitive information is paramount. These include the legal sector, healthcare, education, banking and even government. With records on customers and clients, individuals and other businesses, there’s considerable potential for abuse should the information fall into the wrong hands. When files remain unsecured, exposing private information could be as easy as copying and opening a file.
####          Likewise, not every employee in a business should have access to all the information it produces. In some cases, you may need to conceal details about an upcoming product or service offering to prevent staff from sharing the information outside appropriate company channels. Pay records, financial details and other such private information must also stay out of the hands of the unauthorized. To overcome this problem our client needs a smart portable compartment system.
####           So we are designing a smart portable compartment system having password locking system. Whose movement can be accessible by app guide. This system can be handled by only those people who have the authority to this. The password can be reset so that security get enhanced.

# Photo

![image](https://github.com/CEER-G/G6/assets/131332446/4851380e-e190-47bd-b321-d95ff30443ac)








# PHOTOS

![image](https://github.com/CEER-G/G6/assets/131332446/64bdbae5-a06d-464c-98af-3f6bb4facb8d)

![image](https://github.com/CEER-G/G6/assets/131332446/1870b817-f092-4439-a084-61081c25650c)

![image](https://github.com/CEER-G/G6/assets/131332446/78c6b54c-5400-4c35-94de-d30079d3c7a9)

# VIDEO

https://github.com/CEER-G/G6/assets/131332002/5fc27a9f-7b56-48fe-b6fd-053782df681c

