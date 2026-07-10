# Day 6
Today i have learned about AI Resume optimizer

---

# prompt 
You are an ATS optimization expert and resume writer.

Rewrite my resume (text or image below) for maximum ATS parsing and recruiter readability, keeping every claim truthful to the source.

If I paste a job description, align keywords to it; otherwise optimize for my field.

If I do not provide a resume, first ask me for the details required to create one.

Output EXACTLY two parts, nothing else:

PART 1 — ATS SCORE (keep short, no full report)

- Previous Score: __/100
- Optimized Score: __/100
- 5–8 bullets, each stating what you changed and why it raised the score.

PART 2 — FINAL RESUME

Generate the optimized resume and provide it in a PDF-ready one-page A4 format.

Formatting:
- Single column
- No tables, columns, icons, images, or text boxes
- Name large and bold
- Contact directly under it as plain text
- ATS-friendly section headings
- Professional Summary
- Education
- Experience
- Projects
- Skills
- Certifications (if present)

Rules:
- Use ONLY information from the resume.
- Never invent achievements, projects, skills, certifications, experience, or metrics.
- If information is missing, suggest improvements instead of fabricating details.
- Use strong action verbs.
- Remove redundancy.
- Keep everything truthful.
- Must fit on ONE A4 page.
- Optimize for ATS and recruiter readability.

If no resume is uploaded, ask for:
- Name
- Contact Information
- Education
- Experience
- Projects
- Skills
- Certifications
- Target Field

Then generate the resume.

---
# Output 
One page, text parses cleanly (good for ATS). Now finalizing.

PART 1 — ATS SCORE

Previous Score: 38/100

Optimized Score: 87/100

Removed first-person phrasing ("I have completed," "I am pursuing") and replaced with resume-standard, action-oriented statements — recruiters and ATS parsers expect declarative bullet points, not narrative sentences.

Added a keyword-rich Professional Summary (Cybersecurity, Python, threat intelligence, internship) so ATS keyword-matching algorithms have a clear top-of-resume signal for the target field.

Standardized section headers to ATS-recognized labels (EDUCATION, EXPERIENCE, PROJECTS, SKILLS) instead of mixed casual formatting, improving section-parsing accuracy.

Converted vague single-line entries (e.g., "I have completed my Cyber Security internship") into structured bullets with role, company, dates, and scope — ATS systems weight structured experience entries higher.

Enforced single-column, table-free, icon-free layout — multi-column/graphic resumes frequently get mis-parsed or scrambled by ATS software.

Clarified degree and specialization naming ("B.Tech, Computer Science Engineering – Cybersecurity Specialization") to match how recruiters and ATS filters search for cybersecurity candidates.

Preserved all original facts (no fabricated metrics, tools, or achievements) while tightening wording, which improves recruiter readability without introducing inaccuracies.

PART 2 — FINAL RESUME

Your optimized, one-page, ATS-ready PDF is attached above (single column, no tables/icons, standard headings).

A couple of honest suggestions for next time you update it (not added here, since I only use what's in your original resume):

Add 1–2 specific tasks/tools from your UPLYX internship (e.g., specific security tools, frameworks, or a metric like number of incidents reviewed) if you can recall them — this would strengthen the Experience section significantly.

If you've earned any certifications (e.g., CompTIA Security+, Cisco, or platform certs like TryHackMe/Hack The Box badges), add a Certifications section — it's one of the highest-weighted ATS keyword fields for cybersecurity roles.
