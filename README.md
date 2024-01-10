# Document Scanner (OCR + NER)

Welocome to Document Scanner application!
Hope, you will find it useful for quick extraction of information from different sources (business cards, letters, etc). Created using such scientific approaches like,
* Computer Vision
* Natural Language Processing
Built with sequencing: Load image -> Preprocess with CV -> Extract text blocks with OCR -> NER with NLP

Python Libraries used in Computer Vision Module.
- OpenCV
- Numpy
- Pytesseract
Python Libraries used in Natural Language Processing

SpaCy
- Pandas
- Regular Expression
- String
Two major technologies were combined to develop the project.

Stage 1: Setup the project by doing the necessary installations and requirements.

Install Python
Install Dependencies
Create VEnv
Stage 2: Data preparation stage. Extract text from images using Pytesseract and also do necessary cleaning.

Gather Images
Overview on Pytesseract
Extract Text from all Image
Clean and Prepare text
Stage 3: Labeling NER data using BIO tagging.

Manually Labeling with BIO technique
B - Beginning
I - Inside
O - Outside
Stage 4: Splitting to a train/test sets, converting into a SpaCy format.

Prepare Training Data for Spacy
Convert data into spacy format
Stage 5: Train NER model with specified Spacy's best practicies.

Configuring NER Model
Train the model
Train the model
Stage 6: Perform with image preprocessing, text extraction, data parsing, entities predictions.

Load Model
Render and Serve with Displacy
Draw Bounding Box on Image
Parse Entitles from Text
Finally, gathered it all together and created a document scanner app.
