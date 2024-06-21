# Markdown to HTML Converter

## Description
This Python application converts Markdown files to HTML format. It supports the conversion of basic Markdown syntax, including bold, italic, and inline code, to their HTML counterparts. The application also includes validation for nested and correct usage of Markdown syntax to ensure the output HTML is as expected.

## Guide Installation

### Prerequisites
- Python 3.x

### Installation
Clone the repository to your local machine:
   ```sh
   git clone https://github.com/heereenveen/mtrpz_1lab
   ```

### Running the Application
To convert a Markdown file to HTML, run the `main.py` script with the input file name as an argument. Optionally, you can specify an output file name to save the converted HTML:

```sh
python main.py input_file.md --out output_file.html
```

If no output file is specified, the program will print the converted HTML to standard output.

## User Guide

### Supported Markdown Features
- **Bold**: Wrap your text with `**` to make it bold. For example, `**bold text**` converts to `<strong>bold text</strong>`.
- *Italic*: Use `_` to italicize your text. For instance, `_italic text_` becomes `<em>italic text</em>`.
- `Inline Code`: To format text as inline code, enclose it with backticks (`` ` ``). For example, `` `code` `` turns into `<code>code</code>`.

### Validation
The application checks for incorrect nesting and unmatched symbols to ensure the Markdown is correctly formed before conversion.

### Error Handling
If there are any issues with the Markdown syntax or if the input file cannot be found, the application will provide an error message and terminate the execution to prevent incorrect HTML conversion.

## Revert-commit
The [following link](https://github.com/anasteishat/MTRPZ_labs/commit/41c0ba4e399ab98596a5f912d8758d33eb4df18b).

## Failure commit for CI tests:
The [following link](https://github.com/anasteishat/MTRPZ_labs/commit/301e86466d6de8a19f940b99365b2e3e0a9251a6).

## Conclusions about Unit-Tests:
I can confidently say that the time spent writing unit tests was a very worthwhile investment for me. After all, writing unit tests allows you to ensure high code quality and detect errors at the early stages of development, which greatly facilitates the work of the developer.