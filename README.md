# Smart Incubator for Biological Processes

## Platform: Forge 

## Author: Omar Wael

## How it works:

The incubator regulates a highly controlled environment inside an isolated chamber using an integrated closed-loop cooling and heating cycle. You manage the system via a custom-wired breadboard and timer assembly. The thermodynamic cycle relies on a compressor pushing refrigerant through the condenser, passing through the filter, and entering the expansion valve and evaporator to absorb heat, while an internal fan forces air circulation to maintain perfectly uniform temperature distributions across your biological samples. 


pls read that part briefly because it is a huge step to understand the project and [ how it works ]


and that is the how i explanined it brifely in Forge

just to put you in view and explain how a refrigeration cycles works, you need to have 4 main components a compressor, evaporator, condenser and expansion valve, and no refrigeration cycle can work without those components and here is why. 




.............................





![image.png](https://cdn.hackclub.com/019efda9-8416-70f8-a13b-673a91098702/image.png)




we will start off with the Evaporator, most people start up with the compressor but that is a not wrong but bad move because that does not explain the step before it, and we will get into it, so the Evaporator is inside of the cell or the incubator, and it's function here is too remove excess energy from the inside of the cell, so how would it do that, depending on thermodynamics heat moves from high to lower regions, and inside of the evaporator there is a refrigerant that reaches temperatures below the Zero line [ in Celsius ] so temperature moves from the surroundings of the evaporator to inside of it, so it moves this energy and goes to our second destination, which is the compressor. 



...................................




![Screenshot 2026-06-25 101027.png](https://cdn.hackclub.com/019efdac-e105-71e8-90fd-91d8a5e80847/Screenshot%202026-06-25%20101027.png)




the refrigerant goes to the compressor in a pipe called the return line this return line is the place where the refrigerant gets sucked by the compressor and that line is often covered with thin ice that is because it sucks the already low temperature refrigerant from the evaporator to the compressor and that line is often covered with insulation because you don't want heat from the outside of the system to get inside of the system, but why do you want that ?, and that leads us to the function of the compressor, it's function is to extract those energy that has been carried from the inside of the cell by the evaporator, so how would it extract those energy it will be as following, the compressor will take the refrigerant and walk it through  narrow area and apply pressure to it so that the temperature of the refrigerant will increase [ making a temperature difference ] and as we have discussed earlier heat flows from high to low so the refrigerant is now higher in temperature than the surroundings, so the heat will exit the system to go outside and that leads us to our third destination, which is the condenser. 



.....................................




![image.png](https://cdn.hackclub.com/019efdcf-778a-7950-95b1-b8e2cf7b7dfa/image.png)




the refrigerant which is our hero, walks from the compressor and goes through a line called the push line or the forward line because the refrigerant gets pushed through it and that line is defined by high temperature as we have explained previously, the refrigerant now needs to lose that energy how would it lose it ?, by being applied to the surroundings to the most time it can be applied to, so the compressor is shaped in a way that makes the refrigerant go back and forth making it face the most surface area as possible, and often this outer thing is connected to a fan so a lot of air flows to it making it lose a lot of temperature and avoiding overheating, and after that the refrigerant loses a lot of it's energy and needs to flow back in the system so we need to sort it out, and get it cool again, and here comes our fourth destination, the expansion valve.



................................................






![image.png](https://cdn.hackclub.com/019efdd8-25f2-7729-94d8-61ab9d99f2f5/image.png)






and going to continue but let me breath a bit 


...........




the expansion valve is a tube like structure as shown in the diagram [ the big gulp beside it is a freon filter and that is not necessary beside it helps in longevity of the system or in the long-term ] the expansion valve applies a very good term in thermodynamics and to understand that we have to know ho temperature is made let's assume we have a box and inside of it their is three particles those particles, but wait i love number 7 more let's assume their is 7 particles, and they are moving by a slow speed, that makes them low in temperature and the possibility of them hitting each other is low, now let's make the box smaller without changing the number of particles that will make the particles collide even more reaching more speeds making getting higher in temperature, and our expansion valve works in that way it is a so tight narrow tube the refrigerant flows though it getting higher in temperature and higher in pressure and gets so much pressure that it changes it's state to liquid form [ btw we can't say it changes it's state because it does not have a will to do things on it's own but let's continue my English can't change how i explain that ] and after that the refrigerant gets to the moment of relief, which was our first destination, the evaporator, after getting out of the expansion valve, it goes into the big wide evaporator tubes which allow it to widen up and boil and evaporate [ calling it the evaporator ] and so that it changes into gas state making it perfect for carrying energy because gases have high intermolecular spaces inside of it, and so that completing the cycle and goes to make what we have said again and again and again.



## Why I made it: 

To perform genetic modification at home :| Most DIY setups lack the precise cooling capabilities needed for delicate biological processes, so I built a custom, heavy-duty refrigeration cycle right into the chassis to handle strict environmental regulation properly. 

## Features <3

* Closed-loop thermodynamic regulation system (compressor, condenser, filter, expansion valve, and evaporator cycle)
* High-efficiency thermal isolation chamber utilizing heavy-duty insulator panels
* Automated control hardware configured via an integrated breadboard and timer unit
* Forced-convection airflow system using an internal fan for completely uniform heat distribution

Made for Forge.




## Notes 

#in that section we would talk about the how to do it yourself, there is a lot of stuffs in that sector so focus, 

*the prototype was collected by buying parts from local shops ad was discussed in sections above and to make a refrigeration cycle you have to have some major parts, first ting would a compressor as it is the most expensive, but not main each part that we are going to discuss right now is a main part and without it the refrigeration is not fulfilled or done, and the compressors function was discussed in the How it works section, and then we go to the condenser the second part, and all of the parts functions was discussed in the how it works part btw, but a note to give while buying the condenser you would meet different types and materials ensure that you get the same material as it helps in welding a lot avoiding using metal flux cause it irritates a lot, and for me I did not notice that till late stage and had  to use flux and that was it try to find copper tubes as it is efficient and user friendly, going to the expansion valve sector you can use either parts to work a metering device [ which is often used in bigger projects and more powerful once as it works in a different mechanism from the expansion valve but they drop as the same category ] for me i used an expansion valve as it is cheaper and more practical for me as i have separated thermostats [ we are going to talk about them later], but for the expansion valve try while you are welding try to avoid putting much solder as the tube of the expansion valve is small and you can easily clog it stopping the whole system from functioning and putting yourself in more complex work and money consuming and oh another thing that we did not talk about which is the filter oil filter, as it is not mainly needed for the unit to function, but to ensure  longevity and long term work, and it is the same principle as the welding thing, you put the filter to avoid any tiny particles of oil from the Freon to accumulate in the expansion valve clogging it and stopping the cycle [ and btw that is a common issue that face self-made or DIY projects for refrigeration as they dont monitor the state of the tubes and carbon percentage in it ] after that we go to the evaporator not a hard step as it is a big tube relative to the valve we have but ensure taht you put it in a way inside the unit that has maximum air circulation by which the flux of air on it is as much as possible so that it functions greatly or awesomly or whatever word you want to call it and that evaporator goes back to the compressor in the backline or return line  that line needs to be isolated from the exterior environment and well sealed as you dont want your compressor to consume more energy and fail by overloading, so seal it good and that was it for the mechanical part. 

* for the electrical part i did not just get to work of course, i have sorted my schematics Infront of me and while wiring ensured every  device has certain colors to see and maintain if something happens in future, and that was my strategy and the devices that i have put are two fans and an compressor and a heater going to explain how each one was connected in an instance  starting of with the compressor the compressor is a unit that only works while the whole unit is trying to cool off something so it works in a system called the cooling system a cool name right ?  that cooling system is also connected to the other two fans which are the parts that are involved in the cooling system too as we have discussed in the how it works section and that cooling system was collected in a thermostat so it controls them as needed for the project and while doing so ensure you know where every single wire comes and goes to because that will irritate you a lot while working and for the other system i have done the same things but i put instead the heater which would work from the other thermostat and you can see all of that in schematic diagram listed downward, and every device function and need was explained in the how it works section and that's it till now.
---

## Screenshots

Initial Design Blueprint and Component Layout Sketch:

!<img width="4160" height="3120" alt="IMG_20260616_220047" src="https://github.com/user-attachments/assets/91c62fac-f265-4f3d-8d00-c67bab45789c" />


Hardware Assembly and Cycle Integration:

!<img width="960" height="1280" alt="photo_2026-06-25_06-56-48" src="https://github.com/user-attachments/assets/95c41366-675d-4e98-a54d-41d4f2c211ee" />


Schematic diagram:

<img width="753" height="472" alt="image" src="https://github.com/user-attachments/assets/533b4b30-94d1-4b08-a4d4-b66ca92c73d8" />



## Bill of Materials (Rough BOM)

| Component | Estimated Cost (USD) | Status / Notes |
| :--- | :--- | :--- |
| **Compressor** | $120.00 – $150.00 | Required for refrigeration cycle |
| **Condenser** | $70.00 – $100.00 | Heat dissipation |
| **Evaporator Coil** | $60.00 – $90.00 | Cooling element inside the chamber |
| **Thermostat** | $25.00 – $75.00 | Price varies based on programmable model |
| **Refrigerant Filter** | $15.00 – $30.00 | Inline cycle purification |
| **Expansion Valve** | $10.00 – $25.00 | Pressure regulation |
| **Fans (x2)** | $10.00 – $20.00 | Forced convection and airflow uniformity |
| **Heater** | $10.00 | Heating element for stabilization |
| **BH1750 Sensor** | $7.00 – $12.00 | Ambient light monitoring |
| **Lighting Element** | $10.00 | Type TBD |
| **DHT22 Sensor** | $0.00 | Already on hand |
| **ESP32 Microcontroller** | $0.00 | Already on hand |
| **Incubator Body** | $60 | Sourced from a local shop area |
| **Total Estimated Cost** | **$422.00 – $522.00** | **Project budget range** |

