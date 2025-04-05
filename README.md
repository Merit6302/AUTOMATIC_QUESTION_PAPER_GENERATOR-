                                         📝 Automatic Question Paper Generator (Mini Project)



📌 Project Overview
This mini project is designed to automatically generate a question paper based on a dataset of categorized questions (easy, medium, hard) and chapters. It helps teachers and institutions reduce manual effort in question paper creation by dynamically generating a new and unique paper every time.
This project is especially useful for schools and coaching institutions that frequently need to prepare model papers, tests, or revision assessments.



💡 Key Features
🏫 Custom School Branding: Each paper includes the school name  and fields for student name, class (X), and section.
🔢 Chapter-based Filtering: Select specific chapters from which to generate questions.
🔄 Randomization: Every question paper generated is different, ensuring uniqueness.
🎯 Difficulty Levels:
Section A: 5 Easy Questions
Section B: 5 Medium Questions
Section C: 3 Difficult Questions
✅ CSV-based Input: Questions are loaded from a structured CSV file.
🖨️ Printable Output: Question paper is generated as a clean, formatted text or PDF file (optional).


🗂️ Dataset Format (question_bank.csv)
Chapter should be a number (e.g., 1, 2, 3...)


⚙️ How It Works
Load questions from question_bank.csv.
Ask user:
From which chapter numbers questions should be selected?
Filter questions based on difficulty and chapter.
Randomly select:
5 easy questions (Section A)
5 medium questions (Section B)
3 hard questions (Section C)
Generate and print a formatted question paper including:
School name
Name and section placeholders
Questions under Sections A, B, and C


🖥️ Technologies Used
Python
Pandas
Random
File handling and string formatting
Optional: PDF generation using fpdf or reportlab

