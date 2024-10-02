# QuizMaster Pro

Transform your study sessions with QuizMaster Pro! Input a topic or upload relevant materials, and our intelligent AI will generate customized quizzes designed to reinforce your knowledge and skills. Ideal for self-assessment or collaborative study groups, QuizMaster Pro makes learning dynamic and enjoyable. Challenge yourself with a variety of question formats, track your progress, and identify areas for improvement—all while making studying a fun and interactive experience!

# QuickCheat Creator

Supercharge your exam preparation with QuickCheat Creator, your go-to tool for generating instant cheat sheets! Simply enter the topic name, and watch as our intelligent AI crafts a concise and organized summary of key concepts and essential information tailored to that subject. No need for extensive study materials—just a few clicks, and you’ll have a personalized cheat sheet at your fingertips. Perfect for quick reviews and last-minute studying, QuickCheat Creator helps you maximize your study efficiency and approach your exams with confidence!

## Features

- Generate quizzes instantly based on user-defined topics or uploaded documents (PDF/DOCX).
- Supports various question types: 
  - Multiple Choice Questions (MCQs)
  - True/False questions
  - Fill-in-the-Blanks
- Displays generated quizzes and allows users to answer questions.
- Calculates and displays the user's score after quiz submission.
- Simple and user-friendly interface.

## Requirements

Before running the application, ensure you have the following installed:

- Python 3.7 or higher
- `pip` (Python package installer)

### Required Python Packages

The required packages are listed in `requirements.txt`. 

## Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd <repository-folder>

2. Create a virtual environment (recommended):

   python -m venv venv
   source venv/bin/activate  

   On Windows use  `venv\Scripts\activate`

3. Install the required packages:

   pip install -r requirements.txt

4. Set up your environment variables. Create a .env file in the root directory and add your Google API key:
   
   GOOGLE_API_KEY=<your_google_api_key>

5. Running the Application
   
   To run the application, execute the following command in your terminal:

   streamlit run app.py

   This will start the Streamlit server, and you can access the application in your web browser at http://localhost:8501.

## Usage

1. Enter Topic: Type a specific topic related to the quiz you want to generate.
2. Upload Document: Optionally, you can upload a PDF or DOCX document from which the topic will be extracted.
3. Select Question Type: Choose the preferred type of questions you want in the quiz.
4. Generate Quiz: Click the "Generate Quiz" button to create your quiz.

