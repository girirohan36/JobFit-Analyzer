# **ResumeFit: AI-Powered Job Fit Analysis**

**ResumeFit** is a Streamlit-based web application that leverages **Google's Gemini AI** to assist in resume analysis and evaluation. This tool helps recruiters, hiring managers, and job seekers to analyze resumes against specific job descriptions, identify key strengths and weaknesses, and extract critical information such as technical skills, soft skills, and education details.

![image](https://github.com/user-attachments/assets/6301ad0e-6da2-41d6-948f-40af798c0f26)


#### **Key Features:**
- **Resume Review**: Evaluates a candidate’s resume against a given job description, providing insights into how well the profile matches the role.
- **Skills Improvisation**: Provides recommendations for enhancing a candidate's skill set and areas for improvement.
- **Keyword Analysis**: Identifies missing keywords from the resume that are essential for the specific job description.
- **Match Percentage**: Calculates the percentage match between the resume and job description, followed by a detailed analysis.
- **Detailed Information Extraction**: Extracts key technical skills, soft skills, education, and experience directly from resumes.

#### **Technologies Used**:
- **Streamlit**: For creating the web application interface.
- **Google Gemini AI**: For AI-driven analysis and resume evaluation.
- **PyMuPDF (fitz)**: To extract text from PDF resumes.
- **PDF2Image**: For converting PDFs to images (if needed).
- **Python-dotenv**: For managing environment variables securely.

#### **How to Use**:
1. **Clone the repository**:
   ```
   git clone https://github.com/girirohan36/JobFit-Analyzer.git
   ```
   
2. **Install dependencies**:
   Ensure you have all required libraries by running:
   ```
   pip install -r requirements.txt
   ```

3. **Set up environment**:
   Add your **Google API key** in a `.env` file:
   ```
   GOOGLE_API_KEY=your_google_api_key_here
   ```

4. **Run the application**:
   Start the app by running:
   ```
   streamlit run app.py
   ```

5. **Upload your resume and job description**:
   - Upload a PDF resume.
   - Enter the job description in the input box.
   - Select the appropriate button (e.g., "Tell Me About the Resume") to analyze the resume.
  
## Challenges Faced
- **Integrating Gemini AI**: Ensuring smooth communication between Streamlit and the Gemini AI model.
- **PDF Text Extraction**: Extracting clean text from varied resume formats using PyMuPDF.
- **Handling Diverse Inputs**: Managing different resume formats and handling complex PDFs.
- **Accuracy of Analysis**: Ensuring AI feedback is relevant and actionable for each resume.


## Future Enhancements
- **Multi-Page Resume Support**: Enable the app to process multi-page resumes, expanding analysis to the entire document.
- **Customizable Feedback**: Allow users to select specific areas for tailored feedback, such as skills or experience.
- **Real-Time Resume Editing**: Integrate a feature for users to edit their resumes based on AI suggestions, streamlining the process.
- **Enhanced Error Handling**: Improve compatibility with various file formats and enhance error handling for a smoother user experience.



