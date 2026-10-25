# CS330-Comp-Graphic-and-Visualization
This repository contains my final project for CS 330. The project includes a ZIP folder containing the completed 3D scene and a Design Decisions document that explains the choices I made while developing it. My scene recreates a marina fish display using primitive OpenGL shapes, textures, lighting, and an interactive camera.

How do I approach designing software?

I approach software design by first identifying the required features and separating them into smaller parts. For this project, I studied the reference image and identified the individual objects that would need to be created, including the fish, sign, support posts, wooden beam, fence, and ground plane. I then considered which primitive shapes could be combined to represent each object.

The project helped me improve my ability to break a complex object into simpler components. Each fish was constructed using cones, cylinders, tapered cylinders, prisms, and a pyramid. I had to plan the scale, rotation, and position of every component so that the separate shapes would appear as one complete object.

My design process involved creating the basic geometry first and then adding more advanced features in stages. I began by constructing one fish, followed by the surrounding objects. I then added camera navigation, textures, materials, and lighting. This approach allowed me to focus on one area at a time and identify problems before adding more complexity.

This same process can be applied to future projects by separating large requirements into smaller and more manageable tasks. Planning the structure before writing all of the code can reduce confusion and make later changes easier.

How do I approach developing programs?

I approach program development through iteration and testing. Instead of attempting to complete the entire scene at once, I added and tested features gradually. I first confirmed that individual shapes could be loaded and rendered correctly. I then adjusted their transformations until their positions, proportions, and orientations matched the intended scene.

Iteration was especially important for the fish geometry, camera position, texture scaling, and lighting. Some parts looked correct in the code but did not appear correct when rendered. I repeatedly rebuilt and ran the program while adjusting values until the results improved. Lighting required several revisions because the scene was initially either too dark or too harsh. Testing different light positions, colors, strengths, and directions helped me create a more balanced result.

Throughout the milestones, my code became more organized and reusable. Functions such as SetTransformations, SetShaderColor, SetShaderTexture, SetTextureUVScale, and SetShaderMaterial allowed the same logic to be used for many objects. I also reused the fish construction with different horizontal offsets instead of manually rewriting every fish. This reduced duplicated code and made the scene easier to update.

My development approach evolved from focusing mainly on whether an object appeared on the screen to considering how geometry, textures, lighting, and user controls work together. I also became more comfortable debugging visual problems by changing one value or feature at a time.

How can computer science help me in reaching my goals?

Computational graphics gave me experience with concepts that can support my future educational pathway. I gained a better understanding of coordinate systems, transformation matrices, camera movement, texture mapping, collision concepts, and lighting calculations. These topics connect programming with mathematics and visual design.

These skills can also be expanded in future courses involving game development, simulations, user interfaces, and data visualization. I would like to continue learning about animation, realistic shadows, model importing, and more advanced rendering techniques.

Professionally, computational graphics and visualization can help me present complex information in ways that are easier for users to understand. Even if I am not working directly as a graphics programmer, the problem solving skills used in this project can apply to general software development. Breaking a visual goal into smaller technical requirements, testing changes through iteration, and organizing code into reusable functions are all valuable development practices. This project also gave me a stronger foundation for creating interactive applications and virtual environments in future personal and professional projects.
