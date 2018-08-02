A walkthrough guide on buying electronics online from China. 

## Table of Contents

* [Pre-requisites](#Pre-requisites)
  * [Resources](#Resources)
* [Comparisons & Alternatives](#comparisons--alternatives)
* [Taobao](#Taobao)
  * [Buying](#Buying)
  * [Tips & Tricks](#tips--tricks)
  * [Claiming](#Claiming)
* [Improvements & Feedback](#improvements--feedback)
* [Conclusion](#Conclusion) (w/credits)
  * [Motivation](#Motivation)
  * [Credits](#Credits)


## Prerequisites
This guide assumes basic knowledge of Printed Circuit Board (PCB) design in any PCB design software including EagleCAD, KiCAD or any .gerber generating software. If you wish to learn PCB design or need a refresher, the Sparkfun Eagle guides below provide a concise introduction. For Altium users, you may directly send your .PcbDoc files instead of the .gerber files in step 4d.

You'll also need a Taobao + Alipay account and Aliwangwang installed. (Alternatively, you might want to try [JLC PCB](#jlc-pcb-service) if this is too much of a hassle :satisfied:.) 

While some knowledge of Chinese is helpful, it is not necessary for the basic PCB designs in this guide. 

### Resources
* Taobao [account setup guide](https://www.youtube.com/watch?v=tBuuEMSsF58)
* Aliwangwang [download site](https://alimarket.taobao.com/markets/qnww/portal-group/ww/download)
* Sparkfun Eagle [schematic guide](https://learn.sparkfun.com/tutorials/using-eagle-schematic) and [layout guide](https://learn.sparkfun.com/tutorials/using-eagle-schematic)
* JCL PCB [website](https://jlcpcb.com/)

## Comparisons & Alternatives

### PCB prototyping machine

For prototyping, the advantages of PCB prototyping through a PCB house are less obvious. If longer prototype iteration periods is not a problem and you plan to scale up in the future, PCB house will be the better choice.

|              | Chinese PCB house                 | PCB prototyping machine (LPKF)  |
| ------------ |:---------------------------------:| :---------------------------------------:|
| Speed        | Payment-to-package is ~1.5weeks   | booking-to-board is ~1 afternoon         |
| Board Size   | 5 \* 5cm to 15 \* 15cm            | 305mm \* 229mm                           |
| Price        | Starts from ¥30 depending on board| ~~Prepaid w/school fees~~ Free           |

### JLC PCB service

[JLC PCB service](https://jlcpcb.com/) is an alternative for those who wants to skip the hassle of Taobao. The costs of PCBs from JLC starts from USD$2 and is comparable to Taobao (includes delivery charge). The advantage of Taobao is that you can not only buy PCBs but also cheap Integrated Circuits(ICs) as well. If you choose to make a PCB from JLC PCB, you will need to buy the rest of the components from mainstream electronics distributors.

For example, a common ATMega328p from Taobao cost [¥4.80](https://item.taobao.com/item.htm?spm=a230r.1.14.27.26ec255cQJekQx&id=13854666988&ns=1) (S$0.97) compared to [S$3.17](http://sg.element14.com/microchip/atmega328p-au/microcontroller-mcu-8-bit-atmega/dp/1715486) from Element14. The downside of Taobao's relatively lower price is the extra delivery charges and longer delivery time. This price difference is not applicable to all ICs! Also, if you intend to commercialize/mass produce your electronic product, it is recommended to purchase your electronics from mainstream electronics distributors with a quality guarantee.

Steps for JLC PCB service are not described here as (in my opinion) it's more beneficial to write a guide in a topic readers are struggling in. (PR contributions are much appreciated though!) 
<!-- Moreover, Taobao has way wider variety. :wink: -->

## Taobao

### Buying

1. Go to [Taobao](https://world.taobao.com/) and login

2. Search `PCB 打样` (making). In general, choose the shop with the lowest price per piece and highest number of reviews/verified purchases.

![screenshot](https://github.com/PandaRider/Taobao-PCB-guide/raw/master/screenshots/tb-search-1.png "Taobao Search 1")
3. Click the small blue mascot at the most right side-bar with the phrase "和我联络". This will open up Aliwangwang 

![screenshot-3](https://github.com/PandaRider/Taobao-PCB-guide/raw/master/screenshots/tb-search-2.png "Taobao search 2")

4. Start chatting! Do regularly copy-paste the replies using Google Translate. Usually the conversation goes something like this
  * `您好`
  * [Copy-Paste the PCB product page's taobao link]
  * `我想做[board-size-in-cm, number-of-layers]`: 
  ![screenshot-1](https://github.com/PandaRider/Taobao-PCB-guide/raw/master/screenshots/tb-chat-1.png "Taobao chat 1")
  * The PCB house will ask you to upload the PCB files. The screenshot shows Gerber files were uploaded but Altium .PcbDoc files are accepted as well: ![screenshot](https://github.com/PandaRider/Taobao-PCB-guide/raw/master/screenshots/tb-chat-2.png "Taobao chat 2")
  * The PCB house will confirm with you the process and pricing. 
  * If you are satisfied, reply `确定` (confirm). 
  * He will then refer a link for you to pay through taobao. 
  ![screenshot](https://github.com/PandaRider/Taobao-PCB-guide/raw/master/screenshots/tb-chat-3.png "Taobao chat 3")
  * Sometimes, you might need to adjust the quantity of the purchase at the link. 
5. Go to your cart. Ensure all the parts and components you want to buy appears in the right quantity. Click `结算`.
![screenshot](https://github.com/PandaRider/Taobao-PCB-guide/raw/master/screenshots/tb-buy-1.png "Taobao select orders")

6. Ensure the address is correct. You will see 2 options. The top option will directly deliver each item per package. The bottom option will consolidate your items first before delivering in a single package. Needless to say, select the bottom option. Click `提交订单`
![screenshot](https://github.com/PandaRider/Taobao-PCB-guide/raw/master/screenshots/tb-buy-2b.png "Taobao select delivery type")

7. You will re-directed to Alipay to enter your credit card details. 

8. And finally.
![screenshot](https://github.com/PandaRider/Taobao-PCB-guide/raw/master/screenshots/tb-buy-3.png "Taobao complete")

<!-- 9. Checking delivery <To-be-added> -->

### Tips & Tricks
* Do not order your PCB from China during Chinese New Year holidays or Singles day (11 November)
* Do check the local delivery charges
* For purchases above ¥100, you can get a discounted conversion rate through RateX
* Do watch out for bumped up offers! If the price seems suspicious, just move on to another seller.

### Claiming

Submission of claims depends on your institute's funding procedure. However, you will likely find the steps described here helpful as it passed the mother-of-all-red-tape.

Basically, you need 2 screenshots.

#### 1. Alipay screenshot
  1. Go to https://my.alipay.com/ and login
  2. Scroll to the bottom and click `查看所有交易记录` (see all transactions)
  3. You should see the screenshot below. Click on the any small "Hamburger" menu button.
  ![screenshot-](https://github.com/PandaRider/Taobao-PCB-guide/raw/master/screenshots/ali-1.png "Hamburger button")
  4. Take a screenshot of the entire web page. A sample screenshot is provided below.
    ![screenshot-](https://github.com/PandaRider/Taobao-PCB-guide/raw/master/screenshots/ali-2.png "Alipay screenshot")
  5. Repeat steps 3 and 4 for the rest of the transactions.

#### 2. Bank statement screenshot
  You need to download your e-statement from your online bank account. For DBS, the screenshot below shows the relevant transactions. The particular transaction has the **same amount spent in Yuan**   ![screenshot-](https://github.com/PandaRider/Taobao-PCB-guide/raw/master/screenshots/dbs-4.png "DBS screenshot").
  
  You should not use the dates as a reference to any particular transaction as the timestamps from alipay and your bank is often not synchronized

### Receiving
And finally... 
[screenshot-package](https://github.com/PandaRider/Taobao-PCB-guide/raw/master/screenshots/package.png "Package screenshot")


## Improvements & Feedback
If you’ve spotted any mistake in this guide or would like to improve with your own section, do [contact me](edmund_pang@mymail.sutd.edu.sg) (or do a PR :sweat_smile:). 

For questions and clarifications, do [open an issue](https://github.com/PandaRider/Taobao-PCB-guide/issues/new) and I'll answer there. 
<!-- Why github? Can save Readme + collab.  -->
<!-- Future guides: Multicolor pcb 
https://hackaday.com/2018/02/26/successful-experiments-in-multicolor-circuit-boards/ 
https://twitter.com/mrtwinkletwink  -->
## Conclusion

### Motivation

<!-- Why should you do hardware?

In case you have been living under a rock, hardware frequently gets a bad rep for being [hard](https://www.wired.com/story/why-do-startups-fail-because-hardware-is-hard/). It is hard to scale, hard to prototype cheaply, hard to price competitively, etc. All these disadvantages are multiplied when innovating in Singapore due to our small size. That said, we do have a couple of advantages. Our close proximity lowers delivery costs and lead time. A common language and heritage also makes it easier to collaborate. It has never been a good time and place to do good hardware.

How do you do good hardware?

Good hardware takes time. Take the ubiquitous pillbox school project. With all the smart sensors and wireless connectivity features, have you ever seen one that looks friendly to use? Almost always, the Arduino *Unos* and *Nanos* are larger than the box itself. In an essay titled [Hardware, Less Hard](https://blog.ycombinator.com/hardware-less-hard/), it highlighted many considerations like a beautiful design and idea validation that should be done before the project is executed. After the project is executed, you might even consider scaling it up. However, the modus operandi of a school project is from week 1 to week 12 thus, there is little time to do this except once, at last, for the final year project. 

What has PCB design got to do with hardware innovation?

It is cheap to do and (with experience) is relatively fast to prototype. It gives you room to include design aesthetics in your product. It opens the possibility to scale and multiply. It is the hope of this guide that readers consider scaling their ideas... however hard, into goood hardware. -->

<!-- Oh wow, I did not realize I just did a Why,How,What presentation haha -->

Is there more to engineering school than just tests and labs? Yes! There are projects too! However, school projects often just seems like the same old labs but in groups and scoped into a topic. For example, in a Digital Systems [lab](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-111-introductory-digital-systems-laboratory-spring-2006/labs/), each of us learns how to build a pong game FSM with a FPGA. In a DS project, we form a team to make a [super pong game](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-111-introductory-digital-systems-laboratory-spring-2006/projects/group_6/)? We use the word “lab” to imply it is experimental. A “project” can be more than that and a project only goes beyond the experimental when it is scalable.

Thinking about scalability makes you a better engineer. 
+ **Wiser component choices**: Be liberated from general microcontrollers. There's a saying in engineering that a system that is agnostic to everything... is optimized for nothing. For example, do you really need that many pins for your [wearable technology](https://www.adafruit.com/product/659) or would a low power SoC be better suited?
+ **Better design**: Design is forced from an [afterthought](https://blog.ycombinator.com/hardware-less-hard/) to a deliberate design intent. Considerations as simple as where to place mounting holes in your PCB becomes a make-or-break factor in your overall product design.
+ **Understanding technical debt**: Because in the real world, there needs to be a balance between [innovation and business](https://hackaday.com/2017/02/27/the-tiko-printer-what-happens-when-you-innovate-too-much/). 
<!-- The software version of technical debt is temporary code patches -->

Admittedly, learning about scalibility isn't easy and takes time. But the problems you'll be exposed makes it enriching and different from what is taught from engineering schools :muscle:.

