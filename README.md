# CoverLetterPersonalizer
A simple application to customize your cover letter template with today's date, the company name, and position title. Also features a GPT-3.5-Turbo call for a personalized line. 

Please see the template.docx file for an example of how to format your template. When you run the script, you'll be prompted to enter the company name and position title you're applying to. The script will then replace the appropriate placeholders (<TODAY_DATE>, <COMPANY_NAME>, <POSITION_TITLE>, and <PERSONALIZED_LINE>) in the template and generate a new .docx file. Save yourself some time by modifying the output_filename variable on Line 43 to your first name and last name instead of the generic placeholder that is there currently.

You'll need to pip the following packages first on your device or IDE:
  - "pip install python-docx"
  - "pip install openai"

Example of an output for the AI generated personalized line, where the company is 6sense and the position is Product Manager: "I'm truly thrilled about joining 6sense as a Product Manager. Their innovative solutions combining AI and business resonate with my passion for tech and problem-solving. The chance to contribute to their mission of transforming how businesses understand customers is beyond exciting!"
