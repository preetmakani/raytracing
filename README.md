# raytracing

This C++ code showcases a ray tracing algorithm that generates stunning photorealistic images of 3D scenes. The implementation involves simulating the behaviour of light rays as they interact with virtual objects and light sources. The location is set up with various materials, including spheres with different properties such as refractive index, albedo, and diffuse colour. The algorithm traces rays from a virtual camera's perspective and calculates their intersections with objects in the scene. It handles reflections and refractions, giving surfaces a realistic glossy or transparent appearance. Shadows are accurately rendered by casting rays toward light sources to detect occlusion. The code uses parallel processing with OpenMP to optimize rendering times. The final output is saved as a PPM image, offering a visually captivating representation of the 3D scene.

Usage:
Users can customize the scene by adding or modifying the positions and properties of spheres, creating diverse environments. Experimenting with different materials allows for the creation of unique surface appearances and visual effects. Adjusting camera parameters like field of view and resolution offers flexibility in tailoring the output to specific requirements. This ray tracing code is an educational tool and a foundation for further exploration into advanced rendering techniques and complex scene design. It empowers users to generate impressive and immersive photorealistic 3D scenes for various applications, such as computer graphics, game development, and visual effects.

Below is a sample ppm that is output with the current sphere configurations. 

![out](https://github.com/preetmakani/raytracing/assets/40505135/eec53d29-a242-4b27-8dc8-25a58666f77f)
