# CS-330

How do I approach designing software?

What new design skills has your work on the project helped you to craft?
What design process did you follow for your project work?
How could tactics from your design approach be applied in future work?

How do I approach developing programs?

What new development strategies did you use while working on your 3D scene?
How did iteration factor into your development?
How has your approach to developing code evolved throughout the milestones, which led you to the project’s completion?

How can computer science help me in reaching my goals?

How do computational graphics and visualizations give you new knowledge and skills that can be applied in your future educational pathway?
How do computational graphics and visualizations give you new knowledge and skills that can be applied in your future professional pathway?

For my project, I designed and built a fully interactive 3D scene in OpenGL. This project really changed how I think about and view designing software. Instead of seeing the scene as complete world objects, I had to deconstruct everything into basic primitive meshes, cylinders, tori, spheres, boxes, and planes. I then had to rebuild those forms using transformation matrices to recreate my scene. Shifting from thinking in objects to thinking in geometry and coordinate space has also strengthened my abstract skills. I approached my design by first studying the reference image and planning the object proportions, spatial relationships, and camera placement before I started diving into the code. From there, I followed an iterative process: establish the camera system and block out the basic geometry, apply transformations, layer textures, and finally refine lighting and materials using the Phong model. Working with model, view, and projection matrices deepened my understanding of how coordinate spaces interact, especially when toggling between perspective and orthographic projections. I also became much more intentional about transformation order and how that directly impacts object placement in world space.

From a development standpoint, I built my scene incrementally and constantly tested each layer before moving on. Early milerstones were mostly about functionality, stabilizing camera movement, ensuring shader uniforms were binding correctly, and confirming textures were loaded properly. Later iterations were focused on realism and refinement, particularly adjusting diffuse and ambient specular components to differentiate materials like cardboard, glass, metal, and silicon. I spent a noteworthy amount of time fine-tuning shininess values and light color contrast in efforts to avoid flat shading. Iteration was a necessity; small changes made to specular intensity or light positioning often had much larger visual impact than rewriting geometry had. Throughout the milestones, my coding evolved noticeably. At first, I was mainly focused on getting objects to render correctly. By the end, I was thinking more about modularization, grouping related scene components, reducing redundancy, and keeping the codebase maintainable and readable. This project reinforced that graphics programming is as much about mathematical reasoning as it is about organization and structure. Computational graphics have given me a much stronger grasp of linear algebra in practice; vector math and transformations now feel more concrete instead of abstract theory. Looking in the future, these skills will directly support my educational growth in areas like interactive systems, simulation, and game development. Professionally, this project demonstrates my ability to design, implement, debug, and refine a complete 3D system while applying disciplined iteration and technical precision. Most importantly, this project helped me grow from simply writing code to intentionally engineering a visual system from the ground up.
