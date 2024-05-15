# Local Language Text-to-Image Generator

This project is a local language text-to-image generator that allows users to generate images based on text prompts in Yoruba or French languages. It utilizes the Google Translate API to translate the prompts to English and then generates images using the Dall-E 3 model.

## Features

- Select input language: Choose between Yoruba and French languages for the text prompt.
- Text prompt: Enter a text prompt in the selected language to generate an image.
- Image generation: The application translates the prompt to English using the Google Translate API and generates an image using the Dall-E 3 model.
- Display result: The generated image is displayed in the application.

## Building from Scratch

To get started with this project, follow these steps:

1. Create an account on Windmill
2. Create a new app
3. Include select input, text input, button and Image components
4. Add the comtents of `inline_script.py` into the inline script of the button
5. Set up environment variables
6. Test

## Copypasta

1. Create a Windmill account
2. Copy the contents of the `hub_compatible_json.json` file
3. Click on Import from JSON
4. Paste the `hub_compatible_json.json`
5. Test

## Usage

1. Select the desired input language (Yoruba or French) from the dropdown menu.
2. Enter a text prompt in the selected language in the text input field.
3. Click the "Press me" button to initiate the image generation process.
4. The generated image will be displayed in the application.

## How It Works

The application follows these steps to generate images from local language text prompts:

1. The user selects the input language (Yoruba or French) and enters a text prompt.
2. When the "Generate Image" button is clicked, the application sends the selected language and text prompt to the backend.
3. The backend uses the Google Translate API to translate the text prompt from the selected language to English.
4. The translated English prompt is then passed to the Dall-E 3 model to generate an image.
5. The generated image URL is returned to the frontend and displayed in the application.

## Contributing

Contributions to this project are welcome! Contribute to [Bluewind](https://www.bluewind.ai/contributors)
