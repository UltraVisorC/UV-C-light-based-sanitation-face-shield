# UV-C-light-based-air-sanitation-face-shield

## The Central Problem 
The current pandemic poses a serious threat to people in high-risk environments, especially doctors and nurses. While there are many protective measures, they are not 100% effective. Our team is tasked with designing a prototype modeled after the UVisor, an existing prototype and face shield that is 99% effective against viruses. The current UVisor is a 2.5 lb faceshield that utilizes UV-C technology to sanitize inhaled air particles and has a battery life of 4-8 hours. Although the UVisor is able to successfully sanitize incoming air, one missing component is its inability to sanitize outgoing air. This poses a safety concern for medical professionals who wish not to infect patients and other staff by viral transmission from exhaled air. 

## Problem Statement
The UltraVisor-C’s central goal is to improve the UVisor by sanitizing exhaled air while maintaining the same weight, sanitation efficacy, and durability. Additional targets include improving battery life, comfort, audibility, and ease of use.

## Modifying the UVisor 
The current UVisor has two fans that blow air downwards in front of the user's face. These fans direct air through the UV-C chamber where the air is sanitized by the UV-lamps. However, this airflow mechanism directes exhaled air downwards and through a hole at the bottom of the device, which is why exhaled air is not cleaned. 

One main modification that we made to the original UVisor to address this issue was separating the UV-C chamber to distinguish inhaled and exhaled air. To do this, we  modified the original CAD file to create a wall in the middle. Another modification we made to the original Visor design was reversing one fan. The components are assembled such that most of the air is sealed inside the product with the built-in airflow mechanism. As shown in the image below, the green arrows represent the direction of the air flowing inside the UVisor. The air is pulled in through the inhale chamber with a fan blowing the air into the visor. After a complete circulation of air within the device, the exhaled air will be directed outwards into the exhale UV-C chamber with the other reversed fan. In our prototype, we used LED lights to model UV-C light. The last main modification we made was creating a sealed bottom. Our device uses foam lining and stretchy cloth to make sure minimal exhaled air is escaping from the sides. The stretchy cloth is velcroed to the bottom so it can be easily detached for cleaning. Some additional components we added to the device include a battery compartment that sits on top of the head and a detachable visor. 

<img width="593" alt="Screen Shot 2022-05-02 at 10 51 30 PM" src="https://user-images.githubusercontent.com/48959871/166402635-e789592c-06b4-4e9c-8194-369c797c4b84.png">

## The Final Prototype
The UltraVisor-C is a face shield. Figure 1 shows the final prototype of our device. The overall product has dimensions of 200mm x 170mm x 290mm, and weight of 916g. The battery holder is situated on top of the sanitation chamber, which is situated on top of the head. The chamber is divided into 2 compartments (one for inhaled air and the other for exhaled), both containing LED strips that act as a substitute for UV-C. Two fans turning in opposite directions direct air between the chamber and the visor. A detachable vinyl visor allows for full face visibility, and the elastic fabric and foam lining prevent air leakage. An adjustable hat helps fix the device on the head. It is detachable and can be replaced to fit the user’s preference.

The prototype used 3D-printed materials for the main structure with Open Source SLDPRT files. These printed parts are attached using epoxy, hot glue, and superglue. For the removable cloth parts, consisting of the hat and the sealing cloth, velcro strips help to attach them to the chamber and visor. Finally, the visor is removable, in case the user needs to eat, drink, or touch their face.

<img width="574" alt="Screen Shot 2022-05-05 at 9 51 14 PM" src="https://user-images.githubusercontent.com/48959871/167059038-4898df00-ce2f-4938-be9a-9f016c09c69a.png">

YouTube link of how our prototype works: 
https://youtu.be/ixSwmfPEwCU

## Airflow Testing
Since we did not use real UV-C light, we conducted airflow testing to make sure that air is circulating well throughout the device. To do this, we measured the air being directed into the chamber and the air being directed out the other chamber. Data was collected with an airflow probe, and we placed this airflow probe over the openings of each of the chambers in the back at the same distance. We placed the probe in front of the inhale chamber for about 20 seconds until it had a steady reading, then did the same for the exhale chamber.

We ran 3 trials of this test and our results are shown below in Table 1. Our probe measured the flow rate in and flow rate out in cubed feet per meter. The flow rate in represents the air going into the chamber, while the flow rate out is the flow rate going out the other chamber. We were then able to calculate the volume of air collected in 1 min by making the necessary conversion, which was multiplying the flow rate by about 28. The target value we were trying to achieve is a volume of 6 L/min for both the air going in and the air going out, because that it the average volume that an adult breathes in and out in one minute. As you can see from Table 1 below, all 3 of our trials passed this test. 

<img width="644" alt="Table 1" src="https://user-images.githubusercontent.com/48959871/167058794-d19490d4-7b55-44f4-b871-4c1519b24243.png">


## Audibility Testing
We conducted audibility testing to measure how much the device affects audibility. For our testing procedure, we first recorded ourselves saying “UltraVisor-C” using voice memos. We played the recording and measured the decibel level it reached using an online decibel meter. Then, we measured the decibel level while a team member wore the device and played the voice memo from inside the visor. Since N95 masks have been proven to reduce speech audibility by about 2.7 decibels, the target value of reduction for each recording is ≤ 2.7 decibels. We conducted 3 trials of this process, and the data is shown below in Table 2. We calculated the average of all 3 trials and then calculated the difference. There was only a 1.867 dB reduction between wearing the device versus speaking normally, so our prototype passed this test. 

<img width="635" alt="Table 2" src="https://user-images.githubusercontent.com/48959871/167058807-2384e6a5-dbd0-4815-9f57-6e36534a7b99.png">

## Comfortability Testing
In our Comfortability test, we asked 22 people of varying head sizes to wear the device and rate their opinions on a user defined scale, and we then calculated the average of all the ratings according to our User Defined Scale (Table 3). The target value was an average rating of ≥ 4, which specified that the device is easier to breathe in than an N95 mask and components do not get in the way of work. Our final average rating was 3.7, so the device failed the test, and we cannot conclude that the device is comfortable to wear.

<img width="644" alt="Table 3" src="https://user-images.githubusercontent.com/48959871/167058832-af7bb549-d1d4-4f10-a2e0-006f8eb81f39.png">

## Safety and Battery Life
In our Safety test, we first rubbed a balloon across the device surface to ensure that there were no sharp corners, and it did not pop. Secondly, we observed whether electrical wires are exposed on the exterior, and they are not. Thirdly, we ensured that the battery is fully covered and not potentially exposed to sunlight. We repeated the test twice to account for regions that may have been missed by the balloon or battery areas and wires that may have been missed. The device passed all rounds of testing, so we conclude that our device is safe to use. 

In our Battery Life test, we calculated the battery life from our data, given in terms of voltage, milliamp hours. Since it is a straightforward calculation, we performed this test only once. The target battery life is ≥ 8 hours because we assume hospital staff will have a break every 8 hours. The calculated battery life of our device was 32.5 hours, so our device passed the test, and we can conclude that the battery does not need to be recharged during a single shift.

## Strengths and Limitations
The strengths of our current prototype are that we were able to successfully separate the sanitation of inhaled and exhaled air by dividing the UV-C chamber. In addition to the UV-C lamps on the sides, the added UV-C lamp in the middle provides sufficient sanitation for the air passing through. Furthermore, we created a system using fans to direct the air from the inhale chamber to the exhale chamber. Our airflow testing data shows that the rate of air flowing into the inhale chamber is approximately equal to the rate of air flowing out of the exhale chamber. However, our device has a few limitations. Even though our prototype passed the audibility test we created, the decibel measurements do not account for how muffled speech is. We noticed that when teammates wear the device, their speech is significantly muffled. Secondly, our device has some issues involving adjustability. We used elastic fabric to fit the neck area, but the visor frame around the forehead is not as adjustable. In consequence, individuals with larger or smaller neck sizes may find the device uncomfortable. Lastly, we noticed issues with the battery of the prototype. Although our device is projected to last up to 32.5 hours, we discovered that the voltage drops after long periods of time, so the fan does not consistently move at its maximum speed.

## Future Work
For future teams that plan on continuing this project, we hope that our prototype's current limitations can be addressed. First, to address the issue of muffled speech, a microphone speaker system could possibly be implemented in the device. Second, for issues regarding adjustability, different visor sizes could be made for individuals who have larger or smaller head sizes. Lastly, to address the issue of comfortability and dropping battery voltage, a smaller, rechargeable battery could be used to reduce weight on top of the user's head. 

The modified CAD files we created are added to this post, as well as photos of our prototypes. 

## References
https://www.uvisor.org/

https://doi.org/10.1086/503643

https://www.mdpi.com/1996-1944/13/15/3363/htm

https://doi.org/10.37624/ijert/13.7.2020.1562-1566

https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7882915/

https://www.sciencedirect.com/science/article/pii/S1477893920302301

https://doi.org/10.1063/5.0022968

## Acknowledgements
Client: Dr. Robert Read 

Instructor: Dr. Emin Kececi 

Instructor: Dr. Deirdre Hunter

Design Mentor: Charlie Gorton 

Faculty Mentor: Dr. Bilal Ghosn 

Writing Mentor: Rachel Lee

