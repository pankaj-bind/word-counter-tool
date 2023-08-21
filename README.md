# Word Counter Tool

The Word Counter Tool is a simple web application that allows users to analyze and obtain statistics from text input. It provides information about the character count, word count, sentence count, paragraph count, reading time, and readability score of the provided text.

## Features

- Counts the number of characters, words, sentences, and paragraphs in the input text.
- Calculates the estimated reading time based on the assumption of 275 words per minute.
- Determines the readability score of the text using the Flesch Reading Ease formula.
- Displays the top keywords used in the text and their occurrence count.
- Real-time updates: The displayed statistics are updated automatically as you type in the input field.

## Usage

1. Open the Word Counter Tool in a web browser.
2. Enter or paste the text you want to analyze into the text area provided on the page.
3. As you type or modify the text, the tool will automatically update the following statistics in real-time:
   - Character count
   - Word count
   - Sentence count
   - Paragraph count
   - Reading time estimation

4. Click the "Show readability score" button to obtain the readability score of the text based on the Flesch Reading Ease formula. The score is then translated into a readability level ranging from college graduate to elementary school level.

5. The tool will also identify and display the top keywords in the text, excluding common stop words and numbers. The top keywords are presented along with their occurrence count.

## Responsive Design

The Word Counter Tool is designed to be responsive, adapting to different screen sizes. The layout and font sizes are adjusted to provide an optimal user experience on various devices.

## Technology Used

- HTML: The structure of the web page.
- CSS: Styling and responsive design.
- JavaScript: Real-time updates and interactivity.
- Mashape API (optional): The tool can utilize the Readability Metrics API to calculate and display the readability score.

## Installation

1. Clone or download this repository to your local machine.
2. Open the `index.html` file in a web browser to start using the Word Counter Tool.

## Notes

- The tool uses regular expressions to analyze and process the input text.
- The readability score is calculated using the Flesch Reading Ease formula and provides an estimation of the text's difficulty level.

## Credits

This Word Counter Tool was created by [Your Name] and is provided under the [license type] license. Feel free to use and modify the tool according to your needs.

## License

[This project is licensed under the MIT License.]
