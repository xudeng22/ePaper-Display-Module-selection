
<!-- _coverpage.md -->

# <font color=#1C86EE>Main Page</font>
***
# About idisplaymodule.com
idisplaymodule is an professional display sharing website.  
We focus on the development of various display modules, minimize the development time and development cost of customers, and help customers to market the fastest.  
Tech Support Email: xden@sina.cn

# Getting Started
**ePaper module**

**OLED module**

**UART LCD module （TFT LCD module with UART）**   
TFT serial screen series is the current display industry front-end technology "configuration technology" based on the development of serial color screen products, users only need to go through a serial port, You can use RS485, RS232 or a simpler 51 MCU UART interface to easily achieve text, pictures, audio and video, curves, two-dimensional code, instrumentation, animation, progress bar, data recording and touch and other functions of the control and data transmission, without the need to take up a lot of controller interface and storage space like the old display screen. At the same time, it also improves the anti-interference ability of the product.  

**Android LCD module （TFT LCD module with Android system）**

# **ePaper (e-ink screen)**

## ePaper Module Components 

Electronic ink is coated on a layer of plastic film, and then coated with a thin-film transistor (TFT) circuit, controlled by the driver IC, to form pixel graphics, creating electronic paper displays (EPD), also commonly known as ink screens, ink screens, etc., specifically and subtly described as a screen made of ink and like ink.

### Two Particle Ink System <!-- {docsify-ignore} -->  
E Ink’s two particle electronic ink system is made up of millions of tiny microcapsules, each about the diameter of a human hair.  Each microcapsule contains negatively charged white particles and positively charged black particles suspended in a clear fluid.  When a positive or negative electric field is applied, corresponding particles move to the top of the microcapsule where they become visible to the viewer.  This makes the surface appear white or black at that spot.

![](双色电子墨水原理.gif)
### Three Particle Ink System <!-- {docsify-ignore} -->

The three-color e-ink system works similarly to the two-color system, applying different voltages to cause particles of different colors to move to the upper layer and see different colors. The tri-color system was developed under the Microcup® Eink patent architecture.
![](三色电子墨水原理.gif)
## ePaper Module Benefits 

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

## ePaper selection 
| Size | Color | Resolution | Active Area mm      | TFT Area mm       | Driver IC | Operate temperature（℃） | Storage temperature（℃） | Remark                |
|------|-------|------------|---------------------|-------------------|-----------|--------------------------|--------------------------|-----------------------|
| 1.54 | BW    | 152*152    | 27.0(H)x27.0(V)     | 31.8(H)×37.32(V)  | UC8251D   | 0~40                     | -25~40                   |                       |
| 1.54 | BWR   | 152*152    | 27.0(H)x27.0(V)     | 31.8(H)×37.32(V)  | UC8251D   | 0~40                     | -25~40                   |                       |
| 1.54 | BW    | 152*152    | 27.0(H)x27.0(V)     | 31.8(H)×37.32(V)  | UC8251D   | -25~10                   | -25~40                   | Ultra-low temperature |
| 2.13 | BWR   | 122*250    | 48.55(H)x23.70(V)   | 59.2(H)*29.2(V)   | JD79656   | 0~40                     | -25~40                   |                       |
| 2.13 | BW    | 122*250    | 48.55(H)x23.70(V)   | 59.2(H)*29.2(V)   | UC8251D   | 0~40                     | -25~40                   |                       |
| 2.13 | BW    | 122*250    | 48.55(H)x23.70(V)   | 59.2(H)*29.2(V)   | UC8251D   | -25~10                   | -25~40                   | Ultra-low temperature |
| 2.66 | BWR   | 152*296    | 60.09(H)x30.7(V)    | 71.82(H)*36.3(V)  | JD79651   | 0~40                     | -25~40                   |                       |
| 2.66 | BW    | 152*296    | 60.09(H)x30.7(V)    | 71.82(H)*36.3(V)  | UC8251D   | 0~40                     | -25~40                   |                       |
| 2.9  | BWR   | 128*296    | 66.9(H)×29.06(V)    | 79.0(H)×36.7(V)   | JD79651B  | 0~40                     | -25~40                   |                       |
| 2.9  | BW    | 128*296    | 66.9(H)×29.06(V)    | 79.0(H)×36.7(V)   | UC8251D   | 0~40                     | -25~40                   |                       |
| 4.2  | BW    | 400*300    | 84.8 (H)×63.6 (V)   | 91.0 (H)×77.0(V   | UC8276    | 0~40                     | -25~40                   |                       |
| 4.2  | BWR   | 400*300    | 84.8 (H)×63.6 (V)   | 91.0 (H)×77.0(V   | UC8276    | 0~40                     | -25~40                   |                       |
| 5.83 | BWR   | 648*480    | 118.778(H)X88.22(V) | 125.4(H)×99.5 (V) | UC8179    | 0~40                     | -25~40                   |                       |
| 5.83 | BW    | 648*480    | 118.778(H)X88.22(V) | 125.4(H)×99.5 (V) | UC8179    | 0~40                     | -25~40                   |                       |
| 7.5  | BWR   | 800*480    | 163.2 (H)×97.92 (V) | 170.2(H)×111.2(V) | UC8179    | 0~40                     | -25~40                   |                       |
| 7.5  | BW    | 800*480    | 163.2 (H)×97.92 (V) | 170.2(H)×111.2(V) | UC8179    | 0~40                     | -25~40                   |

Please contact us by email for more model .Four Colors ePaper module mass production.
## Where to buy？ 
Email： 542165823@qq.com or xden@sina.cn



