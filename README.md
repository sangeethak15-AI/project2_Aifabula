## AI Fabula - Generative Storytelling and Visual Augmentation Platform


## About
Storytelling has evolved significantly with the advent of Artificial Intelligence (AI), allowing for the seamless generation of narratives and visuals. This project, AI Fabula – Generative Storytelling and Visual Augmentation Platform, aims to leverage Gemini-1.5-Flash and Hugging Face FLUX.1-dev to create a system that takes a user prompt as input and generates an engaging story with corresponding AI-generated images. 

## Features
Story Generation: Automatically generate creative stories based on user prompts or predefined themes.
Image Generation: Generate images that match the story using AI-based models.
Dynamic Layout: The story and image containers adjust their height dynamically based on content. 
Grid-Based Image Display: Images are arranged in a responsive grid format.
Smooth Scrolling & Overflow Handling: If the content exceeds a certain height, smooth scrolling is enabled.

## Requirements
HARDWARE ENVIRONMENT
Processor	: Pentium Dual Core 2.00GH
Hard disk	: 120 GB
RAM : 2GB (minimum)
Keyboard	: 110 keys enhanced
SOFTWARE ENVIRONMENT
Operating system	: Windows7 (with service pack 1), 8, 8.1 ,10 and 11
Language	: Python
TECHNOLOGIES USED
Frontend: HTML, CSS, JavaScript
Backend: Flask (Python), Asyncio, Requests
AI & ML: Gemini AI, Hugging Face FLUX.1-dev
Database: Google Sheets
Cloud Integration: Google Apps Script


## System Architecture
This graphic provides a concise and understandable description of all the entities currently integrated into the system. The diagram shows how the many actions and choices are linked together. You might say that the whole process and how it was carried out is a picture. The figure below shows the functional connections between various entities.

![Screenshot 2025-02-24 233855](https://github.com/user-attachments/assets/4ba80969-8930-44b6-b7a6-e11c21ed51cc)


## Output

The prediction step in the narrative generation system is the process of converting user inputs into coherent stories with visually appropriate images through Gemini AI and Hugging Face FLUX.1-dev. Upon a user's input, the Flask-based backend asynchronously processes the input to allow for efficient handling of multiple requests. The system tokenizes and encodes the input text first using pre-trained transformer-based model embeddings, converting it into a contextualized representation. The AI model subsequently anticipates the most contextually appropriate story details, guaranteeing coherence and logical continuity. Attention mechanism in the transformer model ensures that the output text is consistent, while reinforcement learning with human feedback (RLHF) continuously improves quality. The story generation model assesses language features such as narrative structure, entity relationships, and sentiment, enabling it to respond appropriately to various storytelling styles.
#### Output1 - Name of the output

![WhatsApp Image 2025-02-24 at 23 31 38](https://github.com/user-attachments/assets/a929fcaf-b75d-4bcf-89b9-3ebc50f289ec)





## Results and Impact
The Story Generation with Images project showcases the successful application of artificial intelligence in creative narrative storytelling. With Google Gemini for generating interesting stories and Hugging Face FLUX.1 for creating high-quality images, the system converts user input into descriptive stories with associated images. The use of asynchronous processing guarantees seamless operation, allowing stories and images to be generated simultaneously without interruptions. This provides an improved user experience, making the platform more responsive and efficient.

## Articles published / References
1.Hong, X., Sayeed, A., Mehra, K., Demberg, V., & Schiele, B. (2023). Visual writing prompts: Character-grounded story generation with curated image sequences. Transactions of the Association for Computational Linguistics, 11, 565-581.
2.Fan, A., Lewis, M., & Dauphin, Y. (2019). Strategies for structuring story generation. arXiv preprint arXiv:1902.01109.
3.Liu, T., Wang, K., Li, S., van de Weijer, J., Khan, F. S., Yang, S., ... & Cheng, M. M. (2025). One-Prompt-One-Story: Free-Lunch Consistent Text-to-Image Generation Using a Single Prompt. arXiv preprint arXiv:2501.13554.
4.Li, D., Sohn, S. S., Zhang, S., Chang, C. J., & Kapadia, M. (2024, November). From Words to Worlds: Transforming One-line Prompts into Multi-modal Digital Stories with LLM Agents. In Proceedings of the 17th ACM SIGGRAPH Conference on Motion, Interaction, and Games (pp. 1-12).
5.Maharana, A., Hannan, D., & Bansal, M. (2022, October). Storydall-e: Adapting pretrained text-to-image transformers for story continuation. In European Conference on Computer Vision (pp. 70-87). Cham: Springer Nature Switzerland.





