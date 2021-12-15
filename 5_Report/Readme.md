# WORD PUZZLE GAME

## Introduction

A Word puzzle is a  game where a random series of characters comes and player have to  rearrange it in a correct  particular (English) word. For example the jumble "cclier" can be decoded as "circle".
This game can  be a basic starter package for small children who just started to learn sentences. The extend contains as it were the client-side. The user can begin the test by clicking on the begin button.In this user can also alter the jumbled words in case they don't know the proper word for them.

In this game  user has to first choose which categories they want to play like fruits,shapes etc, then after that respective question will appear on screen. You'll be able to alter the words on the off chance that you're not able to figure the proper shape. Moreover, you'll be able to check the answer at, to begin with, in the event that you have the points.

## Defining Our System
In this project, when we excute the code then the game starts with a pop up. On that pop up click on start. when the game starts, user have to select the categories like Animals, Body parts, Colour, Fruits, Shapes, Vegetables, Vehicles etc. click on the category that user wants to play then user get jumbled word of selected category and they have to answer the jumbled word in text box. If client gives the correct answer by writing it in text box and click on submit, then client get a pop up window "correct answer keep it up" and they also get score. If user answer is wrong then screen shows "incorrect answer try your best" and as  answer is wrong then no score will be given. If user does not understand the jumbled word then there will be a option of changing the word. If user wants to know the answer without answering the jumbled words then answer will get shown but user marks will be deduct by the system.
## SWOT Analysis

![SWOT](https://user-images.githubusercontent.com/89648059/135571978-cdfdad96-7cb2-459b-9a01-5f76caa0839c.png)


## 4W's and 1'H

## what
It is a game where we can learn spellings correctly.

## when
Anytime we can play this game when you are free.

## where 
We can play this game in electronic gadgets where the game is installed.

## why
To improve IQ levels and  to learn spellings. 

## How
By selecting the category that we want to play.

## DETAIL REQUIREMENTS

## High level requirements

| ID    |                    DESCRIPTION                                           |CATEGORY|   STATUS  |
|-------|--------------------------------------------------------------------------|--------|-----------|   
| HR01  |   The Application should allow User to enter info.                       |Technical|IMPLEMENTED|
| HR02  |   The Application should allow User to login.                            |Technical|IMPLEMENTED|
| HR03  |   The Application should display Main Window to User.                    |Technical|IMPLEMENTED| 
| HR04  |   The Application should display Menu to User.                           |Technical|IMPLEMENTED|                            
| HR05  |   The Application should allow User to choose Menu.                      |Technical|IMPLEMENTED|
| HR06  |   The Application should display score to User.                          |Technical|IMPLEMENTED|
| HR07  |   After getting score,The application should display another jumble word.|Technical|IMPLEMENTED|
| HR08  |   The Application should allow user to go back to main window.           |Technical|IMPLEMENTED|



## Low level requirements


| ID    |                    DESCRIPTION                                                           | HLR ID|   STATUS  |
|-------|------------------------------------------------------------------------------------------|-------|-----------|
| LR01  |   The Application should allow User to enter Username and Password.                      | HR01  |IMPLEMENTED|                                                    
| LR02  |   The Application should display start button.                                           | HR03  |IMPLEMENTED|
| LR03  |   The Application should show the jumbled word to user.                                  | HR05  |IMPLEMENTED| 
| LR04  |   The Application should allow user to enter answer in textbox.                          | HR05  |IMPLEMENTED|
| LR05  |   The Application should display whether the answer is correct or wrong to User.         | HR06  |IMPLEMENTED|
| LR06  |   The Application should allow to user answer in textbox.                         | HR07  |IMPLEMENTED|
| LR07  |   The Application should allow user can exit from application.                           | HR08  |IMPLEMENTED|
   
## UML DIAGRAM 
## Behavioral Structure
## HLR Flow chart
![UML Diagram HLR](https://user-images.githubusercontent.com/89586742/135494927-d9d5d7f8-3f98-4a36-a3c3-c2a88d50ff59.jpg)
## LLR Flow chart
![UML DIAGRAM LLR](https://user-images.githubusercontent.com/89586742/135495134-94791184-4e5c-47eb-961e-c2cd925d4326.jpg)

# ARCHITECTURE
## High Level Architecture

![STRUCTUAL DIAGRAM ](https://user-images.githubusercontent.com/89648059/135462513-6285f51d-def4-43cc-a9d8-586bdf7de215.png)
## Low Level Architecture

![STRUCTUAL DIAGRAM 1](https://user-images.githubusercontent.com/89648059/135462788-2831949e-e46b-40ba-9244-7b2cd1df0409.png)


## HIGH LEVEL TEST PLAN


| Test ID | Description | Expected i/p | Expected o/p | Actual o/p | Status |
| ---     | ---         | ---          | ---          | ---        | ---    |
| `HRO1`  |  start the jumbled quiz | click start button | displaying menu list | displaying menu list | pass |
| `HRO2`  | check if the menu displayed or not |select the one button in the menu  | redirect into the selected category |selected category displayed | pass |
| `HRO3`  | if we want to reach again on home page | click on back arrow button | home page | home page | pass |                                       
| `HRO4`  | play the game what you choosed | type the assumed jumbled word | wrong answer | correct answer | fail |
| `HRO5`  | if we want check answer we can select from menu | click on answer button | Answer will be displayed |  answer displayed points decreased by 5| pass |
| `HRO6`  | if we want to change the word | click on change button | the jumble word changed | jumble word changed | pass |


## LOW LEVEL TEST PLAN


| Test ID | Description | Expected i/p | Expected o/p | Actual o/p | Status |
| ---     | ---         | ---          | ---          | ---        | ---    |
| `LO1`   | Enter the correct word from  menu | Enter word | word is correct | correct | pass |
| `LO2`   | Enter the word from menu RONGEA | ORANGE | ORANGE | ORANGE points : 5 | pass | 
| `LO3`   | Enter the word from menu RONGEA | ERANGO | RENAOG  | ORANGE | fail |
| `LO4`   | If we want check answer we can select from menu | Answer will be displayed | Answer will be displayed | No Points answer displayed | pass |
| `LO5`  |we can select what feature we want from menu | Type valid word | correct points : 6 | correct points : 5 | fail |

# Image of Working Project

## Code Simulataion

## Start Page of an application 


![1](https://user-images.githubusercontent.com/89724393/135766527-1e0fa67a-15ab-4236-88f9-9acd6250367f.JPG)


## After clicking start

## Main Menu


![2](https://user-images.githubusercontent.com/89724393/135766539-884dcfcc-478f-4aef-92e5-24ee94ee3b12.JPG)



## Jumble Color Quiz


![3](https://user-images.githubusercontent.com/89724393/135766626-4cfbddc4-beb9-47fa-ad49-a809e090e986.JPG)


## Corect Answer & Score  5 Points 

![4](https://user-images.githubusercontent.com/89724393/135766636-6dc3d90e-2458-4eeb-a22f-4a9c14cea3c0.JPG)


![Capture](https://user-images.githubusercontent.com/89724393/135766682-83a7d3d4-bac8-4af4-8347-fb630cf37298.JPG)


## Example 2

![WhatsApp Image 2021-10-02 at 13 46 11 (1)](https://user-images.githubusercontent.com/89724393/135746145-adef5429-d14e-4752-852d-3e098f464f37.jpeg)

# Output Video of Working Program


https://user-images.githubusercontent.com/65173670/135751735-92474222-cf82-4dd6-a3b5-3c52ad80d501.mp4

