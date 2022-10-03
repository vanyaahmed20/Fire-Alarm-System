# Fire-Alarm-System
# Abstract
The use of fire Alarm System for Security has become a necessity in every office and in every work field. So, we thought of creating a fire alarms system but this time by using an IC. As we were learning about ICs in our Digital Logic Design lab so we thought why don’t we do a research about it. We searched that (can fire alarms systems be made using an IC?) and we started working on it.
In our project we have used a 10K thermistor(NTC). This is the main component of our project and its purpose is that when the temperature increases/rises the resistance of this thermistor decreases (the working of NTC thermistor). We have used a potentiometer of 10Kohm and it purpose is to divide the voltage output. When the temperature increases its (thermistor) resistance decreases the output of the voltage divider (POT) will increase and its output will be given to LM358s (IC) non-inverting input (pin 2). As the LM358 is a dual operational amplifier it would operate in a comparator mode in this project. The input signals will be applied to the inverting terminals and on the other hand non-inverting terminals will be compared to produce output. The output of non-inverting terminals will be high. So the operational amplifier will become high and the buzzer will make a sound. In our simulation we have attached an LED too so that we would know that when the buzzer will make a sound the LED would turn on and vice versa.
# Over view
Our project is about detecting a fire as mentioned in the Name Fire Alarm system. We have used a 10k NTC thermistor which is the main component of our system. A 4.7Kohm resistor. A Potentiometer of 10Kohm which will act as a voltage divider. A LM358 which is dual operational amplifier and its input signals will be applied to inverting terminals whereas the non-inverting terminals will be compared to generate an output. The output of Potentiometer is connected with the non-inverting inputs of the IC LM358. From (pin number 2). Pin 3 is used to divide the resistor and thermistor, pin 8 as VCC and pin 4 as GROUND. Pin 1 is used as an output which is connected to the one input to the buzzer the other input of the buzzer is connected to GROUND. And according to the rise in temperature the buzzer will make a sound e.g. in case of smoke and fire it would detect it and make a sound.
# INPUT:
                            In input we can say that an input can be the temperature. E.G. (26C), (77C) and 
                            (10C).
 # PROCESS:
                            Whenever the temperature will increase for e.g (77C) the resistance of the
                            thermistor would decrease. The decrease in thermistor would automatically 
                            increase the output of the potential divider. As the output of the potential divider    
                            is connected with the non-inverting terminal of the operational amplifier. Its  
                            value will become more than the inverting inputs. So as a result the output of 
                            operational amplifier or LM358 will become high and as a result it would  
                            generate the buzzer to make a sound.
# OUTPUT:
                             According to the value of temperature our output will be generated depending 
                             upon the output of the potential divider. If the temperature will be high the 
                             output of POT will be increased resulting in the Buzzer to be activated when 
                             compared by the non-inverting terminals of the IC (if its value will be more than  
                             the inverting inputs). if the temperature would decrease the output of POT  
                             will decrease too resulting in the buzzer not to be activated when compared by 
                             the non-inverting terminals of the IC (if its value will be less than the inverting           
                             inputs).  
# 	Block Diagram of Complete System (without using ICs, just use simple blocks)
![image](https://user-images.githubusercontent.com/92653096/193651763-ea580b78-8699-435e-9b22-f4a422162a62.png)
# 2.1	Problem Statement
there are many cases in which a fire alarm system needs to be installed.so we have designed a fire alarm system which must be able to detect fires at all locations so that in case of any fire emergency it should activate and alert the owners of the house or a specific building, that a fire has been broke out. this system would reduce the cost of fire-insurance protection and would provide safety for the homeowners.

# 2.2	Truth Table / State Diagram
# TABLE RELATED TO CALCULATIONS:
![image](https://user-images.githubusercontent.com/92653096/193652251-ce9c4aab-07d2-4f9d-be3f-b03edb2d3e03.png)
# Complete Logic Diagram
![image](https://user-images.githubusercontent.com/92653096/193652295-e476e85b-db31-4a50-acfc-1bb769df3330.png)
#  Simulation 
•	if temperature is normal e.g (26C) room temperature the buzzer will not make a sound we have connected a LED so that when LED will light up it means the buzzer has made a sound.
![image](https://user-images.githubusercontent.com/92653096/193652391-659ef25c-3314-463b-ac96-59aa39c3a04d.png)
# After result
![image](https://user-images.githubusercontent.com/92653096/193652439-a2f2e53e-8a9f-48c0-9c54-59217c9b4d4d.png)
# Temperature set to (55C) the resistivity will be decreased as temperature will decrease.
![image](https://user-images.githubusercontent.com/92653096/193652498-8b35d48b-7edf-48f4-9491-b9a715eed531.png)
# •	Result: buzzer will make a sound.
![image](https://user-images.githubusercontent.com/92653096/193652625-f6fa3b5c-7f2f-4967-b4ce-dd49a2ed06cd.png)
# •	Result: the buzzer will not make a sound.
![image](https://user-images.githubusercontent.com/92653096/193652690-1a8f93e8-37a7-4178-bab7-191267a16fad.png)
# Schematic
![image](https://user-images.githubusercontent.com/92653096/193652810-f77722a7-3beb-4525-9322-5bc7b7f44215.png)
# Project Applications

#	OFFICES:
As in an office you have to fully work on a computer. In some cases, a wire can get loose or in other hand your switch board/ plug may be overloaded. So in both the cases fire may broke out and will cause destruction. so in that case a fire alarm detector must be installed so that all the members of that office would know a fire has been broke out so that their life may be saved.

#	 RESTAURANTS:
Most of the reason for the cause of fire in restaurants are the faulty plugging of AC and other ventilations. They are 9% responsible for the cause of fires. The other reasons include those customers who smoke cigarettes or any other thing similar to cigarette. These results might cause fire in a restaurant so, a fire alarm system must be installed for the security of people.

#	MOVIE THEATER:
As it also depends upon heavily electrical equipment’s so, a malfunction in a projection might cause a spark and if something like paper or any other thing that can cause fire is nearby. It may catch fire and cause harm. So that is why a fire alarm detector must be installed for the security of people.





# Future recomendation
•	Now days fire security alarms/system usage has been spreading rapidly around the world. Before it was not considered important but, today people around the world consider it as an essential source for their safety of life. As the technology is advancing so its sources too. If we talk about fire alarms the fire alarms of the future should have the capability of providing better information to fire departments and other occupants. With these developing technology fire alarm combining with other equipment’s like, mass notification and security will help to reduce cost and would also help for better life safety for people through technology.
•	These alarms will help to change the style/nature of the buildings as they will integrate with the building automation system which will provide protection for the urban buildings so that it may be suitable for both the residential and commercial buildings.
