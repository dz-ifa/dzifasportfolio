---
title: "Syringe Pump"
excerpt: "In this project I created a Syringe pump for medical or research applications  "
header:
  image: /assets/img/syrine pump2.png  
  teaser: /assets/img/syring pump1.png
gallery:
  - url: /assets/img/syring pump1.png
    image_path: assets/img/syring pump1.png
    alt: "placeholder image 1"
  - url: /assets/img/syringepump3.jpg
    image_path: assets/img/syringepump3.jpg
    alt: "placeholder image 2"
  - url: /assets/img/syringepump4.png
    image_path: assets/img/syringepump4.png
    alt: "placeholder image 3"
---


Syringe Pumps are devices that are used for both research and medical purposes to administer precise amounts of fluid over set time periods. There are many benefits of a syringe pump over a other forms of pump. A few of these advantages are:
* Sterility and minimal cross-contamination when swapping syringes 
* Pumping of high viscous fluids
* High accuracy
* Non-pulsatile flow

{% include gallery caption="Syringe Pump" %}

# Features

*  A **pause button** that can start or stop the pump's movement at any time.
    
* Driven by a **stepper motor** coupled to a **lead screw**.
    
* An **LED Status light**  :Green when running, blue when paused, and red when the pump has no more liquid.
    
* An **Arduino** is used to control the system and do all computation
    
* A **dial** to control the flow rate and direction of the syringe pump.
    
* The **flow rate** and **time left** is outputted onto an **LCD**.
    
* The syringe pump enclosure is designed to allow for **easy access** to electrical components while also providing protection from any water spillage that may occur as well as protecting the user from the components.

    
* The syringe pump is compatible with syringes of **two different diameters** and they can easily be changed without the use of any external tools.

* A **limit switch** is automatically triggered once the syringe has expelled all of the liquid and stops pump movement.
    



# Off Shelf Parts

 - [200 mm lead screw with 2 mm pitch and 2 mm lead](https://www.amazon.com/dp/B07R1H5ZMV/ref=cm_sw_em_r_mt_dp_0YZ13D4HQBGW2Z86PBV1?_encoding=UTF8&psc=1)

 - [250 mm lead screw with 2 mm pitch and 8 mm lead](https://amzn.to/3infwI0)

 - [1/4" x 8mm Flexible Coupling](https://openbuildspartstore.com/1-4-x-8mm-flexible-coupling/)

 - [200 mm linear rod with 8 mm diameter](https://www.amazon.com/dp/B07MPGWJMS/ref=cm_sw_em_r_mt_dp_X5AQS0ES7JH8JG83AAZ3)

 - [LM8UU Linear bearing for 8 mm diameter rod](https://www.amazon.com/gp/product/B087WPGQ8T/ref=ppx_yo_dt_b_asin_image_o00_s00?ie=UTF8&psc=1)

 - [2040 Aluminum Extrusion 1' Length](https://www.mcmaster.com/5537T111-5537T705/)

 - [Nema 17 Stepper Motor](https://amzn.to/3uhifWk)

 - [MEAN WELL RQ-65D AC-DC Power Supply Quad Output 5V 12V 24V 12V 4 Amp](https://www.amazon.com/dp/B005T9HGLI/ref=cm_sw_em_r_mt_dp_A8CZ056TM52EJGZTGZGR?_encoding=UTF8&psc=1)

 - [Arduino Uno](https://www.amazon.com/dp/B007R9TUJE/ref=cm_sw_em_r_mt_dp_TY8JGK0CJD1JEJM4BNNJ)

 - [A4988 Stepper Driver](https://www.amazon.com/dp/B01FFGAKK8/ref=cm_sw_em_r_mt_dp_V0YKTYKDWMR8WHTKA53T?_encoding=UTF8&psc=1)

 - [Small Breadboard](https://www.amazon.com/dp/B082VYXDF1/ref=cm_sw_em_r_mt_dp_N6Q28CAGPAYCKCSJKDDC?_encoding=UTF8&psc=1)

 - [Panel Mount Latching Push Buttons](https://amzn.to/3VxQ29h)

 - [Limit Switch](https://amzn.to/3Veb1Ox)


 - [RGB Common Cathode LED](https://www.amazon.com/dp/B0194Y6MW2/ref=cm_sw_em_r_mt_dp_FW3CFQT7ZGFQ2R04N6G3?_encoding=UTF8&psc=1)

# 3D Printed parts

 - Syringe Pump Enclosure
 - Motor Mount
 - Syringe Holder

# [Arduino Code Repository](https://github.com/dz-ifa/dz-ifa.github.io/blob/main/syrinepump3txt.txt)

# CAD Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH35dfcQT936092f0e438cdf6d181a387965?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

#  Pump Operation Instructions

Operation of the syringe pump is a fairly simple process. First rotate the control dial to the left to retract the pump and make space for the syringe. Next take the loaded syringe and slide it into the syringe holder and adjust the start position using the control dial. Once the syringe pump is properly loaded, hit the start/stop button to pause the pump movement and set the flow rate with the control dial. The flow rates will be showcased on the LCD monitor. Once the correct rate is displayed press the start/stop button again to start dispensing liquid. Motion can be stopped at any time by pressing the start/stop button again. Once the syringe pump has finished dispensing the pump will automatically stop. The syringe pump can be unloaded using the control dial in the same way as loading.
