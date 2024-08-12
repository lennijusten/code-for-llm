# Code Library Summarizer

## Overview
This Python script generates a text representation of code libraries, making it easy to upload as context to various LLM applications. It creates a summary of your project's architecture and includes the full content of specified files in a single text file.

## Usage
Run the script from the command line:
```
python summarize_code.py path/to/files_list.txt [-o output_file.txt]
```
- `files_list.txt`: A text file containing paths to the files you want to include, one per line
- `-o output_file.txt`: (Optional) Specify the output file path. If not provided, the script will generate a timestamped file in your Downloads folder.
