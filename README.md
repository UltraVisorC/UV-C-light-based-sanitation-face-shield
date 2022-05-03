# UV-C-light-based-air-sanitation-face-shield

## The Central Problem 
The current pandemic poses a serious threat to people in high-risk environments, especially doctors and nurses. While there are many protective measures, they are not 100% effective. Our team is tasked with designing a prototype modeled after the UVisor, an existing prototype and face shield that is 99% effective against viruses. The current UVisor is a 2.5 lb faceshield that utilizes UV-C technology to sanitize inhaled air particles and has a battery life of 4-8 hours. Although the UVisor is able to successfully sanitize incoming air, one missing component is its inability to sanitize outgoing air. This poses a safety concern for medical professionals who wish not to infect patients and other staff by viral transmission from exhaled air. 

## Problem Statement
The UltraVisor-C’s central goal is to improve the UVisor by sanitizing exhaled air while maintaining the same weight, sanitation efficacy, and durability. Additional targets include improving battery life, comfort, audibility, and ease of use.

## Modifying the UVisor 
The current UVisor has two fans that blow air downwards in front of the user's face. These fans direct air through the UV-C chamber where the air is sanitized by the UV-lamps. However, this airflow mechanism directes exhaled air downwards and through a hole at the bottom of the device, which is why exhaled air is not cleaned. 

One main modification that we made to the original UVisor to address this issue was separating the UV-C chamber to distinguish inhaled and exhaled air. To do this, we  modified the original CAD file to create a wall in the middle. Another modification we made to the original Visor design was reversing one fan. The components are assembled such that most of the air is sealed inside the product with the built-in airflow mechanism. As shown in the image below, the green arrows represent the direction of the air flowing inside the UVisor. The air is pulled in through the inhale chamber with a fan blowing the air into the visor. After a complete circulation of air within the device, the exhaled air will be directed outwards into the exhale UV-C chamber with the other reversed fan. In our prototype, we used LED lights to model UV-C light. The last main modification we made was creating a sealed bottom. Our device uses foam lining and stretchy cloth to make sure minimal exhaled air is escaping from the sides. The stretchy cloth is velcroed to the bottom so it can be easily detached for cleaning. Some additional components we added to the device include a battery compartment that sits on top of the head and a detachable visor. 

<img width="593" alt="Screen Shot 2022-05-02 at 10 51 30 PM" src="https://user-images.githubusercontent.com/48959871/166402635-e789592c-06b4-4e9c-8194-369c797c4b84.png">

## Airflow Testing
Since we did not use real UV-C light, we conducted airflow testing to make sure that air is circulating well throughout the device. To do this, we measured the air being directed into the chamber and the air being directed out the other chamber. Data was collected with an airflow probe, and we placed this airflow probe over the openings of each of the chambers in the back at the same distance. We placed the probe in front of the inhale chamber for about 20 seconds until it had a steady reading, then did the same for the exhale chamber.

We ran 3 trials of this test and our results are shown below in Table 1. Our probe measured the flow rate in and flow rate out in cubed feet per meter. The flow rate in represents the air going into the chamber, while the flow rate out is the flow rate going out the other chamber. We were then able to calculate the volume of air collected in 1 min by making the necessary conversion, which was multiplying the flow rate by about 28. The target value we were trying to achieve is a volume of 6 L/min for both the air going in and the air going out, because that it the average volume that an adult breathes in and out in one minute. As you can see from the yellow columns, all 3 of our trials passed this test. 

<img width="581" alt="Screen Shot 2022-05-03 at 4 44 55 PM" src="https://user-images.githubusercontent.com/48959871/166571635-7c22fff6-01b3-438e-9baa-e20ef2cb97f4.png">




