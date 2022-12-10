# Living Type for the Commander X16
A Chinese Word Processor for the Commander X16 that supports 10,000 Chinese characters. 

The program itself is called "HUOZI.PRG" and the resources should be kept in a folder called "huozi" on the SD card or file system. 

Huozi is the romanization of **活字**, the name given by Bisheng to his 11th century invention of moveable type. 

**IMPORTANT:** The **huozi folder** and should be kept in the same folder where the Commander X16 emulator is located in order to run properly. 

## LOADING:

From the home screen of the Commander X16 load the program with 
```
LOAD "HUOZI/HUOZI.PRG"
```
Followed by
```
RUN
```
Once the program is loaded press any key to get past the title screen.

## CONTROLS:

To toggle Chinese input press:
**SHIFT + SPACE**

To toggle Command Mode press:
**CTRL + C**

There are 4 commands the program can preform:
### 1. save
````
save [filename]
````
Which saves a binary text file to the huozi folder and [filename] represents your given name to the file


### 2. load
```
load [filename]
```
Which loads a binary text file from the huozi folder and [filename] represents the given name of the file


### 3. new
````
new
````
Which creates a new document for the user (erasing all current data held in memory)



### 4. color
```
color [0-9]
```
Which sets the text color to one of the ten selected colors


## Demo
In Command Mode try out
```
load data
```
To see a text file containing 4800 Chinese Characters

```
load david
```
To see some PETSCII art

