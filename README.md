                                                          Resume Builder App

                                                       
This is a vanilla JavaScript-based Resume Builder application designed to help users create professional resumes quickly and efficiently. The app features a dynamic form interface powered by jQuery Repeater, allowing users to easily add and customize their resume sections, such as projects, education, and experiences. Upon completion, the app generates a PDF of the resume.

Key Features
Dynamic Form Creation: The app uses jQuery Repeater to allow users to dynamically add, edit, and delete sections of their resumes, such as projects, education, and work experience.

Custom Form Validation: Implemented custom validation functions to ensure the data entered in the form is accurate and consistent. The validation checks for text, email, phone numbers, percentages, and CGPA, with appropriate error messages displayed to guide the user.

Regular Expressions for Validation: Utilized regular expressions for robust validation of input fields, including text fields, email addresses, phone numbers, and more.

Dynamic CSS Styling: Applied dynamic CSS styles to elements injected via JavaScript, ensuring the generated resume is visually appealing. Special formatting is used for list items like achievements and skills, including bullet points and colon separators.

PDF Generation: Upon form submission, the app dynamically generates a PDF of the resume, which users can download.

Built With
JavaScript
jQuery
jQuery Repeater - For dynamic form creation
HTML/CSS

Usage
Fill out the various sections of the form, such as personal details, education, experience, projects, and skills.
Use the "Add" button to dynamically add more entries to sections like projects and experience.
Validate your inputs as you go—errors will be highlighted.
Once all sections are complete, click the "Generate Resume" button to preview your resume.
Download the generated PDF resume.

Acknowledgements
jQuery Repeater - For making dynamic form handling easy.
jsPDF - For generating PDF files from JavaScript.
