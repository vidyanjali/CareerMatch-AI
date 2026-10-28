# CareerMatch-AI
**An explainable resume and internship matching web application**

🔗 **Live Demo:** https://career-feathered-match-pilot.base44.app/

## About the Project

CareerMatch AI helps college students understand how their resumes align with internship opportunities. Users can provide a resume and a job description to receive an estimated match score, see relevant skills, identify requirements not found in their resume, and get suggestions for improving their resumes.

The goal is to help students understand skill gaps and prepare more effectively for internship applications.
<img width="1514" height="748" alt="image" src="https://github.com/user-attachments/assets/98e651e0-490e-4f93-bb14-26fe6154ece5" />

## Key Features

- **Resume Input:** Upload a PDF, DOCX, or TXT resume, or paste resume text.
- **Job Description Analysis:** Paste a job description or try importing it from a URL.
- **Match Score:** Estimate resume alignment using weighted required and preferred skills.
- **Skill Analysis:** Identify matched skills, missing keywords, and possible matches that need review.
- **Resume Evidence:** Show relevant statements from the resume to explain skill matches.
- **Personalized Learning Roadmap:** Provide learning steps and practice projects based on the selected experience level.
- **Resume Improvement Suggestions:** Identify ways to make existing resume bullet points clearer.
- **PDF Report:** Generate a report that users can save and review.
- **Start Over:** Clear the current analysis and begin again.

## How It Works

1. Upload a resume or paste its text.
2. Paste the internship or job description.
3. Select an experience level.
4. Review the extracted requirements and skill matches.
5. Explore the match score, supporting evidence, and missing requirements.
6. Follow the learning roadmap and review resume improvement suggestions.
7. Download the PDF report.
<img width="1120" height="482" alt="image" src="https://github.com/user-attachments/assets/698dcf97-0df2-4144-85a8-a9beaddef264" />
<img width="1143" height="789" alt="image" src="https://github.com/user-attachments/assets/bbbde496-5f69-4057-a4c5-6ec0f60aa5a9" />
<img width="1184" height="907" alt="image" src="https://github.com/user-attachments/assets/b6c658b9-75ef-42a6-85a4-ee3981ee6215" />
<img width="898" height="811" alt="image" src="https://github.com/user-attachments/assets/96149a70-7275-4050-b850-e665d713218d" />

## Scoring Method

The application assigns:

- **2 points** to each matched required skill.
- **1 point** to each matched preferred skill.

The match score is calculated by dividing matched weighted points by total weighted points and multiplying by 100.

The score is an estimate of resume alignment. It does not predict whether an applicant will receive an interview or job offer.

<img width="1357" height="877" alt="image" src="https://github.com/user-attachments/assets/d5e092f7-5ff2-4da1-a346-10b61edd27d4" />
<img width="1228" height="813" alt="image" src="https://github.com/user-attachments/assets/9ce5e4d1-ed67-443d-868f-d666fecf988d" />

## Tools and Approach

- **Base44:** AI-assisted app development and publishing.
- **Rule-based skill matching:** A curated skill dictionary and keyword rules.
- **Weighted scoring:** A transparent method for comparing required and preferred skills.
- **PDF reporting:** A downloadable summary of the analysis.

## Limitations

- Keyword matching may miss skills described using different words.
- A keyword mention does not necessarily prove practical experience.
- Scanned or image-only PDFs may not provide extractable text.
- Job description URL imports may fail, so pasting the text is an alternative.
- Results should be reviewed by the user and should not replace human judgment.

## Privacy Note

Please review the live application's privacy behavior before uploading sensitive resumes. Do not assume that information is processed locally or never transmitted unless this has been technically verified.

## Project Status

The application is published and undergoing feature testing. Further improvements may be made based on testing and feedback.

## Live Application

Try CareerMatch AI here:

https://career-feathered-match-pilot.base44.app/

## AI Assistance and Development Process

I used OpenAI (ChatGPT) to help brainstorm features, refine prompts, explore design ideas, and plan the development of CareerMatch AI. I used these ideas with Base44, an AI-powered app-building platform, to create and publish the web application.

This process helped me organize the project, think through the user experience, plan the resume-matching features, and improve the application through testing and feedback.

OpenAI was used as a development and brainstorming assistant, while Base44 was used to build and publish the application. I reviewed and tested the generated application to check its features and usability.
