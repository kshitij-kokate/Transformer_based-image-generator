# Image Generation Using AI

## Overview
This project focuses on generating high-quality images based on textual prompts. The implementation leverages state-of-the-art AI models to produce both **anime-style** and **realistic images** with high accuracy and clarity. The model also allows users to incorporate custom text within generated images (e.g., "Write inside a white cloud at a corner").

## Features
- **Anime & Realistic Image Generation:** Users can generate images in different artistic styles based on their prompts.
- **Custom Text Embedding:** Supports adding custom text in specified regions of the generated image.
- **High-Quality Outputs:** Ensures clarity, precision, and visually appealing results.
- **Flexible Prompt Input:** Users can specify various characteristics like background, colors, or specific objects.
- **Scalability:** Optimized to handle multiple image requests efficiently.

## Requirements
To run this project, install the required dependencies using:
```bash
pip install torch transformers diffusers pillow openai
```

## Usage
### Running the Notebook
1. Open the `Img-Generation.ipynb` notebook in Jupyter Notebook or Google Colab.
2. Load the necessary models and dependencies.
3. Provide a textual prompt for image generation.
4. (Optional) Specify custom text and its placement in the image.
5. Execute the notebook cells to generate and save the image.

### Example Input
```python
prompt = "A cyberpunk city with neon lights and flying cars"
text = "Future Awaits!"
position = "top-right"
```

### Example Output
The AI generates an image of a futuristic cyberpunk city with vibrant neon lighting, and the text **"Future Awaits!"** appears in the **top-right** corner.

## Technologies Used
- **PyTorch**: For running deep learning models efficiently.
- **Hugging Face Diffusers**: For accessing state-of-the-art image-generation models.
- **OpenAI API**: For enhancing text-based prompts.
- **PIL (Pillow)**: For processing and adding text overlays to images.

## Future Enhancements
- Improve text placement accuracy using object detection.
- Enhance model selection for anime and realistic styles separately.
- Provide an API interface for automated image generation.
- Allow users to modify generated images with additional effects.

## Contributing
If you'd like to contribute, feel free to fork this repository and submit a pull request with improvements.

## License
This project is open-source and available under the MIT License.

