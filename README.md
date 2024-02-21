# ImageMark

## Requirements:
- Ollama
- pandas
- PIL

## Usage:
1. Install the requirements:
2. Update the path of the image folder in the script as per your requirement.

## Description:
ImageMark, an image annotation app leveraging Ollama and LLava-13b. 

Follow the steps below to annotate images with ease:

## Steps:
1. ImageMark takes the list of files from the specified folder.
2. It loads each file and converts it into bytes using BytesIO.
3. The application then sends the file to LLava-13b-v1.6, with the option to choose parameter sizes (7B, 13B, or 34B) via Ollama for semantic segmentation.
4. Results are saved into a pandas DataFrame for easy management and analysis.
5. Finally, ImageMark saves the DataFrame to a CSV file. If the CSV file doesn't exist, it creates a new one.
