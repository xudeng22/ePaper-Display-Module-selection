
<!-- _coverpage.md -->

# <font color=#1C86EE>Main Page</font>
***
# **关于我们**
idisplaymodule.com专注于各种显示模块的开发，最大程度的减少客户产品开发周期，助力客户产品最快的推向市场，目前我们主要产品包括，电子纸模组，OLED模组，TFT串口屏。安卓显示模组。  
技术支持邮箱: xden@sina.cn

# **开始**
**电子纸模组**  
**OLED模组**  
**TFT串口屏**  
TFT串口屏系列是以当前显示行业的前端技术“组态技术”为基础开发的串口彩屏产品，用户只需要通过一个串口，就可以用RS485、RS232或者是更简单的51单片机UART接口轻松实现文本、图片、音视频、曲线、二维码、仪表、动画、进度条、数据记录和触摸等等功能的控制与数据传输，而不需要像老式的显示屏一样需要大量占用控制器的接口和储存空间等资源，同时也提高了产品的抗干扰能力。  
**安卓显示模组**

# **电子纸(电子墨水屏)模组**

## 电子纸构成元素
----------------------------------------------------------------------------------------------------------------
将电子墨水涂布在一层塑料薄膜上，再贴覆上薄膜晶体管(TFT)电路，经由驱动IC控制，形成像素图形，创造了电子纸显示屏(Electronic Paper Displays, EPD)，也常被习称为墨水屏、水墨屏等，具体而微地形容了这是一块用墨水、也像墨水制造出的屏幕。

### 双色电子墨水原理 <!-- {docsify-ignore} -->
每个微胶囊里含有电泳粒子──带负电荷的白色以及带正电荷的黑色粒子，悬浮于透明液体中。利用正负相吸的原理，当电场接通时，该区块对应的黑或白粒子会移动至微胶囊的顶端，使用者在该区块上，就能看见白色或黑色。

![](双色电子墨水原理.gif)
### 三色电子墨水原理 <!-- {docsify-ignore} -->

三色电子墨水系统运作原理与双色系统类似，施加不同的电压，使不同颜色的粒子移动至上层，看见不同的颜色。三色系统在微杯技术(Microcup®  Eink专利)架构下开发而成。
![](三色电子墨水原理.gif)
## 电子纸特点

### 双稳态(Bi-Stability) <!-- {docsify-ignore} -->

在电源完全移除或断电的状态下，画面仍可持续显示在屏幕上，不会消失。
E Ink的电子纸技术通常被称为「双稳态」(Bi-stable)技术。所谓的双稳态，就是即使移除供电来源，电子纸显示屏上的画面仍然能持续显示，不会消失。仅在更换画面时，才需要消耗电量。
实际应用上，使用电子纸屏幕的电子书在翻页时，才需要消耗电量，在阅读期间则不会消耗任何电量。这正是使用了电子纸作为显示器屏幕，具备长时间待机的原因。
在大型电子看板的应用上，画面不变换的时候，也是完全不需要消耗电量的，长期下来，与相同尺寸的LCD显示屏看板相比之下，拥有非常优异的节电性能。

### 反射式技术(Reflective) <!-- {docsify-ignore} -->  
不自发光、没有背光模组
电子纸显示屏也常被称为「反射式显示屏」，完全不需要背光源，是利用环境光源打在电子纸显示屏幕上，再折射光线至观看者的眼中，与传统纸张、或生活中物体的可视原理无异，所以环境光源越亮，电子纸也越清晰可见。
而LCD或OLED等显示屏幕，需有背光模组或自发光，才能看到影像。但背光源或自发光的光线会穿透显示屏幕，直射观看者的眼睛，容易导致视觉疲劳、蓝光引起的黄斑部病变等问题。
不需要背光模组的电子纸显示屏，非常适合长时间阅读，另外，没有背光模组也可节约电力，大幅提升待机时间。

### 可耐久性 <!-- {docsify-ignore} -->
基于塑料基板的电子墨水薄膜，实现耐用、耐久的显示屏
墨水薄膜本身是柔性的，电子墨水薄膜贴覆至TFT基板上，构成了电子纸显示屏。依据不同的应用需求，产品开发设计人员可能使用一般的玻璃基板，或柔性的塑料基板，使用了柔性基板的电子纸显示屏也就是E Ink Mobius柔性电子纸显示屏。

一片13.3寸塑料基板的柔性电子纸显示屏模组，约等同于15张A4纸张的重量、7张A4纸的厚度。这样的柔性显示屏模组，能让终端产品更轻薄，采用13.3寸柔性电子纸的终端产品，仅重349克(12.3盎司)；而使用12.9寸LCD显示屏的产品，却重达713克(25.2盎司)。

此外，塑料基板比易碎的玻璃基板显示屏来得更为耐久、不易碎裂，终端产品掉落或遭受撞击时，可减少产品的损坏概率。

电子纸与其他显示屏技术最大的不同在于，电子纸是反射式、双稳态的显示技术，所以视觉上看起来与传统纸张几乎没有分别，因此能创造护眼、节能的效益。
![](电子纸特性.jpg)

## 电子纸选型参考  

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

目前四色电子纸（黑白黄红）已量产，要更多型号规格请发送邮件给我们。

# **OLED模组**

## 什么是OLED？
有机发光二极体显示面板（Organic Light-Emitting Diode,OLED），又称为有机电激发光显示器 （Organic Electroluminescence,OEL） ，拥有其他平面显示器技术不易达到之新一代技术─更明亮且清晰的全彩影像与更敏捷的反应速度。   

OLED的基本结构是由一薄而透明半导体性质的铟锡氧化物(ITO)为正极与金属阴极如同三明治般将有机材料层包夹其中，有机材料层包括电洞传输层(HTL)、发光层(EL)、与电子传输层(ETL)。当电池提供适当的电压(低伏特数的特性)，注入正极的电洞与阴极来的电荷在发光层结合时，即可激发有机材料产生光亮(electroluminescence)，有机层的架构与正负极的选择设计是让OLED装置充分发挥发光功效的关键。
 
## OLED特性
	自发光，不需背光源（Backlight）模组及彩色滤光片（Color Filter）
	重量轻，厚度薄（<2mm）
	构造简单，耐用性高，低成本
	低驱动电压（3 ~ 9V）省电佳
	无视角限制
	高亮度
	辉度佳（16LM/W）
	对比高（>10000:1）
	暗视与亮视画质皆优良
	反应速度快（10μs）
	可全彩化
	可大尺寸化
	可桡性(采用塑胶底材)
	使用温度范围广:-40℃～85℃
立即采用OLED显示器，全面提升您的产品价值！
## OLED模组选型
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

要更多型号规格请发送邮件给我们。
# **哪里购买？**

@需要样品及报价可邮箱联系 542165823@qq.com




