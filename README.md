## Document Scanner (OCR + NER)

Welcome to the Document Scanner application! This tool is designed to quickly extract information from various sources, such as business cards and letters. It was created using the following scientific approaches:

- **Computer Vision**
- **Natural Language Processing**

The application is built with the following sequencing:

1. Load image
2. Preprocess with Computer Vision
3. Extract text blocks with OCR
4. Perform NER with NLP

### Python Libraries

The following Python libraries are used in the Computer Vision module:

- **OpenCV**
- **Numpy**
- **Pytesseract**

And in the Natural Language Processing module:

- **SpaCy**
- **Pandas**
- **Regular Expression**
- **String**

### Stages

The project involves six stages:

**Stage 1: Setup**

1. Install Python
2. Install Dependencies
3. Create VEnv

**Stage 2: Data Preparation**

1. Gather Images
2. Overview on Pytesseract
3. Extract Text from all Images
4. Clean and Prepare text

**Stage 3: Labeling NER Data**

1. Manually Labeling with BIO technique
2. B - Beginning
3. I - Inside
4. O - Outside

**Stage 4: Splitting to Train/Test Sets and Converting to SpaCy Format**

1. Prepare Training Data for Spacy
2. Convert data into spacy format

**Stage 5: Train NER Model**

1. Configure NER Model
2. Train the model

**Stage 6: Perform with Image Preprocessing, Text Extraction, Data Parsing, and Entities Predictions**

1. Load Model
2. Render and Serve with Displacy
3. Draw Bounding Box on Image
4. Parse Entities from Text

Finally, all these stages were gathered together to create a document scanner application.
