README: How to Run Your Kushal Support AI Flask Chatbot

1. Requirements
---------------
- Python 3 installed on your computer
- pip (Python package manager)
- Internet connection

2. Install Required Packages
---------------------------
Open your command prompt or terminal and run:

    pip install Flask nltk

3. Download NLTK Data
---------------------
Start Python in your terminal and run:

    python
    >>> import nltk
    >>> nltk.download('punkt')
    >>> nltk.download('averaged_perceptron_tagger')
    >>> exit()

4. Prepare Your Project Folder
-----------------------------
Put these files together in one folder:
    - app.py        (the chatbot backend)
    - index.html    (the frontend chat UI)

5. Run the Chatbot
------------------
Open your command prompt or terminal in your project folder and run:

    python app.py

6. Access the Chatbot
---------------------
Open your web browser and go to:

    http://127.0.0.1:5000

7. Chat with Kushal Support AI!
-------------------------------
Type your questions and enjoy your local support chatbot.

8. Deploy Online (Optional)
--------------------------
If you want to share your bot online for free, consider PythonAnywhere or Replit.
- See setup steps in the tips provided earlier.

Troubleshooting:
---------------
- If you encounter an error about missing NLTK data, repeat step 3.
- If Flask errors, check you installed all requirements.
- For help: Paste your error message when asking questions!
