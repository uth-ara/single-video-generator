# single-video-generator

Single Video Generator

A minimal command-line tool and notebook implementation for generating short AI-based video clips from text prompts.
The project supports two modes:

Mock mode – creates a simple demo video (text rendered on screen).

Model mode – generates short clips using the open-source
damo-vilab/text-to-video-ms-1.7b text-to-video model.

Features

Text-prompt based video generation
Optional style and camera angle parameters
Duration control (up to 10 seconds)
Lightweight mock mode for testing without a GPU
Full notebook included for reproducibility

How to Run in Google Colab

Open videogen.ipynb
Run all cells
Use the CLI cell at the bottom to generate a clip
Example:
!python main.py --prompt "A kite flying in the wind" --cogvideo

Author

Uthara Krishna
