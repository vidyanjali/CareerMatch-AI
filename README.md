# CareerMatch-AI
**An explainable resume and internship matching web application**

🔗 **Live Demo:** https://career-feathered-match-pilot.base44.app/

## About the Project

CareerMatch AI helps college students understand how their resumes align with internship opportunities. Users can provide a resume and a job description to receive an estimated match score, see relevant skills, identify requirements not found in their resume, and get suggestions for improving their resumes.

The goal is to help students understand skill gaps and prepare more effectively for internship applications.

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

## Scoring Method

The application assigns:

- **2 points** to each matched required skill.
- **1 point** to each matched preferred skill.

The match score is calculated by dividing matched weighted points by total weighted points and multiplying by 100.

The score is an estimate of resume alignment. It does not predict whether an applicant will receive an interview or job offer.

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
