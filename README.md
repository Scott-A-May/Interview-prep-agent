# Interview Prep Agent

🔗 **Live App:** [Interview Prep Agent](https://scott-a-may.github.io/interview-prep-agent)

A browser-based AI tool that analyzes a job description alongside your resume and generates tailored interview questions a hiring panel is likely to ask.

Built as part of my AI-augmented analytics portfolio.

## What it does

- Paste your resume and any job description
- Generates 15–25 targeted questions across five categories:
  - **Behavioral** — STAR-format questions based on the role's responsibilities
  - **Technical** — specific to the tools and skills in the job posting
  - **Experience gaps** — questions about areas where your resume is light relative to the job
  - **Role fit** — career trajectory, motivation, and cultural fit
  - **Situational** — hypothetical workplace scenarios relevant to the role
- Each question includes a coaching hint explaining what the interviewer is really assessing

## How it works

- Frontend: plain HTML/CSS/JS hosted on GitHub Pages
- AI: Anthropic Claude (claude-sonnet-4-6) via a Cloudflare Worker proxy
- The API key is stored securely as a Cloudflare secret — never exposed in the frontend code

## Tech stack

| Layer | Tool |
|---|---|
| Hosting | GitHub Pages |
| AI model | Anthropic Claude Sonnet 4.6 |
| API proxy | Cloudflare Workers |
| Frontend | HTML / CSS / JavaScript |

## Related projects

This project is part of a broader portfolio demonstrating AI-augmented data analysis skills:

- [HousingMap](https://github.com/Scott-A-May/HousingMap)
- [HousingDashboard](https://github.com/Scott-A-May/HousingDashboard)
- [DataCleaner](https://github.com/Scott-A-May/DataCleaner)
- [HousingPredictor](https://github.com/Scott-A-May/HousingPredictor)

## Author

Scott May — Data Analytics Professional  
[github.com/Scott-A-May](https://github.com/Scott-A-May)
