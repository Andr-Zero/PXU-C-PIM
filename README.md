# PXU USB-C Power Input Module (PIM)
## _Power your OG Xbox via a USB Charger!_

This is based off the [SparkFun USB-C Power Delivery Board](https://github.com/sparkfun/Power_Delivery_Board-USB-C)

##### Disclaimer!
- I'm not an Electrical Engineer. Just wanted to make something cool and challenge myself.
- The OEM power supply can hold a potentially dangerous charge even after being unplugged for a large period of time!
- Your USB-C Cable MUST be capable of handling 100w! Lot out here that’s only 65w and most don’t have markings saying what their limits are. 
- You're on your own, I'm not responsible for injury or damages. 

##### TODO
- Photos
- Install instruction
- Upload Arduino code for programming
- Upload board and design files
- Explain header, programming, and LEDs
- Update License, assume same as Sparkfuns for now, attrubution specifically. 

##### FAQ
- What chargers work?  
  I dont have a definitive list. Any 100w charger *should* work. I tested with an Anker 100w I got off Amazon and have had no issues.
- Does it have to be a 100w charger?  
   At a minimum, YES! There's a lot of 65w chargers out there and they simply not enough to power a *stock* console.
- I'm plugging in my charger but nothing is working.  
   The charger has to be able to negotiate with the PIM saying it can do ~100w at 20v, otherwise the PIM refuses to pass power.
- My USB charger is warm when running the console, is that normal?  
   Depends on the charger, mine does and with anything I use it with. Apperently the GaN chargers run cooler? I've yet to verify myself.
- My USB-C Cable is hot or has melted down!  
   It wasn’t rated for 100w. MUST use a cable that’s rated for 100w.

##### Known Issues
-AC adapters that support PPS (Programgamable Power Supply) seems to have issues. 
