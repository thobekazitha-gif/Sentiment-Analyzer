# Sentiment Analysis Dashboard

## Group Project (Logic League)

**Program:** Tech Career Accelerator (CAPACITI)  
**Project Type:** Interactive NLP Dashboard  
**Sector/Application:** Text Analytics / Customer Insights  
**Team Size:** Individual / Group Project  

🔗 **Deployed Application Link:**  
[Sentiment Analysis Dashboard](https://c0qai4ygity3.trickle.host/)

---

## Project Overview

The **Sentiment Analysis Dashboard** is an interactive system designed to analyze the emotional tone of text data. Users can input text directly or upload files to evaluate sentiment across customer reviews, social media posts, or other textual content. The dashboard provides multi-class sentiment classification (positive, negative, neutral), confidence scores, keyword extraction, and comparative analysis between multiple texts or sources.

---

## Objectives

- Enable sentiment classification for individual and batch text data  
- Provide confidence scoring and highlight key sentiment-driving terms  
- Visualize sentiment distribution and comparative analysis  
- Explain classification decisions to help users understand why a text received a specific sentiment  
- Export analysis results in multiple formats (CSV, JSON, PDF)  

---

## Features

### Core Features
- **Text Input:** Manual entry or file upload  
- **Multi-class Sentiment Analysis:** Positive, negative, neutral  
- **Confidence Scoring:** Shows probability of each classification  
- **Keyword Extraction:** Highlights words driving sentiment  
- **Batch Processing:** Analyze multiple texts efficiently  
- **Comparative Analysis:** Compare sentiment across different data sources  
- **Interactive Visualizations:** Graphs showing sentiment distribution  
- **Explanations:** Highlights reasons behind sentiment classification  
- **Export Options:** CSV, JSON, PDF  

---

## Technical Specifications

- **NLP API Integration:** Hugging Face, AWS Comprehend, or equivalent  
- **Frontend:** Streamlit or Gradio for responsive, interactive web interface  
- **Error Handling:** Detects API failures and invalid inputs  
- **Batch Processing:** Efficient handling of multiple texts  
- **Documentation:** Clear notes on API limitations, confidence thresholds, and implementation challenges  

---

## Implementation Details

### User Flow
1. User inputs text manually or uploads a text file  
2. AI classifies sentiment and calculates confidence scores  
3. Dashboard displays keyword highlights and sentiment visualizations  
4. User can compare multiple datasets and export results  
5. Explanations show which terms influenced sentiment classification  

### Technical Stack
- **Frontend:** Streamlit / Gradio  
- **Backend/AI:** NLP API (Hugging Face, AWS Comprehend, etc.)  
- **Storage:** Temporary local storage for uploaded data  
- **Visualization:** Matplotlib, Plotly, or built-in Streamlit/Gradio charts  

---

## Deliverables

- **GitHub Repository:** Complete source code with setup instructions  
- **Deployed Application:** [Sentiment Analysis Dashboard](https://c0qai4ygity3.trickle.host/)  
- **Accuracy Report:**  
  - Analysis of at least 50 sample texts  
  - Confusion matrix and performance metrics  
  - Discussion of API limitations (300-500 words)  
- **Demo Video:** 3-minute walkthrough highlighting key features  
- **Documentation:**  
  - API selection rationale  
  - Implementation challenges  
  - User guide with examples  

---

## Error Handling & Validation

- Validates text input and file uploads  
- Handles API errors and rate limits gracefully  
- Alerts users for invalid or empty text submissions  
- Ensures exported data formats are correctly generated  

---

## Evaluation Alignment

- Functionality and accuracy of sentiment analysis  
- Quality and clarity of visualizations and UI  
- Code organization and documentation completeness  
- Technical depth in accuracy analysis and comparative reporting  
- Innovation beyond basic requirements (e.g., keyword extraction, explanations)  

---

## Conclusion

The **Sentiment Analysis Dashboard** provides a robust tool for analyzing text sentiment with visual insights and explanations. It allows users to gain a deeper understanding of emotional tone in textual data while providing batch processing, export options, and multi-class analysis in an interactive, user-friendly interface.
