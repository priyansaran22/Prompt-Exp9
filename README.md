# Exno.9-Exploration of Prompting Techniques for Video Generation

# Date: 04-09-2026
# Reg. No.: 212225060282

# Aim:
To demonstrate the ability of text-to-video generation tools to reproduce an existing video by crafting precise prompts. The goal is to identify key elements within the video and use these details to generate a video as close as possible to the original.

# AI Tools Required:
- ChatGPT
- Sora / Text-to-Video Generation Tool
- Stable Diffusion-based Video Generation Tools
- Midjourney
- Web Browser

# Explanation:

Text-to-video generation is a generative AI technique that creates videos from natural-language prompts. The quality of the generated video depends on how accurately the prompt describes the subjects, actions, environment, camera movement, lighting, style, and other visual characteristics.

In this experiment, an existing reference video is analyzed and its important visual and temporal characteristics are identified. These characteristics are then converted into a detailed prompt and provided to a text-to-video generation model.

The generated video is compared with the original video. If differences are observed, the prompt is refined by adding more specific information about the objects, actions, camera movement, lighting, background, timing, and visual style.

# Video Analysis:

The reference video is analyzed based on the following characteristics:

1. Objects/Subjects:
- Identify the main subjects and objects present in the video.
- Observe their appearance, size, position, and movement.

2. Actions and Motion:
- Identify the actions performed by the subjects.
- Observe the direction and speed of movement.
- Identify how the scene changes over time.

3. Colors:
- Identify the dominant colors and overall color palette.
- Observe contrasts, highlights, and color changes during the video.

4. Textures:
- Observe surface characteristics such as smooth, rough, glossy, metallic, or natural textures.

5. Lighting:
- Identify the brightness, shadows, highlights, light direction, and time of day.

6. Background:
- Identify whether the environment is indoor, outdoor, natural, urban, or artificial.
- Observe important background objects and environmental details.

7. Composition:
- Identify the position of the main subject.
- Observe foreground, middle ground, and background elements.
- Analyze the perspective and framing.

8. Camera Movement:
- Identify whether the camera is stationary, panning, tilting, zooming, tracking, or moving around the subject.

9. Style:
- Identify whether the video is realistic, cinematic, artistic, animated, cartoon-like, or minimalistic.

# Basic Prompt:

"A video of a serene landscape with mountains and a river."

# Basic Prompt Output:

The video generation model produces a basic landscape video containing mountains and a river. However, the generated video may differ from the reference in terms of colors, camera movement, lighting, environment, and overall composition.

# Refined Prompt:

"Generate a realistic video of a serene landscape during sunset, showing purple mountains in the background and a calm river flowing through the scene. The river should reflect the warm colors of the sunset. Include a few trees along the riverbank, soft clouds in the sky, natural lighting, and gentle camera movement."

# Advanced Prompt:

"Create a realistic cinematic video closely matching the reference video. Preserve the main subject, environment, composition, color palette, lighting, camera perspective, and movement.

The scene should contain the same major foreground, middle-ground, and background elements as the reference. Maintain consistent object proportions and positions throughout the video.

Use natural lighting, realistic shadows, detailed textures, smooth motion, and stable object identity. The camera should follow the same type of movement as the reference, with smooth and controlled motion. Maintain temporal consistency between frames and avoid unnecessary objects or sudden scene changes."

# Final Prompt:

"Generate a highly detailed and realistic video reproduction of the reference video. Match the original subject, actions, environment, object placement, camera angle, camera movement, perspective, color palette, lighting, shadows, textures, depth, and visual style as closely as possible.

Preserve the movement and timing of the main subject throughout the video. Maintain consistent appearance, proportions, and identity of all important objects across frames. Use smooth natural motion, realistic physics, stable backgrounds, and cinematic lighting.

Do not introduce additional objects or unnecessary scene changes. Maintain temporal consistency and ensure that transitions and camera movements remain smooth throughout the generated video."

# Procedure:

1. Examine the given reference video carefully.

2. Identify the main subjects and objects present in the video.

3. Observe the actions and movements performed by the subjects.

4. Analyze the dominant colors and overall color palette.

5. Identify the textures and surface characteristics of important objects.

6. Analyze the lighting, shadows, highlights, and time of day.

7. Study the background and surrounding environment.

8. Analyze the composition, framing, perspective, and camera angle.

9. Identify the camera movement such as panning, tracking, zooming, or stationary shots.

10. Identify the artistic or visual style of the video.

11. Create a basic prompt describing the main elements of the video.

12. Generate an initial video using a text-to-video generation model.

13. Compare the generated video with the original reference video.

14. Identify differences in subjects, actions, colors, composition, lighting, camera movement, and style.

15. Refine the prompt by adding the missing or incorrect details.

16. Generate the video again using the refined prompt.

17. Repeat the refinement process until the generated video closely resembles the reference video.

18. Save the final generated video and document all prompts used during the experiment.

# Tools/LLMs for Video Generation:

1. Sora:
- An AI video generation system that can generate video content from natural-language descriptions.

2. Stable Diffusion-based Video Generation Tools:
- Video generation systems based on diffusion models that can generate visual content from textual descriptions.

3. Midjourney:
- An AI generative tool capable of creating visual content from natural-language prompts and can be used as part of generative video workflows.

# Comparison of Original and Generated Video:

| Feature | Original Video | Generated Video |
|---|---|---|
| Main Subject | Present as shown in reference | Reproduced using the prompt |
| Actions | Original movement and actions | Similar generated movement |
| Composition | Original arrangement | Similar arrangement |
| Colors | Original color palette | Similar color palette |
| Lighting | Original lighting conditions | Similar lighting |
| Background | Original environment | Recreated environment |
| Camera Movement | Original camera movement | Similar camera movement |
| Texture | Original surface details | AI-generated approximation |
| Style | Original visual style | Similar generated style |
| Temporal Consistency | Continuous original motion | AI-generated continuous motion |

# Observations:

1. The basic prompt was able to reproduce the general concept of the reference video.

2. The initial generated video differed from the reference in several visual and motion-related details.

3. Adding information about the environment, colors, lighting, subject actions, and camera movement improved the generated result.

4. Including temporal consistency and motion instructions helped maintain more consistent objects throughout the video.

5. Prompt refinement was necessary to obtain a video that was visually closer to the reference.

# Differences Observed:

- Minor differences in object positions may occur.
- Subject movements may not exactly match the original.
- Camera movement may vary from the reference.
- Colors and lighting may differ slightly.
- Background details may be generated differently.
- Fine textures may not be identical.
- Some frames may contain small inconsistencies.
- Timing and speed of actions may differ from the original video.

# Prompt Refinement Analysis:

The basic prompt provided only a general description of the video. Therefore, the generated output captured the overall concept but did not accurately reproduce the visual and motion details.

The refined prompt included additional information about the subjects, actions, environment, composition, colors, lighting, camera movement, and visual style.

The final prompt additionally specified motion consistency, object identity, realistic physics, camera movement, and temporal consistency. These instructions helped guide the video generation model toward a closer reproduction of the reference video.

# Prompting Techniques Used:

1. Descriptive Prompting:
- Describes the subjects, environment, objects, and visual elements.

2. Contextual Prompting:
- Provides information about the scene, environment, and intended visual appearance.

3. Style Prompting:
- Specifies the desired artistic or visual style.

4. Camera Prompting:
- Specifies camera angle, framing, perspective, and camera movement.

5. Motion Prompting:
- Describes the actions and movements that should occur in the video.

6. Constraint-Based Prompting:
- Instructs the model to maintain object consistency and avoid unnecessary elements.

7. Iterative Prompt Refinement:
- Improves the prompt based on differences observed between the original and generated videos.

# Deliverables:

1. Original reference video.

2. Initial generated video.

3. Final generated video.

4. Basic prompt.

5. Refined prompt.

6. Final prompt.

7. Comparison report between the original and generated videos.

8. Observations regarding prompt refinement.

# Result:

The reference video was successfully analyzed and reproduced using text-to-video generation prompts. The experiment demonstrated that detailed prompts containing information about subjects, actions, colors, composition, lighting, background, camera movement, and visual style can produce generated videos that are visually closer to the original reference.

# Conclusion:

The experiment demonstrated the practical use of prompt engineering techniques for video generation. By analyzing the visual and temporal characteristics of a reference video and progressively refining the prompt, the generated video could be made closer to the original. The experiment also demonstrated the importance of precise descriptions, motion instructions, camera specifications, temporal consistency, iteration, and comparison when using AI-based text-to-video generation models.
