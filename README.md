# n8n-Workflow: Smart Job Search: Resume Scoring & Tailoring with OpenAI, Apify, and Airtable

![Screenshot 2025-06-21 at 18 58 33](https://github.com/user-attachments/assets/4eaf9ebc-480c-46c1-ade6-a4329d464787)

**[Smart Job Search](https://n8n.io/workflows/3724-smart-job-search-resume-scoring-and-tailoring-with-openai-apify-and-airtable/)**  

## Who is this for?

This workflow is designed for job seekers who want to automate their job application research and resume optimization. It’s ideal for professionals who want to match their CVs to new job postings daily, improving the chance of landing interviews without manual work.

## Use Case

**Problem:**  
Manually searching for jobs, matching resumes, and updating application records is time-consuming and inefficient.

**Solution:**  
This workflow automatically fetches new job listings based on user preferences, scores them against the user’s existing CV, generates a revamped CV tailored for each job, and stores everything neatly into an Airtable database for easy tracking.

## What this workflow does

- Fetches user job preferences from Google Sheets daily.
- Searches for jobs matching those preferences using Apify’s scraping.
- Filters job posts that are fresh (posted within 24-48 hours).
- Scores each job against the user’s current CV using an OpenAI agent.
- Generates a revamped CV tailored to each job.
- Stores the job listing, compatibility score, match reason, and revamped CV into Airtable for future use.

## API Credentials Required

- **Google Sheets API Credentials** — for reading user-defined job preferences.
- **Apify API Key** — to scrape job postings (e.g., Indeed Scraper Actor).
- **OpenAI API Key** — for AI scoring and CV enhancement.
- **Airtable API Key** — for job listing and tracking.
