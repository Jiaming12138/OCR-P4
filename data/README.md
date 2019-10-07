# Project: OCR (Optical Character Recognition) 

### Data folder

The data directory contains data used in the analysis. This is treated as read only; 

In this project, there are three subfolders -- 

Firstly, ground_truth and tesseract. Each folder contains 100 text files with same file names correspondingly.

And there are another folder called ground_truth_trimmed, which contains preprocessed ground truth. During the preprocess phase, rows with characters that can’t be recognized in Tesseract are deleted; Then delete rows in ground truth and tesseract which character number don’t match.

'ground_truth_trimmed' is the input in the following process.

