**ATS Resume Expert: Gemini Pro-Powered Resume Analysis**

This Streamlit application leverages the power of Google's Gemini Pro model (with vision capabilities) to help you optimize your resume for Applicant Tracking Systems (ATS).  ATS systems are widely used by companies to filter resumes, and this tool provides insights to increase your chances of getting noticed.

**Features**

* **Resume Evaluation:** Get a professional assessment of your resume's strengths and weaknesses compared to a specific job description.
* **ATS Match Score:** Receive a percentage match score indicating how well your resume aligns with the job requirements based on ATS keywords.
* **Actionable Feedback:** Identify missing keywords and areas where your resume could be improved for better ATS performance.

**How It Works**

1. **Paste Job Description:**  Provide the job description you're applying for.
2. **Upload Resume (PDF):** Upload your resume in PDF format.
3. **Click "Tell Me About the Resume":** Get a detailed evaluation of your resume's fit for the role.
4. **Click "Percentage match":** Receive an ATS match score, missing keywords, and final thoughts on your resume.

**Getting Started**

1. **Prerequisites:**
   * Python (3.7 or higher)
   * Google Cloud project with Gemini Pro access
   * `pdf2image` library (install with `pip install pdf2image`)
   * `google-generativeai` library (install with `pip install google-generativeai`)
2. **Installation:**
   * Clone this repository.
   * Set up your `.env` file with your Google API key.
   * Install required packages: `pip install -r requirements.txt` 
3. **Run the App:**
   * `streamlit run app.py`

**Important Note:**

* Your resume and job description data are only used for analysis within this application and are not stored or shared elsewhere. 
* Please review the generated feedback critically. While Gemini Pro is powerful, it's still an AI model and may not perfectly understand all nuances of every job description.


