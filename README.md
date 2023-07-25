# EmojiArtGenerator

This is a simple C++ program that takes an input image and an emoji image to create a new image where the emoji is overlaid on the input image.

## Requirements

- C++ compiler (supporting C++11 standard)
- OpenCV library (version 2 or 3)
- CMake (can be compiled directly)

## Usage

1. Clone the repository.
2. Move to EmojiArtGenerator directory.
3. Create build directory and move there.
4. Give path to cmake file.
5. Build program.
6. Run the program.
    - ./EmojiArt `<input-image>` `<emoji-image>` `<emoji-size>` `<background-color>`
        - `<input-image>`: The path to the input image on which the emoji will be overlaid.
        - `<emoji-image>`: The path to the emoji image that will be used for overlaying.
        - `<emoji-size>` (optional): The size of the emoji (default is 7x7).
        - `<background-color>` (optional): The background color in RGB format (default is white) or
            one of these (red, blue, green, yellow, black, white).
7. Get the output in output.(input-image's extension) file.

#### Use bigger images for input-images and smaller images for emoji-images to get better results.

### Examples


