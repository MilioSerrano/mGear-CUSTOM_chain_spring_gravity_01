Custom chain spring with gravitiy and colliders setup.

Following some insight from Hiroyuki Akasaki [https://x.com/akasaki1211/media](https://x.com/akasaki1211/status/1761769004715397579) 

I managed to add gravity and colliders to the spring chain component.

I simply duplicated the component and hooked the mgear_springGravityNode to it, exposing the relevant parameters to the host control.

![image](https://github.com/user-attachments/assets/78e44fc2-92d1-4971-8ba5-447c1b026faa)

The component is exactly as the spring chain:

![image](https://github.com/user-attachments/assets/41a1bbe3-6a07-48cb-8158-8bcfcea02c2e)

Once built you can see the usual spring parameters plus the new ones exposed: 

![image](https://github.com/user-attachments/assets/967c5e60-0436-4c3f-9d52-c2fc0c184b99)

Gravity per sections 0 to 10

Gravity direction pointing down (Y) per section

Use Ground. (infinite plane at 0.0.0) per section

Collide softness when you connect some basic primitives to the collider list and radius

![image](https://github.com/user-attachments/assets/14e556e4-8550-4f0b-9281-7f7957417107)





Download the zip, and extract into your mGear shifter Classic components:

![image](https://github.com/user-attachments/assets/6c38679d-1aca-42ee-84d6-d9c0e968f373)
