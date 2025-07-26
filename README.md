# Multi-Model-CLIP-guided-Generation-Using-Stable-Diffusion
Built a pipeline for image generation(Stable Diffusion) and image captioning(Blip) and comparing results using cosine similarity

## Results

| 📝 Prompt Image         | 🎨 Generated Image   | 🧾 Caption                           | 🧠 Prompt ↔ Caption Cosine Similarity | 🔄 Re-Generated Image   | 🖼️ Image ↔ Re-Gen Image Cosine Similarity |
| ----------------------- | -------------------- | ------------------------------------ | ------------------------------------- | ----------------------- | ------------------------------------------ |
| ![](images/prompt1.png) | ![](images/gen1.png) | *A cat wearing sunglasses*           | **0.89**                              | ![](images/re_gen1.png) | **0.84**                                   |
| ![](images/prompt2.png) | ![](images/gen2.png) | *A rocket launching at night*        | **0.91**                              | ![](images/re_gen2.png) | **0.86**                                   |
| ![](images/prompt3.png) | ![](images/gen3.png) | *A person hiking in snowy mountains* | **0.87**                              | ![](images/re_gen3.png) | **0.83**                                   |

