===========================================================
AI-Based Phishing Detection for Smart City
Client Setup & Run Instructions
===========================================================

Thank you for using this project. Follow these steps to set up and run the phishing detection notebook on your PC.

-----------------------------------------------------------
1. Install Python (if not already installed)
-----------------------------------------------------------
- Go to https://www.python.org/downloads/
- Download Python 3.8 or higher (e.g., 3.10, 3.11, 3.12)
- During installation, CHECK the box "Add Python to PATH"
- Click "Install Now"

-----------------------------------------------------------
2. Install Required Libraries
-----------------------------------------------------------
Open Command Prompt (Windows) or Terminal (Mac/Linux) and type:

    pip install -r requirements.txt

If the above command gives an error, manually install each library:

    pip install pandas numpy scikit-learn matplotlib seaborn joblib notebook

Wait for all installations to finish (1-2 minutes).

-----------------------------------------------------------
3. Prepare Project Folder
-----------------------------------------------------------
- Create a folder on your Desktop (e.g., "Phishing_Detection_Project")
- Place the following files inside this folder:
    * Spam_Classifier_Smart_City.ipynb   (the notebook)
    * SMSSpamCollection                  (dataset file)
    * requirements.txt                   (this list)
    * README.txt                         (this file)

-----------------------------------------------------------
4. Launch Jupyter Notebook
-----------------------------------------------------------
- Open Command Prompt / Terminal
- Navigate to your project folder. Example (Windows):
    cd Desktop\Phishing_Detection_Project
- Then type:
    jupyter notebook
- Your web browser will open automatically with Jupyter dashboard.

-----------------------------------------------------------
5. Open and Run the Notebook
-----------------------------------------------------------
- In the Jupyter file list, click on "Spam_Classifier_Smart_City.ipynb"
- In the notebook menu, click Kernel -> Restart & Run All
- All cells will execute automatically. Outputs (metrics, plots, test results) will appear.

-----------------------------------------------------------
6. Verify Results
-----------------------------------------------------------
You should see:
- Accuracy: 98.12%
- Confusion matrix heatmap
- Custom email test: 4/4 spam caught, 1/4 ham correctly identified

-----------------------------------------------------------
7. Test Your Own Emails (Optional)
-----------------------------------------------------------
- Scroll down to Cell 14 (the custom email test)
- Edit the list of emails (add, remove, or change text)
- Press Shift+Enter to re-run the cell
- See predictions for your new emails

-----------------------------------------------------------
Troubleshooting
-----------------------------------------------------------
Problem: 'pip' is not recognized
Solution: Reinstall Python and make sure "Add to PATH" is checked.

Problem: FileNotFoundError: SMSSpamCollection
Solution: Make sure the dataset file is in the same folder as the notebook.

Problem: ModuleNotFoundError: No module named 'sklearn'
Solution: Run "pip install scikit-learn" again.

Problem: Notebook doesn't open in browser
Solution: Manually copy the URL (e.g., http://localhost:8888) from the terminal into your browser.

-----------------------------------------------------------
For any other issues, contact the developer with the error message.
===========================================================
