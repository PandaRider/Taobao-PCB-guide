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
This guide assumes basic knowledge of Printed Circuit Board (PCB) design in any PCB design software. We'll use EagleCAD in this guide but it should be similar to other PCB design software that can generate Gerber files (e.g. KiCAD). For Altium users, you can simply use the .PcbDoc file.

We'll also need a taobao + alipay account and aliwangwang installed. (Alternatively, you might want to try [JLC PCB](#JLC PCB service) if this is too much of a hassle.) 

While some knowledge of Chinese is helpful, it is not necessary for the basic PCB designs in this guide. 

### resources
Taobao [account setup guide](https://www.youtube.com/watch?v=tBuuEMSsF58)

Aliwangwang [download site](https://alimarket.taobao.com/markets/qnww/portal-group/ww/download)

Sparkfun Eagle [schematic guide](https://learn.sparkfun.com/tutorials/using-eagle-schematic) and [layout guide](https://learn.sparkfun.com/tutorials/using-eagle-schematic)

JCL PCB [website](https://jlcpcb.com/)

## Comparisons

### PCB prototyping machine

For prototyping, the advantages of PCB prototyping are less obvious. In general, if your project is not urgent and you plan to scale up, Chinese PCB house will be the better choice.

|              | Chinese PCB house                 | FabLab's PCB prototyping machine (LPKF)  |
| ------------ |:---------------------------------:| :---------------------------------------:|
| Speed        | Payment-to-package is ~1.5weeks   | booking-to-board is ~1 afternoon         |
| Board Size   | 5* 5cm to 15 \* 15cm              |                                          |
| Price        | 30 to 50 yuan depending on board  |                                          |

### JLC PCB service

[JLC PCB service](https://jlcpcb.com/) is an alternative for those who wants to skip the hassle of Taobao. The costs of PCBs from JLC starts from $2 and is comparable to Taobao (includes delivery charge). The advantage of taobao is that you can not only buy PCBs but also cheap Integrated Circuits(ICs) as well. If you choose to make a PCB from JLC PCB, you will need to buy the rest of the components from mainstream electronics distributors.

For example, a common ATMega328p from Taobao cost [¥4.80](https://item.taobao.com/item.htm?spm=a230r.1.14.27.26ec255cQJekQx&id=13854666988&ns=1) (S$0.97) compared to [S$3.17](http://sg.element14.com/microchip/atmega328p-au/microcontroller-mcu-8-bit-atmega/dp/1715486) from Element14. The downside of Taobao's relatively lower price is the extra delivery charges and longer delivery time. This price difference is not applicable to all ICs! Also, if you intend to commercialize/mass produce your electronic product, it is recommended to purchase your electronics from mainstream electronics distributors.

Steps for JLC PCB service are not described here as (in my opinion) it's more beneficial to write a guide in a topic readers a struggling in. (Want to contribute? Make a PR!) 
<!-- Moreover, Taobao has way wider variety. -->

## Taobao

### Buying


1. Search `PCB 打样` (making). In general, choose the shop with the lowest price per piece and highest number of reviews/verified purchases.
![screenshot](https://github.com/PandaRider/Taobao-PCB-guide/raw/master/screenshots/tb-search-1.png "Taobao Search 1")
2. Click the small blue mascot at the most right side-bar with the phrase 和我联络. 
![screenshot-3](https://github.com/PandaRider/Taobao-PCB-guide/raw/master/screenshots/tb-search-2.png "Logo Title Text 1")
3. Start chatting! Do regularly copy-paste the replies using Google Translate. Usually the conversation goes something like this
  * `您好`
  * [Copy-Paste the PCB product page's taobao link]
  * `我想做[board-size-in-cm, number-of-layers]`: 
  ![screenshot-1](https://github.com/PandaRider/Taobao-PCB-guide/raw/master/screenshots/tb-chat-1.png "Logo Title Text 1")
  * The PCB house will ask you to upload the PCB files. The screenshot shows Gerber files were uploaded but Altium .PcbDoc files are accepted as well: ![screenshot](https://github.com/PandaRider/Taobao-PCB-guide/raw/master/screenshots/tb-chat-2.png "Logo Title Text 1")
  * The PCB house will confirm with you the process and pricing. 
  * If you are satisfied, reply `确定` (confirm). 
  * He will then refer a link for you to pay through taobao. 
  ![screenshot](https://github.com/PandaRider/Taobao-PCB-guide/raw/master/screenshots/tb-chat-3.png "Logo Title Text 1")
  * Sometimes, you might need to adjust the quantity of the purchase at the link. 
4. Go to your cart. Ensure all the parts and components you want to buy appears in the right quantity

5. Checking delivery 

### Pro-tips
1. Do check the local delivery charges
2. For purchases above 100 yuan, you can get a discounted conversion rate through RateX
3. Do watch out for bumped up offers! If the price seems off, just move on to another seller.

### Claiming

Submission of claims depends on your institute's funding procedure. However, you will likely find the steps described here helpful as it passed the mother-of-all-red-tape.

Basically, you need 2 screenshots.

##### Aliwangwang screenshot
  1. Go to https://my.alipay.com/ and login
  2. Scroll to the bottom and click `查看所有交易记录` (see all transactions)
  3. You should see the screenshot below. Click on the any small "Hamburger" menu button.
  ![screenshot-](https://github.com/PandaRider/Taobao-PCB-guide/raw/master/screenshots/ali-1.png "Hamburger button")
  4. Take a screenshot of the entire web page. A sample screenshot is provided below.
  5. Repeat steps 3 and 4 for the rest of the transactions.

By now you should have all 
![]()

2. 

## Improvements

## Conclusion

### Motivation
In case you have been living under a rock, hardware frequently gets a bad rep for being *hard*. It is hard to scale, hard to prototype cheaply, hard to price competitively etc. The country I live in, Singapore, is often discouraged by our small market size. Yet, 

It is a matter of making the best of what we have. 


