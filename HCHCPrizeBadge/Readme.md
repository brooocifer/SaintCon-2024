Parts - ***NOTE - The Order URLs provided were the best prices I could find at the time that I ordered. Prices change often, so you may want to do some research to ensure the lowest cost to you. The price in the table below is the quantity for only one badge, prices may be lower if ordering in bulk. Prices do not include shipping fees.***

| Qty | Part | Order URL | Price | Notes |
| --- | ---- | --------- | ----- | ----- |
| 1 | PCB | [jlcpcb.com](https://jlcpcb.com) | $0.30 | Use files in the ***Gerber*** directory |
| 8 | Male header pins | [digikey.com](https://www.digikey.com/en/products/detail/adam-tech/PH1-08-UA/9830442) | $1.28 | - |
| 3 | Female header sockets | [digikey.com](https://www.digikey.com/en/products/detail/samtec-inc/SSW-101-01-T-S/1112304) | $1.23 | - |
| 1 | Badge-side SAO socket | [digikey.com](https://www.digikey.com/en/products/detail/adam-tech/BHR-06-VUA/10414837) | $0.26 | - |
| 1 | SO-45 3v DC panel voltmeter | [aliexpress.us](https://www.aliexpress.us/item/3256806004338224.html) | $2.91 | Includes 2x nuts, 2x lock-washers, 4x flat washers |
| 1 | Pulse Sensor | [electropeak.com](https://electropeak.com/pulsesensor) | $1.75 | Includes 3x Male to Female header wires. There is more info at [pulsesensor.com](https://pulsesensor.com) on how to use the pulse sensor without the minibadge, such as with an Arduino. Also note that buying from the source is very expensive, $24.99 each.
| 1 | ~~3d printed PLA sensor case~~ | [printables.com](https://www.printables.com/model/308807-3d-printed-pulse-sensor-case) | Free | We found that the finger sensor case took a lot of effort to cut out the 3D printed supports, and wasn't very effective. I'm personally just ***throwing mine away***. It was much more effective to tuck the pulse sensor into the Saintcon Badge wristband and measure your pulse there. |

Total Parts Cost (not including taxes and shipping): $7.73

Build Instructions
1. Solder SAO socket to back of PCB, lining up socket notch with silkscreen line & gap
2. Solder Male header pins to back of PCB
3. Solder Female header sockets to front of PCB
4. Bolt SO-45 to front of PCB. One flat washer per meter bolt on front of PCB, one flat washer, lock washer, and nut per meter bolt on back of PCB
5. Snap pulse sensor into sensor case (***unless you're throwing it away, like I am!***)
6. Connect pulse sensor to badge with header wires, Sig -> S, P+ -> +, P- -> -
7. Plug badge into SaintCon badge, mini-badge extender, 10x10, (via lower right pins) or DefCon badge (via SAO) to power up
