Product Requirements Document (PRD): GitHub Profile README
1. Overview
Develop a professional, highly visual, and purely technical GitHub Profile README ( README.md ). The profile must highlight the developer’s focus on Web Development, Python Automation, and Cybersecurity/Penetration Testing. The final output must use Markdown combined with inline HTML for precise alignment and layout.
2. Global Constraints & Styling Rules
	•	No Emojis: Strictly prohibit the use of emojis anywhere in the document.
	•	Alignment: Use HTML tags (e.g.,  <h1 align="center"> ,  <p align="center"> ,  <p align="left"> ) to control layout. Standard markdown headers should only be used for section titles.
	•	Separators: Use horizontal rules ( --- ) between major sections.
	•	Badge/Icon Standardization:
	•	For standard dev tools, use Skillicons ( skillicons.dev ).
	•	For specific software/platforms without a Skillicon, use Shields.io ( img.shields.io ) with the query parameter  style=for-the-badge .
3. Layout & Section Specifications
3.1. Hero Section
	•	Header 1: Centered, reading “Hi there, I am Your Name”.
	•	Header 3: Centered, reading “A passionate developer and CTF player”.
	•	Dynamic Typing SVG: Centered image link pointing to  readme-typing-svg.demolab.com .
	•	Parameters:  font=Fira+Code ,  weight=600 ,  size=22 ,  pause=1000 ,  color=38BDF8 ,  center=true ,  vCenter=true ,  width=500 .
	•	Lines to type:
	1.	“Python + React Developer”
	2.	“Building Bots & CLI Games”
	3.	“CTF Player & Automation”
	4.	“Penetration Testing Enthusiast”
3.2. About Me Section
	•	Bulleted list focusing strictly on technical pursuits.
	•	Content points to cover:
	•	Currently studying Web Development and Python Automation.
	•	Creating custom Discord bots, CLI games, and frontend web apps.
	•	Actively participating in CTF events, cryptography challenges, and vulnerability assessments.
3.3. Cybersecurity and Penetration Testing Platforms
	•	Description: A brief sentence stating active participation in penetration testing, cryptography, and vulnerability assessment across competitive platforms.
	•	Badges (Shields.io): Left-aligned.
	•	Hack The Box ( logo=hackthebox ,  logoColor=9FEF00 ,  color=111927 )
	•	TryHackMe ( logo=tryhackme ,  logoColor=white ,  color=212C42 )
	•	picoCTF ( logo=linux ,  logoColor=white ,  color=4B275F )
	•	pwn.college ( logo=gnu-bash ,  logoColor=white ,  color=000000 )
3.4. Languages and Tools Section
Must be broken down into specific H4 ( #### ) subsections, rendered left-aligned. Use the specified icon provider for each tool.
A. Programming Languages
	•	Skillicons: Python, JavaScript, TypeScript, HTML5, CSS.
	•	Shields.io: Visual Basic, SQL (PostgreSQL logo).
B. Frontend Frameworks
	•	Skillicons: React, Vite.
C. Backend, Cloud and Databases
	•	Skillicons: Supabase, Firebase, Vercel, Cloudflare.
D. Design and Creative
	•	Skillicons: Figma.
	•	Shields.io: Framer, Affinity Photo, DaVinci Resolve.
E. Security and Penetration Testing Tools
	•	Shields.io: Burp Suite Community, Wireshark, John the Ripper (GnuPrivacyGuard logo).
F. Environments, Utilities and Other Tools
•	Skillicons: Linux, Bash, Git, Arduino.
	•	Shields.io: Cursor IDE, Google Workspace, Razorpay, Google Antigravity.
3.5. Player Stats (GitHub Metrics)
	•	Centered  <p>  container.
	•	Two images side-by-side, each with  width="48%" .
	•	Card 1 (Stats):  github-readme-stats.vercel.app/api 
	•	Parameters:  username=YOUR_USERNAME ,  show_icons=true ,  theme=tokyonight ,  hide_border=true ,  bg_color=0D1117 .
	•	Card 2 (Streak):  github-readme-streak-stats.herokuapp.com/ 
	•	Parameters:  user=YOUR_USERNAME ,  theme=tokyonight ,  hide_border=true ,  background=0D1117 .
3.6. Contact / Social Links
	•	Title: “Lets Connect”
	•	Left-aligned  <p>  container.
	•	Badges (Shields.io wrapped in  <a>  tags):
	•	Email ( logo=gmail , color  D14836 , pointing to  mailto:your.email@example.com ).
	•	Discord ( logo=discord , color  7289DA , pointing to  https://discord.com/users/YOUR_DISCORD_ID ).
4. Acceptance Criteria
	1.	The code is strictly valid Markdown and HTML.
	2.	The file contains zero emojis.
	3.	Non-technical hobbies are entirely excluded.
	4.	All shields.io images adhere to the  for-the-badge  style constraint.
	5.	Placeholder strings ( Your Name ,  YOUR_USERNAME , etc.) are clearly visible for the user to replace later.