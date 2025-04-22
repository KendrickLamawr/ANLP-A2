
# ANLP Assignment 2 – Rule-Based and Learning-Based Approaches for Stack Overflow Questions Categorization

This repository contains the implementation for Assignment 2 of the Applied Natural Language Processing (ANLP) course. The assignment explores both rule-based and learning-based methods for natural language processing tasks.

## Repository Structure

```
├── Assignment2.ipynb      # Main notebook contains implementations of all tasks given in Assignment 2 requirement
├── data/                  # Directory containing dataset files
│   ├── nlp_questions.csv # Stack Overflow questions dataset
│   ├── nlp_questions.xlsx
│   ├── nlp_questions_unique.csv # Stack Overflow questions dataset (unique questions only)
│   ├── nlp_questions_unique.xlsx
│   ├── ques_ans.xlsx # Stack Overflow questions + answers dataset
│   └── ques_ans_processed.xlsx # CLEANED Stack Overflow questions + answers dataset
├── rule_based/            # List of posts categorised by rule-based NLP methods
├── learning_based/        # List of posts categorised by learning-based NLP methods
├── visualizations/        # Visualization of our dataset (high resolution)
├── wordcloud_data/        # Word clouds generated (high resolution)
├── .ipynb_checkpoints/   
└── README.md
```

## Setup Instructions

1. **Clone the Repository**

   ```bash
   git clone https://github.com/KendrickLamawr/ANLP-A2.git
   cd ANLP-A2
   ```


2. **Create and Activate a Virtual Environment**

   It's recommended to use Python 3.8 or higher.

   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```


3. **Install Dependencies**

   ```bash
   pip install -r requirements.txt
   ```

## Usage

Open the Jupyter notebook to explore the assignment tasks


```bash
jupyter notebook Assignment2.ipynb
```

The notebook is structured to guide you through:

- Data gathering from Stack Exchange API
- Data preprocessing steps 
- WordCloud visualization
- Implementation of rule-based methods
- Development of learning-based models
- Visualization of results and analysis


