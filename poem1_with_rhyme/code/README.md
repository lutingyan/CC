
# Poetry Image Collection Generator

This Jupyter Notebook is designed to generate a collection of poetry images and combine them into a single PDF file with a custom cover image.

## Features

- **Custom Cover Creation**: A maple leaf-themed cover image with a title is generated using `matplotlib`.
- **Image Loading**: Loads five poetry images.
- **PDF Generation**: Combines the poetry images, along with the custom cover, into a single PDF file.

## Prerequisites


Make sure the following Python packages are installed:

- Python：3.10
- `matplotlib`
- `PIL` (Python Imaging Library)
- `numpy`
- `diffusers` (can be installed using `!pip install diffusers`)



## Usage

1. Clone or download the notebook.
2. Prepare your poetry images and ensure they are in the correct paths (as specified in the code).
3. Run the notebook to generate a custom cover image and merge the poetry images into a PDF file.

### Steps in the Notebook:

1. **Custom Cover Creation**:
   - The notebook creates a background and draws a maple leaf shape with a poem title in the center.
   - The cover is saved as `maple_poetry_cover_manual.jpg`.

2. **Image Loading**:
   - The five poetry images are loaded, and the cover image is resized to match the dimensions of the poems.
   - The cover is inserted at the start of the list.

3. **PDF Creation**:
   - The images (cover and poems) are converted to `RGB` format.
   - The images are combined and saved as a PDF file named `poetry_collection.pdf`.

## Output

- The final output is a PDF file named `poetry_collection.pdf`, which contains the custom cover and all the poetry images.

## License

This project is open-source and free to use.

