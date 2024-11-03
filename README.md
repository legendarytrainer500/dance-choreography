# Dance Choreography App

## Overview

The Dance Choreography App is a Python application designed to help users create and organize choreography for their dance routines. Users can input dance moves and lyrics, associate moves with specific lyrics, and save the choreography to a Word document in a structured table format. The app provides a user-friendly interface using PySimpleGUI.

## Features

- **Add Dance Moves**: Users can paste multiple dance moves into the app, each separated by a new line.
- **Input Lyrics**: Users can paste song lyrics, with each line corresponding to a lyric.
- **Choreograph Lyrics**: Users can drag and drop dance moves to corresponding lyrics, assigning up to five moves per lyric.
- **Save Choreography**: Save the choreographed lyrics and their associated dance moves to a Word document. The document contains a table format with lyrics in one column and corresponding dance moves in another.
- **Dynamic Interface**: The app features tabs for adding moves, inputting lyrics, choreographing, and saving choreography, making it easy to navigate.

## Requirements

To run the Dance Choreography App, you need the following:

- Python 3.x
- Required Python packages:
  - PySimpleGUI
  - python-docx

You can install the required packages using pip:

```bash
pip install PySimpleGUI python-docx
