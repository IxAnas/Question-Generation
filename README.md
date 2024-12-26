# Question Generator

## Version: 1.0

### Author:
Anas Alharbi  

### Submitted To:
Eng. Khaled Al-Ghamdi  

---

## Introduction
**Smart Question Generator** is an innovative open-source application built with Python, designed to simplify the creation of educational questions using Natural Language Processing (NLP) and text analysis techniques. It offers a user-friendly interface that enables educators to create various types of questions, such as:

- Fill in the blanks
- True/False
- Multiple Choice Questions

The application allows customization of the question types and number. Unlike many similar tools, the Smart Question Generator is fully independent, utilizing custom Python code for NLP, eliminating the need for external GPT APIs.

The tool supports multiple file formats, including TXT, PDF, and DOCX, and integrates seamlessly with Learning Management Systems (LMS).

This project is open-source and highly extensible, allowing other developers to contribute and enhance its functionality.

---

## Features
- **Input:** Upload text files in TXT, PDF, or DOCX formats.
- **Control Panel:** Preview text content, select question type and quantity.
- **Output:** Display generated questions and answers within the control panel.
- **Additional Features:** Save results in various formats, clear inputs to reset.

---

## Technical Details

### Languages and Tools Used:
- **Programming Language:** Python  
- **Libraries:**
  - **Tkinter:** For the user interface.
  - **nltk & spaCy:** For text analysis and question generation.
  - **FPDF2:** To support Arabic text in PDF files.
  - **python-docx:** To extract text from Word files.

### Development Environment:
- Visual Studio Code

### Workflow:
1. **File Upload:** The user uploads a text file through the application interface.
2. **Content Analysis:** Text is automatically analyzed to extract key ideas.
3. **Question Generation:** Based on user preferences, questions are generated dynamically.
4. **Result Display:** Generated questions and answers are displayed in the interface.
5. **Additional Options:** Save the results in various formats or clear input for fresh analysis.

---

## Acknowledgments
I extend my deepest gratitude to **Eng. Khaled Al-Ghamdi** for his invaluable guidance and support throughout this project. Special thanks to my family and colleagues for their encouragement and support.

---

## License

**Smart Question Generator**  

This project is licensed under the **MIT License**. See the `LICENSE` file for more details.

---

## Contributing

Since this project is open-source, contributions are welcome! Feel free to fork the repository, make improvements, and submit pull requests. Any contributions that improve the functionality, usability, or performance of the Smart Question Generator are greatly appreciated.
