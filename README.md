# EmojiArtGenerator

This is a simple C++ program that takes an input image and an emoji image to create a new image where the input image consist of emoji images.

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
        - `<input-image>`: The path to the input image which will consist of emoji images.
        - `<emoji-image>`: The path to the emoji image that will be used for overlaying.
        - `<emoji-size>` (optional): The size of the emoji (default is 7x7).
        - `<background-color>` (optional): The background color in RGB format (default is white) or
            one of these (red, blue, green, yellow, black, white).
7. Get the output in output.(input-image's extension) file.

#### Use bigger images for input-images and smaller images for emoji-images to get better results.

## Examples

### Example 1

The original image`

<img src="images/girl.jpg" alt="Example 1" width="400">

The emoji image`

![heartEmoji](https://github.com/SamvelMakaryan/EmojiArtGenerator/assets/123547362/4640052e-cfac-4215-8d09-409514edda71)

The result`

![Screenshot from 2023-07-26 00-53-30](https://github.com/SamvelMakaryan/EmojiArtGenerator/assets/123547362/987ab5f6-14f6-45f8-b8e4-790104b595cf)

### Example 2

The original image`

![Lion](https://github.com/SamvelMakaryan/EmojiArtGenerator/assets/123547362/c3b7ee8f-264d-4819-9ff0-6a8ce8654f5a)

The emoji image`

![lionEmoji](https://github.com/SamvelMakaryan/EmojiArtGenerator/assets/123547362/a9c7c00b-cc4f-44cf-9619-5d742725a1db)

The result`

![Screenshot from 2023-07-26 00-51-27](https://github.com/SamvelMakaryan/EmojiArtGenerator/assets/123547362/069908de-05dd-4068-87b6-eec294508ee5)

