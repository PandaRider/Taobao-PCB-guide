A walkthrough guide on buying electronics online from China. 

## Table of Contents

Table of contents:
* [Pre-requisites](#Pre-requisites)
  * [resources](#resources)
* [Comparisons & alternatives](#Comparisons)
* [Taobao](#Taobao)
  * [Buying](#Buying)
  * [Pro tips](#Pro tips)
  * [Claiming](#Claiming)
* [Improvements]()
* [Conclusion](#Conclusion) (w/credits)
  * [Motivation](#Motivation)


## Pre-requisites
This guide assumes basic knowledge of Printed Circuit Board (PCB) design in any PCB design software. We'll use EagleCAD in this guide but it should be similar to other PCB design software that can generate Gerber files like KiCAD. For Altium users, you can simply use the .PcbDoc file.

We'll also need a taobao + alipay account and aliwangwang installed. (Alternatively, you might want to try [JLC PCB](#JLC PCB service) if this is too much of a hassle)

While some knowledge of Chinese is helpful, it is not necessary for the basic PCB designs in this guide. 

### resources
Taobao [account setup guide](https://www.youtube.com/watch?v=tBuuEMSsF58)
Sparkfun Eagle [schematic guide](https://learn.sparkfun.com/tutorials/using-eagle-schematic) and [layout guide](https://learn.sparkfun.com/tutorials/using-eagle-schematic)

[JCLPCB](https://jlcpcb.com/)

## Comparisons

### PCB prototyping machine

For prototyping, the advantages of PCB prototyping are less obvious. In general, if your project is not urgent and you plan to scale up, Chinese PCB house will be the better choice.

|              | Chinese PCB house                 | FabLab's PCB prototyping machine (LPKF)  |
| ------------ |:---------------------------------:| :---------------------------------------:|
| Speed        | Payment-to-package is ~1.5weeks   | booking-to-board is ~1 afternoon         |
| Board Size   | 5* 5cm to 15 \* 15cm              |                                          |
| Price        | 30 to 50 yuan depending on board  |                                          |

### JLC PCB service

JLC PCB service is an alternative for those who wants to skip the hassle of Taobao. The costs of PCBs are similar (includes delivery charge). The only advantage of taobao is that the price of ICs are much cheaper as compared to local electronic distributors (RS or element14). 

For example, a common ATMega328p from Taobao cost [14 yuan]() (S$3) compared to [S$5]() from Element14. This price difference is not applicable to all ICs! Also, if you intend to commercialize/mass produce your electronic product, the quality assurance from mainstream electronic distributors should justify the margin.

## Taobao

### Buying


1. Search "PCB 打样" (making). In general, choose the shop with the lowest price per piece and highest number of reviews/verified purchases.
![screenshot-2](https://github.com/PandaRider/Taobao-PCB-guide/raw/master/screenshots/tb-search-1.png "Logo Title Text 1")
2. Click the small blue mascot at the most right side-bar with the phrase 和我联络. 
![screenshot-3](https://github.com/PandaRider/Taobao-PCB-guide/raw/master/screenshots/tb-search-2.png "Logo Title Text 1")
3. Start chatting! Do regularly copy-paste the replies using Google Translate. Usually the conversation goes something like this
  1. "您好"
  2. [Copy-Paste the PCB product page's taobao link]
  3. 我想做[board-size-in-cm, number-of-layers]: 
  ![screenshot-1](https://github.com/PandaRider/Taobao-PCB-guide/raw/master/screenshots/tb-chat-1.png "Logo Title Text 1")
  4. The PCB house will ask you to upload the PCB files. The screenshot shows Gerber files were uploaded but Altium .PcbDoc files are accepted as well: ![screenshot](https://github.com/PandaRider/Taobao-PCB-guide/raw/master/screenshots/tb-chat-2.png "Logo Title Text 1")
  5. The PCB house will confirm with you the process and pricing. 
  6. If you are satisfied, reply "确定" (confirm). 
  7. He will then refer a link for you to pay through taobao. 
  ![screenshot](https://github.com/PandaRider/Taobao-PCB-guide/raw/master/screenshots/tb-chat-3.png "Logo Title Text 1")
  6. Sometimes, you might need to adjust the quantity of the purchase at the link. 
4. Go to your cart. Ensure all the parts and components you want to buy appears in the right quantity

5. Checking delivery 

### Pro-tips
1. Do check the local delivery charges
2. For purchases above 100 yuan, you can get a discounted conversion rate through RateX
3. Do watch out for bumped up offers! If the price seems off, just move on to another seller.

### Claiming

Submission of claims depends on your institute's funding procedure. However, you will likely find the steps described here helpful as it passed the mother-of-all-red-tape.

In short, you need 2 screenshots.

1. Aliwangwang screenshot
![]()

2. 

## Improvements

## Conclusion

### Motivation
In case you have been living under a rock, hardware frequently gets a bad rep for being *hard*. It is hard to scale, hard to prototype cheaply, both of which made harder in Singapore with it's small size and advanced economy. 

It is a matter of making the best of what we have. 

