
<!-- _coverpage.md -->

# <font color=#1C86EE>Main Page</font>
***
# **About Us**
idisplaymodule.com is an professional display sharing website.  
We focus on the development of various display modules, minimize the development time and development cost of customers, and help customers to market the fastest.  
Tech Support Email: xden@sina.cn

# **Getting Started**
**ePaper Module**

**OLED Module**

**UART LCD Module （TFT LCD Module with UART）**   
TFT serial screen series is the current display industry front-end technology "configuration technology" based on the development of serial color screen products, users only need to go through a serial port, You can use RS485, RS232 or a simpler 51 MCU UART interface to easily achieve text, pictures, audio and video, curves, two-dimensional code, instrumentation, animation, progress bar, data recording and touch and other functions of the control and data transmission, without the need to take up a lot of controller interface and storage space like the old display screen. At the same time, it also improves the anti-interference ability of the product.  

**Android LCD Module （TFT LCD Module with Android system）**

# **ePaper (e-ink screen)**

## ePaper Module Components 

Electronic ink is coated on a layer of plastic film, and then coated with a thin-film transistor (TFT) circuit, controlled by the driver IC, to form pixel graphics, creating electronic paper displays (EPD), also commonly known as ink screens, ink screens, etc., specifically and subtly described as a screen made of ink and like ink.

### Two Particle Ink System <!-- {docsify-ignore} -->  
E Ink’s two particle electronic ink system is made up of millions of tiny microcapsules, each about the diameter of a human hair.  Each microcapsule contains negatively charged white particles and positively charged black particles suspended in a clear fluid.  When a positive or negative electric field is applied, corresponding particles move to the top of the microcapsule where they become visible to the viewer.  This makes the surface appear white or black at that spot.

![](双色电子墨水原理_en.gif)
### Three Particle Ink System <!-- {docsify-ignore} -->

The three-color e-ink system works similarly to the two-color system, applying different voltages to cause particles of different colors to move to the upper layer and see different colors. The tri-color system was developed under the Microcup® Eink patent architecture.
![](三色电子墨水原理_en.gif)
## ePaper Module Characteristics 

### Bi-Stability <!-- {docsify-ignore} -->

No power is needed to hold an image.

E Ink's technology is commonly referred to as "bistable". Bistablility refers to the fact that an image on an E Ink screen will be retained even when all power sources are removed. This means that the display is consuming power only when something is changing. For example, when reading on an eReader, power is only needed when turning to a new page but no power is consumed by the display while reading the page. Bistability significantly reduces the power consumption and is a key reason devices using E Ink have such long battery life. The larger ePaper screen, the more electronic power can be saved compared with the same size LCD screen.

### Reflective <!-- {docsify-ignore} -->
 
No backlight is used.

E Ink displays are referred to as "reflective displays." In an LCD, or "emissive display", light from a backlight is projected through the display towards your eyes. In an E Ink display, no backlight is used; rather, ambient light from the environment is reflected from the surface of the display back to your eyes. As with any reflective surface, the more ambient light, the brighter the display looks. This attribute mimics traditional ink and paper, and users of E Ink displays have said that they do not have the same eye fatigue as with LCDs when reading for long periods of time. Eliminating the need for a backlight significantly increases the battery life versus using a traditional LCD.
### Rugged <!-- {docsify-ignore} -->

Plastic-based films enable durable displays.

E Ink displays are comprised of an ink layer laminated to a plastic film substrate. Depending on the application, product designers may use a traditional glass-based TFT, or utilize our E Ink Mobius plastic-based TFTs.

Plastic-based TFTs allow the end product to be substantially lighter and thinner than products using glass-based TFTs. In addition, glass-based TFTs can be fragile; use of plastic-based TFTs can result in a more rugged end product with less breakage in the electronics due to drops or stress tension.

A 13.3" E Ink displays with a plastic TFT and similar internal components can weigh only 12.3 ounces (349g) as compared to an LCD-based display with smaller screen size 12.9”, which weighs an average of 25.2 ounces (713g).

E Ink also offers a simple segmented product line, E Ink SURF™. In this product line, a drive line is routed to each segment, making for a conformable, rugged, all plastic display, suitable for simple character- or icon-based displays. 

![](电子纸特性.jpg)

## ePaper Module Selection 
| Size(inch) | Color | Resolution | Active Area(mm)     | TFT Area(mm)      | Driver IC | "Operate temperature(℃)" | "Storage temperature(℃)" | Remark                |
|------------|-------|------------|---------------------|-------------------|-----------|--------------------------|--------------------------|-----------------------|
| 1.54       | BW    | 152*152    | 27.0(H)x27.0(V)     | 31.8(H)×37.32(V)  | UC8251D   | 0~40                     | -25~40                   |                       |
| 1.54       | BWR   | 152*152    | 27.0(H)x27.0(V)     | 31.8(H)×37.32(V)  | UC8251D   | 0~40                     | -25~40                   |                       |
| 1.54       | BW    | 152*152    | 27.0(H)x27.0(V)     | 31.8(H)×37.32(V)  | UC8251D   | -25~10                   | -25~40                   | Ultra-low temperature |
| 2.13       | BWR   | 122*250    | 48.55(H)x23.70(V)   | 59.2(H)*29.2(V)   | JD79656   | 0~40                     | -25~40                   |                       |
| 2.13       | BW    | 122*250    | 48.55(H)x23.70(V)   | 59.2(H)*29.2(V)   | UC8251D   | 0~40                     | -25~40                   |                       |
| 2.13       | BW    | 122*250    | 48.55(H)x23.70(V)   | 59.2(H)*29.2(V)   | UC8251D   | -25~10                   | -25~40                   | Ultra-low temperature |
| 2.66       | BWR   | 152*296    | 60.09(H)x30.7(V)    | 71.82(H)*36.3(V)  | JD79651   | 0~40                     | -25~40                   |                       |
| 2.66       | BW    | 152*296    | 60.09(H)x30.7(V)    | 71.82(H)*36.3(V)  | UC8251D   | 0~40                     | -25~40                   |                       |
| 2.9        | BWR   | 128*296    | 66.9(H)×29.06(V)    | 79.0(H)×36.7(V)   | JD79651B  | 0~40                     | -25~40                   |                       |
| 2.9        | BW    | 128*296    | 66.9(H)×29.06(V)    | 79.0(H)×36.7(V)   | UC8251D   | 0~40                     | -25~40                   |                       |
| 4.2        | BW    | 400*300    | 84.8 (H)×63.6 (V)   | 91.0 (H)×77.0(V   | UC8276    | 0~40                     | -25~40                   |                       |
| 4.2        | BWR   | 400*300    | 84.8 (H)×63.6 (V)   | 91.0 (H)×77.0(V   | UC8276    | 0~40                     | -25~40                   |                       |
| 5.83       | BWR   | 648*480    | 118.778(H)X88.22(V) | 125.4(H)×99.5 (V) | UC8179    | 0~40                     | -25~40                   |                       |
| 5.83       | BW    | 648*480    | 118.778(H)X88.22(V) | 125.4(H)×99.5 (V) | UC8179    | 0~40                     | -25~40                   |                       |
| 7.5        | BWR   | 800*480    | 163.2 (H)×97.92 (V) | 170.2(H)×111.2(V) | UC8179    | 0~40                     | -25~40                   |                       |
| 7.5        | BW    | 800*480    | 163.2 (H)×97.92 (V) | 170.2(H)×111.2(V) | UC8179    | 0~40                     | -25~40                   |    

Please contact us by email for more model .Four Colors ePaper module mass production.  
# **OLED Module**

## What is OLED?
Organic Light-Emitting Diodes (OLED) display monitors, also referred to as Organic Electroluminescence (OEL) display monitors, have the new generation of technology that is not easily reached by other flat-screen display technology – brighter and clearer full-colored images and faster response times.

The basic structure of OLED uses thin and transparent indium tin oxide (ITO) with semiconductor properties as the anode with a metallic cathode to sandwich the organic material layer. The organic material layer includes the hole transport layer (HTL), emissive layer (EL), and the electron transport layer (ETL). When the battery provides suitable voltage (characteristics of low voltage), and electrical charges combine in the anode hole and the cathode at the emissive layer, it elicits electroluminescence in the organic material. The framework of the organic layer and selection and design of the anode and cathode are keys to light emission by OLED devices.

## OLED Characteristics
	Self-lighting, no backlight required module and color filter
	Light and thin (< 2mm)
	Simple structure, high durability, low cost
	Low starting power (3 ~ 9V) and power-saving
	Free Viewing Angle, bright and distinct screen from anywhere.
	High brightness
	Good luminance (16LM/W)
	High contrast (>10,000:1)
	Excellent picture quality in both dark view and bright view
	Fast response speed (10μs)
	Full color capability
	Large size possible
	Flexibility (plastic base is used)
	Broad range of usable temperatures:-40℃~85℃
Using OLED displays immediately, to enhance the value of your product!   
## OLED Module Selection  
| Size（inch） | Color       | Gray level    | Product structure | Pannel Size（mm） | A.A Size（mm）    | Interface                 | "Operate temperature(℃)" | "Storage temperature(℃)" |
|------------|-------------|---------------|-------------------|-----------------|-----------------|---------------------------|--------------------------|--------------------------|
| 0.49       | White       | Monochrome    | COG+FPC           | 14.5*11.6       | 11.14*5.56      | SPI                       |  -40 to 70               |  -40 to 85               |
| 0.68       | White       | Monochrome    | COG+FPC           | 19.25*10.56     | 16.3*5.42       | SPI/I2C                   |  -40 to 70               |  -40 to 85               |
| 0.84       | White       | Monochrome    | COG+FPC           | 25.3*12.6       | 19.18*9.58      | 6800/8080/SPI/I2C         |  -40 to 70               |  -40 to 85               |
| 0.91       | White       | Monochrome    | COG+FPC           | 28.58*18.78     | 12.85*19.18     | I2C/SPI                   |  -40 to 70               |  -40 to 85               |
| 0.95       | Full colors | 65K           | COG+FPC           | 24.8*22.42      | 20.135*13.42    | 6800/8080/SPI/I2C         |  -40 to 70               |  -40 to 85               |
| 0.96       | Full colors | 66K           | COG+FPC           | 21.4*23.8       | 17.255*17.26    | SPI                       |  -40 to 70               |  -40 to 85               |
| 0.96       | White       | Monochrome    | COG+FPC           | 19.8*23.7       | 17.26*17.26     | SPI                       |  -40 to 70               |  -40 to 85               |
| 0.96       | Full colors | 262K/65K      | COF+FPC           | 14.1*28.4       | 10.8*21.692     | 6800,4-wire SPI           |  -40 to 70               |  -40 to 85               |
| 1.12       | White       | Monochrome    | COG+FPC           | 22.8*26.9       | 20.14*20.14     | SPI/I2C                   |  -40 to 70               |  -40 to 85               |
| 1.13       | Full colors | 262K/65K      | COF+FPC           | 16.14*32.3      | 12.838*25.66    | 8080/6800/4-SPI           |  -40 to 70               |  -40 to 85               |
| 1.3        | White       | Monochrome    | COG+FPC           | 35.8*17.1       | 29.42*14.7      | SPI/I2C                   |  -40 to 70               |  -40 to 85               |
| 1.32       | White       | 16 gray scale | COG+FPC           | 30.9*27.1       | 26.85*20.14     | 6800/8080/SPI/I2C         |  -40 to 70               |  -40 to 85               |
| 1.54       | White       | 16 gray scale | COG+FPC           | 42.1*21.75      | 35.052*17.516   | 8080/6800/3SPI/4SPI/IIC   |  -40 to 70               |  -40 to 85               |
| 1.62       | White       | 16 gray scale | COG+FPC           | 46.28*15        | 39.66*10.86     | SPI                       |  -40 to 70               |  -40 to 85               |
| 1.77       | Full colors | 256Kor65K     | COG+FPC           | 41.88*35.83     | 35.0292*28.0024 | 8-6800/8-8080/3,4-SPI/I2C |  -40 to 70               |  -40 to 85               |
| 1.84       | Full colors | Full colors   | COG+FPC           | 52.5*16         | 46.05*7.852     | 8080                      |  -40 to 70               |  -40 to 85               |
| 1.92       | Amber       | 16 gray scale | COG+FPC           | 20.8*53.6       | 16.94*45.74     | I2C                       |  -40 to 70               |  -40 to 85               |
| 1.92       | White       | 64灰度          | COG+FPC           | 46.1*36.4       | 39.34*28.91     | 8-6800/8-8080/3,4-SPI/I2C |  -40 to 70               |  -40 to 85               |
| 2.23       | Yellow      | 16 gray scale | COG+FPC           | 62.0*24.0       | 55.02*13.1      | 3/4SPI、6800、8080          |  -40 to 70               |  -40 to 85               |
| 2.25       | White       | 16 gray scale | COG+FPC           | 26.15*61.1      | 21.7*53         | SPI                       |  -40 to 70               |  -40 to 85               |
| 2.25       | White       | Monochrome    | COG+FPC           | 61.1*24.48      | 52.9886*21.676  | 4-SPI/I2C                 |  -40 to 70               |  -40 to 85               |
| 2.40       | White       | Gray scale    | COG+FPC           | 62.5*30.6       | 55.01*26.55     | 6800/8080/SPI/I2C         |  -40 to 70               |  -40 to 85               |
| 2.40       | White       | Gray scale    | COG+FPC           | 62.5*30.6       | 55.01*26.55     | 6800/8080/SPI/I2C         |  -40 to 70               |  -40 to 85               |
| 2.7        | Yellow      | Monochrome    | COG+FPC           | 68.4*37.7       | 61.415*30.695   | SPI/I2C/8080/6800         |  -40 to 70               |  -40 to 85               |
| 2.7        | Yellow      | 16 gray scale | COG+FPC           | 73.0*41.86      | 61.41*30.69     | 6800/8080/SPI             |  -40 to 70               |  -40 to 85               |
| 2.70       | White       | 16 gray scale | COG+FPC           | 71.3*34         | 61.414*29.956   | 6800/8080/SPI/I2C         |  -40 to 70               |  -40 to 85               |
| 2.80       | Blue        | 16 gray scale | COF               | 84*25.8         | 69.1*17.26      | 6800/8080/SPI             |  -40 to 70               |  -40 to 85               |
| 2.80       | White       | 16 gray scale | COG+FPC           | 77.5*23.1       | 69.1*17.26      | SPI                       |  -40 to 70               |  -40 to 85               |

Please contact us by email for more model .

# **Where to buy？** 
Email： 542165823@qq.com 



