<p align="center">
  <h3 align="center">Resume.ai</h3>
  <p align="center">
  Let Us Sort the Resumes
  </p>
</p>
<br>
<br>

## About the Project

This is minor project submitted in the fulfillment of Internship at TechCiti Software Consulting Private Limited.

Every day, thousands of Job Listings are created to help the companies meet the ever growing demand of market by recruiting fresh talent. The job of a Recruiter is a very hard and important. It’s like identifying a needle in a haystack. But in the age of Artificial Intelligence it can be eased out for them through our product, Resume.ai.

Resume.ai reduces the burden on a Recruiter by leaving the tedious and repetitive task of going through thousands of resumes, of which only are handful are relevant. Just upload all the CVs into the system and receive a list of names of candidates and their respective CVs in descending order of their relevance to the Job Description. Reduce your Recruitment Turn Around Time with just a click.

## Technologies used

- Node
- Express
- MongoDB
- Typescript
- React
- Redux
- Ant Design
- Flask
- Numpy

## Features

- 2 Layer Filter Mechanism:

  - **Role-Based** – It features an AI classifier trained with 900+ resumes that can classify the resumes into 20 broad categories of Job roles with an accuracy of 95%.
  - **Similarity with Job Description** – It extracts the keywords from the inputted job description and maps them with resume based on cosine similarity(document similarity) to get a score percentage, which is used to sort and display the best resumes on top

- It can process up to 3000 resumes per hour
- Added Google OAuth and Password-based authentication to maintain the privacy
- Recruiters can export shortlisted candidates details, scores as CSV

## Architecture

- [Dataset Used](https://www.kaggle.com/gauravduttakiit/resume-dataset)
- [Architecture Design](https://user-images.githubusercontent.com/46809038/126433985-b84b832a-a029-479f-922c-c344ee88a21e.png)
