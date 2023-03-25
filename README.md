# Image-Text-Summarization-using-Pegasus-xsum.
Following steps arebeing followed in this project
1- Using PIL library I loaded image of a notice downloaded from google.
2- Text from the image was extraxcted using OCR tool of python called Pytesseract.
3- After extracting the text was stord in a variable.
4- In the next step I downloaded pegasus xsum pretrained model and created tokens of the text that was extracted.
5- Those tokens were used to create the summary of the text.
6- Summary tokens were decoded to get the text format of the summary.
