# Picture_Processing

## Description:

This project contains a set of simple image-processing operations written in C, created for educational purposes.
It demonstrates manual memory management, file I/O operations, and pixel-level image transformations without using external libraries.
This code doesn't follow modern coding standards.
The program works with images in the `.pgm` (Portable GrayMap) format.

## How to run:
1. Clone the repository:<br>
  `git clone <repo_url>`
2. Navigate to the project folder:<br>
  `cd Picture_Processing`
3. Compile the program:<br>
  `gcc Project2_Image_processing.c -o Project2_Image_processing2.exe `
4. Run the executable:<br>
  `./Project2_Image_processing.exe `

## Usage

After running the executable, you will see a menu:

1. **Load the picture** – load a `.pgm` file into memory (the file `.pgm` must be in the same directory as the executable).
2. **Save the picture** – save the current image in memory to a `.pgm` file.
3. **Release the picture's memory** – free the memory used by the loaded image.
4. **Rotate the picture** – rotate the image by 90 degrees.
5. **Add noise** – apply salt-and-pepper noise to the image.
6. **Make negative** – invert the image colors.
7. **Filter** – apply a median filter to reduce noise.
8. **Save to database** – store a copy of the current image in memory.
9. **Show database** – list all images stored in memory.
10. **Histogram** – generate a `.csv` file with histogram data for the current image.
11. **Select an image from the database** – set a stored image as the current image for processing.
0. **Exit** – quit the program.

The program guides you and should not lead you to a dead end.

## Screenshots:

<img width="457" height="355" alt="obraz" src="https://github.com/user-attachments/assets/ee27788e-1a19-4f1b-95b6-e4750f8a2df8" />

<img width="357" height="459" alt="obraz" src="https://github.com/user-attachments/assets/4e87deeb-a898-48d4-94f0-9229807e603c" />

<img width="452" height="358" alt="obraz" src="https://github.com/user-attachments/assets/fe45ece4-c678-4023-bc3c-609ed6fbb95b" />

<img width="457" height="358" alt="obraz" src="https://github.com/user-attachments/assets/b4b01087-80ab-4347-a6bb-8ceceb01319e" />




