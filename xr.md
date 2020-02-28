# Extended Reality Interview Questions:

- Question 1:  what is VR ? 

VR (Virtual Reality) is a computer-simulated artificial multisensory 3D environment that can mimic the properties and imagery of the physical world, be completely based in fantasy, or a mix of both.
  
The system uses position-tracking and responds to the user’s inputs. In VR, the senses are temporarily fooled into believing that the artificial environment is real. The goal of a true VR experience is to create presence - the feeling of physically being somewhere else, of being in another reality.

- Question 2: what is AR ? 

AR(Augmented Reality) is a technology that enhances perception, allowing environments to be enriched in new ways. A basic characteristic of AR is that it merges the real and the virtual worlds. The technology aims to enhance our perception of reality through the incorporation of computer generated data and simulations into our senses, creating a reality-based interface.

The goal of AR devices is to supplement the real world with virtual objects by overlaying digital imageries and information on top of physical objects and enabling the users of the devices to seamlessly interact with the digital content. Through the use of computer vision and object recognition, digital information about the real world around us can not only be viewed but also manipulated in real-time.

In general, the technology combines real and virtual objects, aligns real and virtual objects with each other, and runs interactively in real-time. Furthermore, it is not restricted to a specific type of display technology, like an HMD, and can potentially be applied to other senses beside sight.

- Question 3: what is MR ? 

Mixed Reality (MR) is the blending of the physical and digital worlds.

While the main goal of mixed reality is to combine the best aspects of virtual reality and augmented reality, it can also refer to the entire spectrum of situations between virtual reality and actual reality.

In an MR environment, the user navigates through the real and virtual environments at the same time instead of exploring only a completely virtual world like in virtual reality. The main characteristic of MR is that the digital content and the real world content react to each other in real time.

- Question 4: What are the differences of AR/VR/MR ? Could you give examples about each of them ? 

- Question 5: what is motion tracking ? what is 3DOF/6DOF ?

Degrees of freedom or DOF is the ways an object can move within a space. There are a total of 6 degrees of freedom in a 3 dimensional space. The 6 DOF can be divided into 2 categories, rotational movements and translational movements.

The 3 rotational movements are pitch, yaw, and roll. These movements are tracked by most HMDs' on-board sensors. As you tilt and turn your head, the HMD senses the movements and alters its display accordingly.

Rotational Movements are tracked by IMUs or inertial measurement units consist of accelerometer, gyroscope and magnetometer. These IMUs measure the HMD's velocity, orientation, and gravitational forces to infer rotational orientation and movement. The 3 IMUs are often marketed as having "9 DOF". The 9 DOF are calculated by adding up the 3 DOF detected by each IMU. In reality, accelerometer, gyroscope and magnetometer all measure the same 3 DOF: pitch, yaw, and roll.


- Question 6: what is inside-out tracking and outside-in tracking? How des that work ? 

Inside-out tracking is a method of positional tracking commonly used in virtual reality (VR) technologies, specifically for tracking the position of head-mounted displays (HMDs) and motion controller accessories. It differentiates itself from outside-in tracking by the location of the cameras or other sensors that are used to determine the object’s position in space . In inside-out positional tracking, the camera or sensors are located on the device being tracked (e.g. HMD) while in outside-in the sensors are placed in 
a stationary location.

A VR device using inside-out tracking looks out to determine how its position changes in relation to the environment. When the headset moves, the sensors readjusts its place in the room and the virtual environment responds accordingly in real time. This type of positional tracking can be achieved with or without markers placed in the environment. 



- Question 7: what is time warping ? How does it works ? 

  Timewarp / Time warping also known as Reprojection is a technique in VR that warps the rendered image before sending it to the display to correct for the head movement occurred after the rendering.
  
  Timewarp can reduce latency and increase or maintain frame rate. Additionally, it can reduce judder caused missed frames (when frames take too long to render).
  
  Asynchronous Timewarp or ATW is when timewarp occurs on another thread in parallel (asynchronously) with rendering. Before every vsync, the ATW thread generates a new timewarped frame from the latest frame completed by the rendering thread.
  

- Question 8: what is foveated rendering ? How does it works ? 

- Question 9: what is Motion-to-photon latency ? How to reduce this latency ? 

- Question 10: what is single-buffer-rendering ? How doest it work ? 

- Question 11: what is lens distortion ? How to resolve it? 

- Question 12: what is chromatic aberration ? How to resolve it ? 
