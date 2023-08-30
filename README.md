# Text Fetch - Image Text Extraction and Translation

Text Fetch is a Python project that uses various technologies to extract text from images and provide translation capabilities.

## Features

- Text extraction from images using Pytesseract OCR.
- Image preprocessing with Keras and Tensorflow.
- Translation of extracted text using GoogleTrans API.
- Command-line interface for user interaction.

## Technologies Used

- Python
- Pytesseract
- Keras
- Tensorflow
- GoogleTrans

## Installation

```shell
git clone https://github.com/yourusername/text-fetch.git
cd text-fetch
pip install -r requirements.txt
# Download and install Tesseract OCR: https://github.com/tesseract-ocr/tesseract
python text_fetch.py
```


## Usage
```
# Place the images in the 'images' folder.
# Run the program:
python text_fetch.py
# Follow the prompts to select an image and target language for translation.
# The program extracts text, enhances it, translates it, and displays the results.
```
## Example

```shell
$ python text_fetch.py
Enter the filename of the image (from the 'images' folder): example_image.jpg
Select target language for translation (e.g., 'en' for English): es
```
## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your improvements.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

For inquiries, please contact rishabh.jaiswal10.rj@gmail.com


