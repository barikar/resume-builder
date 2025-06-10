# resume-builder
A mini project built using Streamlit that enables users to create professional resumes and portfolios dynamically. This web app leverages OpenAI’s GPT-3.5 API to auto-generate personalized content and produces a stylized PDF resume using `pdfkit` and HTML/CSS templates.

Project Description: This project is an AI-powered Resume and Portfolio Builder developed as part of Assignment-4. It allows users to fill out their personal, educational, and professional details through a user-friendly form interface. Users can also generate an "About Me" section using GPT-3.5 by simply entering their job title.

Once the form is filled, the app:

* Dynamically creates an HTML resume using user input.
* Displays a **live preview** inside the app.
* Converts the HTML content to a **downloadable PDF resume** with the help of `wkhtmltopdf`.
Input Interface for:
  * Full Name & Job Title
  * Profile Image Upload
  * Contact Information (Phone, Email, LinkedIn, Address)
  * "About Me" (manual or AI-generated)
  * Education (2 entries)
  * Experience (1 entry)
  * Projects (2 entries)
  * Skills (comma-separated)

Tech Stack
* Frontend: Streamlit
* AI Model: OpenAI GPT-3.5
* Templating: Jinja2
* PDF Conversion: pdfkit, wkhtmltopdf
* Languages: Python, HTML, CSS

 How to Use
1. Run the Streamlit app.
2. Enter your OpenAI API key in the sidebar.
3. Fill in your resume details via the form.
4. (Optional) Use AI to generate the "About Me" section.
5. Preview your resume inside the app.
6. Click the Download Resume as PDF link.
