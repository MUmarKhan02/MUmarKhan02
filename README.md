# Greetings! I'm Umar 

### [Portfolio Website Showcase!](https://mumarkhan02.github.io/Website/)

Here are some quick fun facts about me:

- I graduated from University of Windsor with a Bachelors Degree in Computer Science with Software Engineering Option
- I am currently pursuing my Masters Degree in Computer Science at Wayne State University
- My main interests are AI, ML, and of course....software engineering...lol
- My main comfortable languages to work with are Java, Python, and HTML/CSS/JS.
- Recently I have been working more on C# and ASP.NET projects so we'll see how my comfort languages change. Maybe I finally leave the dark path of Java behind me and embrace the light of Python, C#, JS.....(nah maybe not)
- I love coding with my life but holy I cannot stare at a computer screen for like more than an hour of my time cause otherwise I start to get restless and bored. Which then leaves me to procrastinating and doing absolutely nothing for the next 3 hours after #WForLaziness
- My regular day goes as follows: Wake up, have coffee, apply nonstop for jobs, work on projects, go gym, work on projects again, sleep and suffer. (While in between each activity, I'm slacking off doing something else entirely that's unrelated to anything)

---

## Actually Cool Projects I made

### [AutoOps AI](https://auto-ops-ai-mu.vercel.app/)

- Full-stack AI document processing platform built with ASP.NET Core, FastAPI, Celery, Redis, React, and PostgreSQL. Upload any document and get an AI-generated summary, extracted fields, and metadata — processed asynchronously through a parse → chunk → analyze pipeline with real-time progress updates.
- I built this because I wanted to tackle something that felt genuinely complex end-to-end — async workers, SSE streaming, JWT auth with refresh tokens, Docker Compose, and actual cloud deployment. Basically threw everything at it to see if I could make it all work together. Spoiler: eventually yes, after suffering for a while.
- Deployed on Railway (backend + workers) and Vercel (frontend). Uses Gemini 2.5 Flash for the AI processing side.

### [Blog Platform](https://d3djg0s7uij4hb.cloudfront.net/)

- Full-stack blogging platform built with Spring Boot, React, TypeScript, and PostgreSQL. Features JWT authentication with role-based access control, a rich text editor with DOMPurify sanitization, and full AWS deployment across Elastic Beanstalk, RDS, S3, and CloudFront.
- Honestly built this to get proper hands-on with AWS because everyone talks about it but actually setting up Elastic Beanstalk, hooking RDS to it, and proxying everything through CloudFront is a different experience entirely. Worth the pain.
- All API traffic routes through CloudFront for unified HTTPS delivery which was probably the most satisfying part to get working.

### [AdaptIQ](https://github.com/MUmarKhan02/AdaptIQ)

- Full-stack AI resume tailoring tool powered by Google Gemini. Paste a job link or description, upload your resume, and get a tailored ATS-optimized version with a 5-metric score breakdown and cover letter.
- Built this out of pure frustration with the job application process. Tailoring a resume for every single posting is genuinely exhausting so I automated it. Single-pass LLM pipeline keeps it fast and cuts API overhead significantly.
- The 5-metric ATS scoring engine (parsing ability, keyword coverage, quantification rate, job match, and injection quality) was the most interesting part to design because it had to be actually useful, not just a fake score.

### [SwiftFill](https://github.com/MUmarKhan02/SwiftFill)

- Chrome extension that autofills job application forms on Workday, Greenhouse, and more. Supports application, signup, and login modes with per-field selector matching and configurable profile data.
- I made this to solve the most annoying step in every job application, and that is filling in basic information such as email, phone number, name, to even creating/logging into accounts such as Workday with email and password, which eliminates the tedious amount of time it takes all to just a simple button click.
- When creating accounts, you can either use a default general password or a stronger password if you so desire.
  
---
## Top Languages

![Top Languages](https://github-readme-stats-nine-gold-62.vercel.app/api/top-langs/?username=MUmarKhan02&layout=compact&theme=radical)
