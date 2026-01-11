# wildlife_identification_system

The problem of detecting wildlife populations in remote areas, where in-person monitoring can be challenging. Our proposed solution is an automatic wildlife detection and monitoring system. This Wildlife Monitoring System will consist of key components, including a camera, an Animal Categorization System, a Mobile Hotspot Communication System, a Power Management System, and an Animal Tracking System. These elements work together to ensure that wildlife activity can be effectively monitored, where real-time tracking and data transmission are essential to understanding and managing wildlife behaviors.

The hardware is split between structure and electronics. The structure consists of the enclosure on top of a tripod with a double ball joint on top to the solar panel and the motion sensor on the side. The double ball joint for the solar panel allows it to be positioned ideally for the sun depending on the surroundings and the latitude to determine the angle for it to absorb the most sunlight. Inside the enclosure are all of the chips. The battery and solar panel are connected to the solar power management board which keeps track of the battery power and charges it. The power management board directly powers the wireless hotspot and the Nvidida Jetson Nano which then powers the Arduino. The battery is connected to a voltage sensor which sends battery information to the Arduino. The motion sensor is also connected to Arduino which sends motion triggers and battery health information to the Nano over serial port. The cameras are connected to the Nano using ribbon cables. The Nano sends the processed information to the wireless hotspot which then sends it to the google drive.

<img width="628" height="496" alt="image" src="https://github.com/user-attachments/assets/52eee28e-1cc5-4918-9cba-fc86a167d017" />


<img width="750" height="1000" alt="image" src="https://github.com/user-attachments/assets/ef20eaae-d8c3-4242-8c90-c40af577dc5d" />


<img width="1200" height="1084" alt="image" src="https://github.com/user-attachments/assets/14ebf698-d0b3-46fe-a1f1-98f8c3467675" />


<img width="1024" height="251" alt="image" src="https://github.com/user-attachments/assets/399486eb-dcda-4949-a92e-39323df92589" />


<img width="1024" height="987" alt="image" src="https://github.com/user-attachments/assets/7f8ab717-7482-4ab5-8eba-08d7954e8165" />





