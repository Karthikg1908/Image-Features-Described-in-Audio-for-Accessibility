# Image Features Described in Audio for Accessibility

## Overview
This project aims to enhance accessibility for visually impaired individuals by generating audio descriptions of image features. Using state-of-the-art image captioning models, the project creates descriptive narratives that are then translated into audio formats for easy comprehension.

## Features
- **Image Captioning**: Automatically generates captions for input images using a Vision-Transformer and GPT-2 model.
- **Multilingual Translation**: Translates English captions into Kannada and Hindi to reach a broader audience.
- **Audio Narration**: Converts text captions into audio, providing an auditory representation of visual content.
- **User-Friendly Interface**: Simple integration allows users to input any image and receive descriptive audio output.

## Installation and Setup
To run this project, check out the code.ipynb file for detailed setup and installation instructions.

## Usage
Follow these steps to generate audio descriptions for your images:

Step 1: Upload Images
📥 Place your images in the appropriate directory (e.g., /content/Images/).

Step 2: Set Image Path
🔗 Update the image_path variable in the code to point to your desired image:
image_path = '/content/Images/your_image.jpg'  # Replace with your image filename

Step 3: Generate Descriptions
⚙️ Run the code to generate captions, translate them into Kannada and Hindi, and convert them to audio.

Step 4: Play Audio
🎧 Listen to the generated audio descriptions for a richer understanding of the image features.

## Sample Results
Here are some sample output images and their corresponding descriptions for this project:

### _Description: a black dog and a brown dog playing in a yard_ 

![image](https://github.com/user-attachments/assets/80e2aeac-3b60-4740-96c7-b048509f7be9)

________________________________________________________________________________________________________________________

### _Description: A woman standing on top of a sandy beach._

![image](https://github.com/user-attachments/assets/38defe35-d666-4289-bcf0-a3142b6d94dd)

________________________________________________________________________________________________________________________

### _Description: Two children are flying a kite in a field._

![image](https://github.com/user-attachments/assets/9acb5ea8-0b1a-4b5f-9e25-aea9b0089b39)

________________________________________________________________________________________________________________________
**Feel free to make any modifications to fit your project better! If you need further assistance, please contact at karthikgr1908@gmail.com.**
