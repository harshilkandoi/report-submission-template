#### 3. Mechanical 
##### Requirements
**Geographical requirements**

System can work under all geographical conditions.

**Basic Requirements**
1. An average fit person (in the age range of 18 years - 45 years) can generate 115W of electricity from pedalling a cycle connected with a dynamo which means we can generate around 460w power for a household with four adults and 230w power for a household with two adults, an elite cyclist can generate upto 300W.
2. Geared DC Motor should be brushless as brushes make the efficiency of motors down to less than 40%,  which is miserable.
    
3. To operate the speed controller, we have to use a servo tester. The servo tester offers a physical dial, dialing which we can increase the speed of rotation of the motor. 

##### Specifications

**Components**

(1)  *Bicycle*:Here, it is used to rotate the motor using mechanical power, thus producing electricity.

(2) *DC Motor*:It helps in converting the mechanical energy through pedals into rotatory motion (the pedals generate force in the form of torque applied on the motor's shaft) which is then converted into electrical energy.Here, we have to remove the brushes of the geared brushed DC Motor as instead of providing lots of torque, it is not fast enough.

(3) *Lithium Ion Cells*:It is used to power the DC motor controller.Due to the limited space we have to use a pair of high discharge lithium polymer battery packs. Two 11.1v and 5200 mAh batteries required with a peak discharge of 25C which means that these batteries can provide nearly 130 amp of continuous current draw

(4) *Sprocket*:A sprocket or chain wheel is a profiled wheel with teeth that mesh with a chain, track or other perforated or indented material. To drive the rear wheel we need somewhere around 16N-m of torque and so the required speed is 50km/hr. Our sensorless speed controller can handle 22.2v max, so we can get around 350 rpm. With this setup and gear ratio 1:1 we can have the sufficient torque.

(5) *Chain*:It is used to connect rear sprocket to the dc motor to rotate  the motor.

(6) *Buck-Boost converter*:The buck–boost converter is a type of DC-to-DC converter (also known as a chopper) that has an output voltage magnitude that is either greater than or less than the input voltage magnitude. It is used to “step up” the DC voltage.

**Power generation**

Our project has 4 stationary bicycles as we are assuming a household of 4 members.Each stationary cycle when pedaled by an average fit person can generate 115watts of electricity and up to 300 watts when driven by an elite cyclist.
Let us assume that each cycle is rode for 2 hours a day.
Energy generated by all 4 bicycles on an average=115watts* 2hours* 4cycles=920wh=0.92Kwh=0.92units.

**Cost Analysis**
Installation Cost for 1 bicycle
| Part  |  Cost |
| :--------:  | :---------: |
|  Bicycle | Rs5,000  |
| Brushless DC Motor  |  Rs6,000  |
|Buck Boost converter| Rs 3000 |
|Power inverter| Rs 5000|
| Other misc items like battery, chain, sprocket | ₹4,000 |
| **Total** | Rs23,000  |

<figcaption align = "center"><b>Table1 - Total Installation Cost </b></figcaption>  


So, cost for installing 4 bicycle generators: 23000*4=Rs 92,000
*Maintenance Cost* :Negligible maintenance cost

##### Diagrams and Working
- Here DC motor works as DC generator. It has a flywheel attached to it which increases its moment of inertia meaning even if you stop cycling for a moment, the generator will spin by itself for a couple of seconds.
- The output of the generator is connected to a buck-boost converter, whose output is then fed to a power inverter which is finally driving the load. This is done to regulate the generated voltage to get its full use.
- In this setup, the buck boost converter is driven by a 3-60 v dc always stepping up or down to the input voltage to an exact output voltage of 22.2v dc.
- This 22.2v is then fed to a power inverter which steps up and reshapes it to 230v 50Hz ac.
- After charging the batteries, the inverter is removed and the output of the buck boost converter is directly attached to the two 11.1v batteries connected in series.
- Below is the model for our bicycle electricity generator
![Side view](https://i.ibb.co/zRDYTMS/bike-side-view.png)

<figcaption align = "center"><b>Fig.1 - CAD Model Of Bicycle Electricity Generator </b></figcaption>

#### Vender's Info
|         Part          |  Link   |
| :-------------------: | :-----: |
| Sprocket | [Buy Link](https://www.alibaba.com/product-detail/Motorcycle-Chain-with-Sprocket_60449232001.html) |
|         Wires         |   [Buy Link](https://www.electronicscomp.com/electronic-components/small-electronic-components/wires-cables/silicone-wires/6-to-10-awg/high-quality-ultra-flexible-10awg-silicone-wire-1m-black-1m-red) |
|    Bicycle    |  [Buy Link](https://www.amazon.in/ACTINO-XENDER-Sports-Cycle-Suspension/dp/B09MFZNVTQ/ref=sr_1_3?keywords=bicycle&qid=1643693232&sr=8-3)   |
|  Buck-Boost Converter  |  [Buy Link](https://www.alibaba.com/product-detail/dc-to-dc-buck-boost-converter_62314759637.html?spm=a2700.galleryofferlist.normal_offer.d_title.16847ea0AlKV3x)  |
|  Brushless DC Motor  |  [Buy Link](https://www.alibaba.com/product-detail/Putian-Vibration-Motor-DC-Brushless-Miniature_62093981315.html?spm=a2700.galleryofferlist.normal_offer.d_title.42743b75ARHtO8&s=p)  |

##### References
1. ‘Bike powered electricity generators are not sustainable - LOW-TECH MAGAZINE’. https://www.lowtechmagazine.com/2011/05/bike-powered-electricity-generators.html (accessed Jan. 18, 2022).
2. D. King 00, ‘DIY Electric Bicycle Conversion (Using a Brushless Motor)’, Instructables. https://www.instructables.com/DIY-Electric-Bicycle-Conversion-Using-a-Brushless-/ (accessed Jan. 18, 2022).
3. R. Suhalka, M. C. Khandelwal, K. K. Sharma, and A. Sanghi, ‘Generation of Electrical Power using Bicycle Pedal’, . Flux, p. 5.
4. ‘Main Page’, Wikipedia, the free encyclopedia. Feb. 03, 2021. Accessed: Jan. 18, 2022. Available: https://en.wikipedia.org/w/index.php?title=Main_Page&oldid=1004593520
5. ‘Pedal Power! How to Build a Bike Generator’. https://www.popularmechanics.com/technology/gadgets/how-to/a10245/pedal-power-how-to-build-a-bike-generator-16627209/ (accessed Jan. 18, 2022).
6. 'Linear technology design manual'  
https://www.analog.com/media/en/technical-documentation/application-notes/an19fc.pdf
---
<div style = "page-break-after: always; visibility: hidden">
\pagebreak
</div>