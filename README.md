# Document Classifier with spaCy

## 📌 Description
This project automatically classifies documents into **25 categories** using the [spaCy](https://spacy.io/) library. The model analyzes the text and identifies its type based on predefined keywords.

## 🚀 Technologies Used
- Python 3.x
- spaCy

## 📂 Supported Categories
- Email
- Contract
- News
- Recipe
- Scientific Article
- Programming Code
- Essay
- Report
- Blog Post
- Speech
- Diary
- Poetry
- User Manual
- Letter
- Thesis
- Review
- Advertisement
- Fable
- Comic Book
- Text Message
- Official Statement
- Shopping List
- Movie Script
- Joke

## 📦 Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/document-classifier-spacy.git
   cd document-classifier-spacy
   ```
2. Install dependencies:
   ```bash
   pip install spacy
   python -m spacy download pt_core_news_sm
   ```

## ▶️ How to Use
Run the script and enter a text for classification:
```bash
python classifier.py
```
Type or paste the text when prompted and see the corresponding category.

## 📜 Example Usage
Input:
```
Dear team, I am sending the performance report for the last month as an attachment.
```
Output:
```
The document was classified as: Email
```

## 🤝 Contribution
Feel free to open issues and submit PRs with improvements!

## 📄 License
This project is licensed under the MIT License.
