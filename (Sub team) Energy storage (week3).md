### Energy Storage And Distribution

<font size = "2">

|Name	            |Entry	       |Role                     |email           |Participation |
|--------------  |-----------|-----------------|------------|--------------|
|			S K Vignesh			  |2019EE10513                  |Sub-coordinator| ee1190513@iitd.ac.in                   |  1   				  |
|	Vishal Meena					  |   2019MT10735               |Member               |  mt1190735@iitd.ac.in                  |  1    				  |
|		Pradim Siwa			      |      2019MT10712            |Member               |   mt1190712@iitd.ac.in             |  1					  | 
|                 Harisam Sharma        |  			2019EE30570	 |Member               |        ee3190570@iitd.ac.in      | 	1				  |
|                     Vaibhav Soni    |				 2019EE10542	 |Member               |   ee1190542@iitd.ac.in           |  	1				  
|		Dasaradhi Lokesh				  |  2019MT60751                 |Member               |          mt6190751@iitd.ac.in           |  1    				  |
|			Deepankar Tiwari			  |          2018EE30536        |Member               |       ee3180536@iitd.ac.in            |      1				  |
|				Prashant Verma		  |           2018EE30556       |Member               |            ee3180556@iitd.ac.in       |    1  				  |
|					Abhishek Palway	  |           2019EE10459       |Member               |           ee1190459@iitd.ac.in        |    1  				  |
|				Lakshika Rathi		  |       2019EE10491           |Member               |   ee1190491@iitd.ac.in                |      		1		  |

</font>

##### Requirements


**House Requirements**
1. **Ventilation and Temperature:** A shaded, dry place with reasonably free airflow. Operational temperature range 10$C^\circ$ to 40$C^\circ$ , Ideal temperature range of 25-35$C^\circ$
2. **Space and Area:**

|Tier |Volume (in litres) |Area (cm$\times$cm)|
|--|--|--|
|*Plus* |480  | 80 $\times$ 50|
|*Base*|513|77 $\times$ 60|
|*Economy*|162|54 $\times$ 40|

##### Specifications
### Charger Specifications
  **Chargers** --- *per source*
The chargers used are of the MPPT (Maximum power point tracking) type are preferred , which allows for networking and better efficiency compared to PWM type.
	  
	 
| **Source** | **Specification** |**Cost** (INR) |
|--|--|--|
| **Solar**-*Plus*| 24V/48V 60A *Sparkel* MPPT charge controller | 16500 |
| **Solar**-*Base*| 24V/48V 50A *Smarten* MPPT charge controller | 11440 |
| **Solar**-*lite*| 12V/24V 30A *Sparkel* PWM Digital Solar Charge Controller | 1100 |
| *Wind* |24V 500W *ato* wind turbine MPPT controller  | 8200 (99.82USD) 
|*combustion*  |*not required*(direct(ac-dc) inverter connection)  |-
| *Hydro* |12V/24V *Ethan* 30A MPPT charge controllers  |5000
|*Mechanical*|12/24V *sunzter Trak* 10A MPPT controller| 1800

The sources Mentioned above are the major Power sources and other power sources are too little in comparison to be added to the system for it to be cost effective.

- --
### Battery-Inverter Specifications

##### *Plus* tier
 **Components** 

 - **Batteries**  --- *heart of the energy storage system*
	 - $LiFePO_4$ based batteries are used as they are a perfect combination of Energy density, Life Span, Weight and Safety. Even though, there are more cheaper alternatives (Lead-Acid Batteries) but the advantages are worth the extra cost.
	 - The Number of batteries used is the minimum number required, but the number can be increased based on requirement and backup time required

 |                     |             |
  | :-----------------: | :---------: |
  |       Manufacturer       |   Grenergy     |
  | Combination  |  8S5P : 3.2V : 20AH : $LiFePO_4$ Cells  |
  |     Dimension ( h$\times$b$\times$d ) |  52.5 $\times$ 24.0 $\times$ 21.8 cm     |
  |   Nominal Voltage (Charge - Discharge)  | 24V  ( 29.2V - 20V )|
  |       Max Working Current        |    100 A    |
  |       Nominal capacity       |    100Ah    |
  |       Operating Temperature      |  0$^\circ$C to 50$^\circ$C    |
  |     *Cost* per piece| USD 550 (INR 43000 incl. customs)  |
  **No. of Units :-** 5  (Connected in parallel)
  **Cost :-** 2,15,000 INR ( 2,887.5 USD)


 - **Inverter** (with charger)  -- *DC to AC converter*
	 - The invertor is used to convert the DC power from the various chargers and the battery system to AC power for domestic consumption. 
	 - It also allows for AC power Sources such as the Biogas' generator to charge the battery. In a complete power failure situation, It also allows for Connection to the electrical grid or to a fuel based generator. 

|                     |             |
  | :-----------------: | :---------: |
  |       Manufacturer       |   Luminous     |
  | Name  |  Cruze+, 4KVA  |
  |Battery Volatge|48V|
  |VA rating |4VA|
  |Weight |31.9Kg|
  |Size|28$\times$ 30.5 $\times$ 38 cm|
  **Cost :-** 22500 INR
**Power And Energy**

 - **11 KWh** amount of *Energy can be stored* (roughly energy required for one days use)
 - *Peak Power consumption* (without biogas generator) is **3360Watts**
 - *Expected monthly Power generation* is  **450 units** 

**Costs**

 - *Initial Setup Cost:-*  **2,80,000 INR** (including Wiring and labour )
 - *Maintenance And Running cost:-* virtually none
 - *lifespan:-* *10 Years for the battery* and 1*5 years for the rest of the system*



##### *Base* tier
 **Components** 

 - **Batteries**  --- *heart of the energy storage system*
	 - *Lead-Acid* based batteries are used here to for their superior capacity at any given cost.
	 - The Number of batteries used is the optimum number for running. Number of batteries can also be reduced to 4, if there is a budget constraint.

 |                     |             |
  | :-----------------: | :---------: |
  |       Manufacturer       |   LUMINOUS     |
  |     Dimension ( h$\times$b$\times$d ) |  50.2 $\times$ 19.1 $\times$ 44 cm     |
   |       Nominal capacity       |    100Ah    |
  |   Nominal Voltage (Charge - Discharge)  | 12V  ( 12.7V - 10.8V )|
  |Weight|52Kg|
  |     *Cost* per piece| 11000 INR  |
  |Country of Origin | India|
  **No. of Units :-** 6  (Connected in 2S3P configuration)
  **Cost :-** 66,000 INR 

 - **Inverter** (with charger)  -- *DC to AC converter*
	 - The invertor is used to convert the DC power from the various chargers and the battery system to AC power for domestic consumption. 
	 - It also allows for AC power Sources such as the Biogas' generator to charge the battery. In a complete power failure situation, It also allows for Connection to the electrical grid or to a fuel based generator. 

|                     |             |
  | :-----------------: | :---------: |
  |       Manufacturer       |   Exide     |
  | Name  |  STAR 1050VA  |
  |Battery Volatge|24V|
  |VA rating |1.015VA|
  |Weight |11.9Kg|
  |Dimensions|35 $\times$ 30 $\times$ 25|
  **Cost :-** 5500 INR
**Power And Energy**

 - **10.2 KWh** amount of *Energy can be stored* (roughly energy required for one days use)
 - *Peak Power consumption* (without biogas generator) is **900Watts**
 
**Costs**

 - *Initial Setup Cost:-*  **75000 INR** (including Wiring and labour ) for only battery system
 - *Maintenance And Running cost:-* 4000 INR per annum
 - *lifespan:-* *3 Years for the battery* and *10 years for the rest of the system*




#### *Economy* tier
 **Components** 

 - **Batteries**  --- *heart of the energy storage system*
	 - *Lead-Acid* based batteries are used here to for their superior capacity at any given cost.
	 
 |                     |             |
  | :-----------------: | :---------: |
  |       Manufacturer       |   AMARON    |
  |     Dimension ( h$\times$b$\times$d ) |  50.2 $\times$ 19.1 $\times$ 44 cm     |
   |       Nominal capacity       |    165Ah    |
  |   Nominal Voltage (Charge - Discharge)  | 12V  ( 12.7V - 10.8V )|
  |Weight|59Kg|
  |     *Cost* per piece| 12000 INR  |
  |Country of Origin | India|
  **No. of Units :-** 1  
  **Cost :-** 12,000 INR 




 - **Inverter** (with charger)  -- *DC to AC converter*
	 - The invertor is used to convert the DC power from the various chargers and the battery system to AC power for domestic consumption. 
	 - It also allows for AC power Sources such as the Biogas' generator to charge the battery. In a complete power failure situation, It also allows for Connection to the electrical grid or to a fuel based generator. 
	 - Due to unavailability of Proper inverters for the required capacity, we need to either design such a system for less than 2000 INR or use an Inverter cum solar charger.
	 - The specifications are for the combined solar charger with inverter

|                     |             |
  | :-----------------: | :---------: |
  |       Manufacturer       |   Solar Universe     |
  |Battery Volatge|12V|
  |VA rating |300VA|
  |Weight |3 Kg|
  |Max Bulb Power|240W|
  **Cost :-** 2700 INR
 **Power And Energy**

 - **1.98 KWh** amount of *Energy can be stored* (roughly energy required for one days use)
 - *Peak Power consumption* (without biogas generator) is **240Watts**
 
 **Costs**

 - *Initial Setup Cost:-*  **16000 INR** (including Wiring and labour ) for only battery system
 - *Maintenance And Running cost:-* 700 INR per annum
 - *lifespan:-* *3 Years for the battery* and *10 years for the rest of the system*

##### Diagrams and Working
Unlike living offgrid , offgrid and independent electrical systems are more complicated than normal electrical wiring and must contain the functionalities similar to a national grid like load balancing and maintaining a fairly constant frequency and voltage. The energy Storage and management system essentially does the following functions -
1.  Fills the gap between electricity generation and usage
2.  Combines multiple sources into one coherent output
3.  Tries to address the unreliability of renewable sources by providing backup power during disruptions
Solar photovoltaic power, being the most contributing in terms of energy production, has influenced the design of the battery system to be *DC coupled*, inspite of AC coupling being more easy to set up.

The following diagram gives us a brief description of the system.

![enter image description here](https://i.ibb.co/nbvfFqb/week3jpg.jpg)
The system has been designed to be modular, allowing for: *easy installation, flexibility and user customization*  . Every energy source is paired with its own charge controller which is synchronized with other charge controllers for balanced charging. The chargers are then connected in parallel to both the battery and the inverter allowing for direct pass through of energy. The Inverter is then chosen in accordance with the overall expected system power usage.

The setup is same across all tiers with the main difference between each tier is in the capacity of power and storage.
##### References

1. Martin Johnson - Off Grid Living, _EASIEST Off Grid Solar Power System Battery Bank_, (Oct. 10, 2020). Accessed: Jan. 19, 2022. [Online]. Available: [https://www.youtube.com/watch?v=lGs0VPKM1jU](https://www.youtube.com/watch?v=lGs0VPKM1jU)
 2. D. A. Mse and L. P. Mse, _The Ultimate Solar Power Design Guide: Less Theory More Practice_. Digital Publishing Limited, 2015.

 4. D. A. Mse and L. P. Mse, _The Truth About Solar Panels: The Book That Solar Manufacturers, Vendors, Installers And DIY Scammers Don’t Want You To Read_. Digital Publishing Limited, 2015.
 5. O. E. Olabode, T. O. Ajewole, I. K. Okakwu, A. S. Alayande, and D. O. Akinyele, “Hybrid power systems for off-grid locations: A comprehensive review of design technologies, applications and future trends,” _Scientific African_, vol. 13, p. e00884, Sep. 2021, doi: [10.1016/j.sciaf.2021.e00884](https://doi.org/10.1016/j.sciaf.2021.e00884).
 6. “Solar Charge Controller Types, Working Functionality and Applications,” _ElProCus - Electronic Projects for Engineering Students_, Nov. 06, 2013. [https://www.elprocus.com/solar-charge-controller/](https://www.elprocus.com/solar-charge-controller/) (accessed Jan. 19, 2022).
 7. “MULTIPLE INPUT CHARGE CONTROLLER FOR RENEWABLE ENERGY,” _Microcontrollers Lab_, Oct. 19, 2015. [https://microcontrollerslab.com/multiple-input-charge-controller-renewable-energy-sources/](https://microcontrollerslab.com/multiple-input-charge-controller-renewable-energy-sources/) (accessed Jan. 19, 2022).
6. "Mixing solar panels – Dos and Don’ts • SOLAR POWER SECRETS.” [https://solarpanelsvenue.com/mixing-solar-panels/](https://solarpanelsvenue.com/mixing-solar-panels/) (accessed Jan. 19, 2022).
7. “Solar Charge Controller Sizing and How to Choose One,” _Renogy United States_. [https://www.renogy.com/blog/solar-charge-controller-sizing-and-how-to-choose-one-/](https://www.renogy.com/blog/solar-charge-controller-sizing-and-how-to-choose-one-/) (accessed Jan. 19, 2022).
8. “What Cables Do I Need For My Power Inverter?,” _Wagan Corporation_. [https://wagan.com/blogs/news/customer-question-what-cables-do-i-need-for-my-power-inverter](https://wagan.com/blogs/news/customer-question-what-cables-do-i-need-for-my-power-inverter) (accessed Jan. 19, 2022).

##### Appendix : Product links And Product Detail/Specifications
***Chargers***

 1. https://www.amazon.in/Sparkel-Smart-Charge-Controller-SPSCC-6048LiMPPT/dp/B094CS2P7V/ref=sr_1_3?crid=LYRI2T533096&keywords=MPPT+60A&qid=1642532993&sprefix=mppt+60a%2Caps%2C259&sr=8-3
 2.  [https://www.amazon.in/Controller-Regulator-Temperature-Indicator-SPSCC-230/dp/B07HT99ZMZ](https://www.amazon.in/Controller-Regulator-Temperature-Indicator-SPSCC-230/dp/B07HT99ZMZ)
 3. https://www.flipkart.com/smarten-24v-48v-50amp-automatic-mppt-solar-charge-controller/p/itmb5fa89d794f58
4. https://www.indiamart.com/proddetail/12v-24v-30-amp-mppt-solar-charge-controller-21874100730.html
 5. https://www.ato.com/500w-wind-turbine-mppt-charge-controller
 6. https://www.indiamart.com/proddetail/trak-12-24v-10a-mppt-charge-controller-21423732073.html

***Plus*  Tier**
 1. https://www.globalsources.com/LiFePO4-battery/24V-Deep-cycle-battery-100AH-LiFePO4-battery-1177169646p.htm
 2. https://www.amazon.in/Luminous-Cruze-4KVA-Tecknology-Capacity/dp/B07DYQQCV8/ref=asc_df_B07DYQQCV8/?tag=googleshopdes-21&linkCode=df0&hvadid=396988844319&hvpos=&hvnetw=g&hvrand=867541717046943090&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9040178&hvtargid=pla-813895011528&psc=1&ext_vrnc=hi

***Base* Tier**

 1.  https://www.luminousindia.com/rc-18000.html
 2. https://www.powerwale.com/store/exide-inverterz-star-12v-1050va/77569

***Economy* Tier**
1. https://www.moglix.com/solar-universe-india-240w-300va-off-grid-solar-inverter-sui-300va-12v-inverter/mp/msn75dqrwmyv92?s_kwcid=AL!10177!3!455163737679
2. https://www.batteryboss.in/battery/amaron-current-short-tubular-ar165st36-165ah?gclid=CjwKCAiA866PBhAYEiwANkIneBXM18Txykd1zZI6e8ariXiibsEJGPcKpdkfLRhUIXP1jYE3u4_pQRoCE90QAvD_BwE


---



