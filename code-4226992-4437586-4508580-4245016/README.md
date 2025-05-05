# Creative Drawing Assistant with Style Options

## Overview
The **Creative Drawing Assistant** is a Gradio-based application that generates creative artworks based on user preferences, themes, sentiments, and selected artistic styles. It leverages a genetic algorithm to optimize themes and uses the Stable Diffusion model for generating images.

## Features
- **User Preferences**: Adjust sliders for different artistic themes such as landscape, portrait, abstract, still life, and fantasy.
- **Sentiment Analysis**: The application analyzes the sentiment of user-provided descriptions to adjust the mood of the generated artwork.
- **Art Styles**: Choose from artistic styles such as impressionism, cubism, and surrealism.
- **Image Generation**: Generates high-quality images using the Stable Diffusion model.
- **Interactive Interface**: Intuitive Gradio interface for easy interaction and customization.

## How It Works
1. **User Input**: Provide preferences for themes, a description of your idea, and choose an artistic style.
2. **Genetic Algorithm**: The app optimizes the combination of themes based on your preferences.
3. **Prompt Generation**: Creates a descriptive prompt based on your preferences, sentiment, and style.
4. **Image Generation**: Uses Stable Diffusion to create an image based on the generated prompt.

## Installation
To run the application locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```bash
   cd creative-drawing-assistant
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Download the Stable Diffusion model:
   Ensure you have access to the Stable Diffusion model and download it from `runwayml/stable-diffusion-v1-5`.

## Usage
Run the application with the following command:
```bash
python app.py
```
This will launch a Gradio interface in your browser where you can interact with the Creative Drawing Assistant.

## Input Parameters
- **Sliders**: Adjust the preference levels (1-5) for each theme: Landscape, Portrait, Abstract, Still Life, Fantasy.
- **Text Box**: Provide a description of your idea or theme.
- **Radio Buttons**: Select an artistic style (Impressionism, Cubism, Surrealism).

## Outputs
- **Generated Prompt**: The detailed prompt used to generate the image.
- **Generated Image**: The artwork created by the Stable Diffusion model.
- **Image Path**: File path of the saved image.

## Dependencies
The application relies on the following libraries:
- `gradio`
- `diffusers`
- `torch`
- `textblob`
- `json`
- `random`

## File Structure
- `app.py`: Main application file containing the logic for generating images and user interaction.
- `preferences.json`: File used to store and load user preferences.
- `requirements.txt`: List of required dependencies.

## Contributing
Contributions are welcome! Feel free to fork the repository and submit a pull request with improvements or new features.

## License
This project is licensed under the MIT License.
