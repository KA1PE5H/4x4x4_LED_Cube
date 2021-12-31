# 4x4x4_LED_Cube
This repo consist of the arduino code made from scratch for the LED Cube with soldered LEDs of dimensions 4x4x4, connected to arduino board with 20 wires. 

Code Explaination:




First the virtual model was prepared in TinkerCAD, and after the succesful working of the arduino code in TinkerCAD model. You can check the TinkerCAD model [here](https://www.tinkercad.com/things/cTvofxKdty1-ka1pe5hledcubeproject/editel?sharecode=wYJQzJZ-9d_QAwHThTwb5Yn3JVQgLMFIXNzUKTJgpt8).

![KA1PE5H_LED_CUBE_PROJECT](https://user-images.githubusercontent.com/66291674/147839617-387285dd-7542-4c23-bf25-7d31af2afc73.png)

Once I was sure the model worked properly in TinkerCAD I proceded to make the actual model.
So, I ordered 100 LEDs (Though only 4x4x4 = 64 was needed), copper wires with silverplating, an arduino board, connecting wires.

The soldering was done in a way that for each level I would first connect the anodes of all the LEDs in the level, then I connected the catodes of each level vertically, making the wiring easier by soldering 16 wires to the base (all cathodes) and all the levels (with a 100 ohms resistor)(anode) soldered separately, making the total connection to be made to the arduino equal to 20, now out of these 20 connection 6 were connected to the analog pins and the remaining 14 to the digital pins of the arduino board.

![IMG_20211114_104409](https://user-images.githubusercontent.com/66291674/147839723-b336da80-d755-472f-a928-0740e211ccef.jpg)

![IMG_20211114_112408](https://user-images.githubusercontent.com/66291674/147839736-c91d7f68-8fe0-41bc-a6b2-4a1b83accdff.jpg)

![IMG_20211114_114239](https://user-images.githubusercontent.com/66291674/147839743-e627b816-0867-446d-b049-b5608c52a2ed.jpg)

![IMG_20211114_140444](https://user-images.githubusercontent.com/66291674/147839752-2605f21b-e9af-4498-8e3e-d4b0042bfec7.jpg)

![IMG_20211121_035934](https://user-images.githubusercontent.com/66291674/147839778-373222d7-8e3c-4178-a798-9d560b1702db.jpg)

![IMG_20211121_051605](https://user-images.githubusercontent.com/66291674/147839792-43014276-953a-459e-97a4-d81b37e0cc69.jpg)

![IMG_20211121_052144 (1)](https://user-images.githubusercontent.com/66291674/147839801-1504b341-88c1-4d57-9280-ff0952d61450.jpg)

After this I made a solid stand and protection around the delicate soldered copper wires and it luckily survived a few falls too :)

![1](https://user-images.githubusercontent.com/66291674/147839835-a6b7ad26-4af7-49aa-902f-5816b6fa6332.jpg)

![2](https://user-images.githubusercontent.com/66291674/147839859-7fcee6fe-1dca-4562-b0f4-21d8d325e149.jpg)

![3](https://user-images.githubusercontent.com/66291674/147839864-6a073639-dab9-4cf0-9470-c6950d2d9509.jpg)

Now I just had to upload the arduino code to the arduino board to get the beautiful patters/letters and since the LEDs were multicoloured so altering the voltage gave different colours making a magnificent LED cube for my desk decoration :)

https://user-images.githubusercontent.com/66291674/147839980-189b0df2-1e2a-47c6-88e5-4433a6587d18.mp4
