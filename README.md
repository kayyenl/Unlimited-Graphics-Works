### Welcome to my Graphics Works!
The works below have been done in OpenGL, in NUS's Computer Graphics Course.

**Lab 1 - Bouncing Circles**  
By making use of the correct event callback functions, we draw circles and implement their logic in the space, making it look like a DVD player screensaver.  

![photo_2023-09-30_15-14-25](https://github.com/kayyenl/Unlimited-Graphics-Works/assets/99934242/8d5b365d-6d02-43d3-8d6b-905fe75dfc8b)  

**Lab 2 - Need for Speed**  
By understanding projection and view transformation, we learn how to provide a suitable `gluLookAt` and correct implementation of `glPerspective` (or `glFrustum`). This allowed us to position the camera and simulate an orbiting view around a planet while rendering cars moving along great circles on its surface.  

![image](https://github.com/kayyenl/Unlimited-Graphics-Works/assets/99934242/64ba5433-a581-42e3-be02-b8581e7c05c1)  

---

**Lab 3 - Reflective Table**  
In this lab, we implemented **planar reflections** using multi-pass rendering techniques and texture mapping. The reflective surface (a table) was created by rendering the scene from an imaginary viewpoint and applying the captured texture onto the table. The resulting reflection included mipmapping to smooth textures and simulated partial reflectivity, blending the reflection with the base material's color.  

![image](https://github.com/user-attachments/assets/0f210ed4-4943-44b3-b89b-9d0cf0e7fca9)

---

**Lab 4 - Ray Tracer**  
This lab introduced the fundamentals of **ray tracing** by implementing the Whitted Ray Tracing algorithm. We programmed recursive ray intersections for spheres and planes, calculated lighting effects, and handled reflective surfaces. The final render included realistic shadows, reflections, and specular highlights, with recursion depth controlling the level of reflection realism.  

![image](https://github.com/user-attachments/assets/1607f845-d7e6-4e7d-acc9-3735ee716383)

---

**CS4247 Lab 1 - Skybox and Normal Mapping**  
We explored **environment rendering** by implementing a skybox with cubemap textures to create an infinite background effect. Additionally, we applied **normal mapping** to enhance surface details on a cube, creating realistic lighting interactions without increasing the geometry complexity.  

![image](https://github.com/user-attachments/assets/16dd3255-2d2f-48fb-8007-5eb16c11daf5)

---

**CS4247 Lab 2 - Shadow Mapping with PCF**  
In this lab, we implemented **shadow mapping** to project shadows from a light source onto a scene, using framebuffers to store depth information. We enhanced the shadow realism by integrating **percentage-closer filtering (PCF)** to smooth shadow edges and eliminate jagged artifacts.  

![image](https://github.com/user-attachments/assets/7231539f-96f6-4dbc-a8e7-ed770e32cd03)

---

**CS4247 Lab 3 - Whitted Ray Tracing in GLSL**  
Using GLSL shaders in Shadertoy, we built a **real-time ray tracer** capable of recursive reflections and lighting. The project included **distributed ray tracing** to simulate soft shadows, anti-aliasing, and depth-of-field effects, producing photorealistic scenes with dynamic objects and lights.  

---

**CS4247 Lab 4 - Progressive Radiosity**  
In the final lab, we implemented the **progressive refinement radiosity algorithm** for global illumination. This included computing form factors with the hemicube method and iteratively refining light distribution for diffuse interreflections. The rendered scene demonstrated photorealistic ambient lighting and realistic diffuse shading.  
