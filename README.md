
# import { Icons } from "@/components/icons";

import { HomeIcon, NotebookIcon } from "lucide-react";

export const DATA = {
name: "Altaf",
initials: "MA",

url: "https://your-portfolio.com", // SAMPLE
location: "India",
locationLink: "https://www.google.com/maps/place/India",

description:
"Full-stack  developer and founder of Adowise. Passionate about building scalable products, clean UI, and high-performance web apps.",

summary:
"I'm a MERN/Next.js developer and the founder of Adowise. Previously worked with Tradylytics and Explorin, where I built responsive UIs, REST APIs, optimized databases, and shipped full-stack features. I’ve built platforms like WordFlow, JobGo, Briefly.ai, and Connectify.",

avatarUrl:
"https://avatars.githubusercontent.com/u/178491093?s=400\&u=54809017fc5993a4448a1a1ecb1eb4dda2c315fa\&v=4",

skills: [
"React",
"Next.js",
"TypeScript",
"Node.js",
"Express.js",
"MongoDB",
"PostgreSQL",
"Prisma",
"Tailwind CSS",
"Shadcn UI",
"Redux",
"GraphQL",
"Zod",
"WebSockets",
],

navbar: [
{ href: "/", icon: HomeIcon, label: "Home" },
{ href: "/blog", icon: NotebookIcon, label: "Blog" },
],

contact: {
email: "reachmohdaltaf@gmail.com",
tel: "+91 7876637551",
social: {
GitHub: {
name: "GitHub",
url: "https://github.com/code-with-altaf",
icon: Icons.github,
navbar: true,
},
LinkedIn: {
name: "LinkedIn",
url: "https://linkedin.com/in/reachmohdaltaf",
icon: Icons.linkedin,
navbar: true,
},
X: {
name: "X",
url: "https://x.com/reachmohdaltaf",
icon: Icons.x,
navbar: true,
},
YouTube: {
name: "YouTube",
url: "https://www.youtube.com/@codewithaltaf",
icon: Icons.youtube,
navbar: true,
},
Portfolio: {
name: "Portfolio",
url: "https://adowise.in",
icon: Icons.globe,
navbar: true,
},
email: {
name: "Send Email",
url: "mailto:reachmohdaltaf@gmail.com",
icon: Icons.email,
navbar: false,
},
},

},

// ---------------------------------------------------
//                    EXPERIENCE
// ---------------------------------------------------
work: [
{
company: "Adowise",
href: "\#", // SAMPLE
badges: ["Founder"],
location: "India",
title: "Founder \& Full-Stack Developer",
logoUrl: "/adowise.png", // You will replace
start: "January 2025",
end: "Present",
description:
"Building Adowise, a full-stack mentorship and services platform using React, Redux, Express.js, and MongoDB with secure authentication and booking workflows.",
},
{
company: "Tradylytics",
href: "\#", // SAMPLE
badges: ["Intern"],
location: "Remote",
title: "Full-Stack Developer Intern",
logoUrl: "/tradylitics.png", // You will replace
start: "January 2025",
end: "December 2025",
description:
"Designed modern UI components, implemented responsive layouts, integrated charts, and improved UX using Shadcn UI.",
},
{
company: "Explorin",
href: "\#", // SAMPLE
badges: ["Intern"],
location: "Roorkee, India",
title: "MERN Stack Developer",
logoUrl: "/explorin.png", // You will replace
start: "September 2024",
end: "November 2024",
description:
"Worked on MERN applications, optimized database queries, improved API performance, and helped scale backend systems.",
},
],

// ---------------------------------------------------
//                    EDUCATION
// ---------------------------------------------------
education: [
{
school: "SGGSJ Govt. College",
href: "\#", // SAMPLE
degree: "Bachelor of Computer Applications (BCA)",
logoUrl: "/sggsj.jpg", // SAMPLE
start: "2021",
end: "2024",
},
{
school: "Bibi Jeet Kaur College",
href: "\#", // SAMPLE
degree: "Higher Secondary Education (11th–12th)",
logoUrl: "/bibi-jeet.png", // SAMPLE
start: "2019",
end: "2021",
},
{
school: "The Scholars Home, Paonta Sahib",
href: "\#", // SAMPLE
degree: "Primary \& Secondary Education (Grades 1–10)",
logoUrl: "/scholars-home.png", // SAMPLE
start: "2009",
end: "2019",
video: "/workflow.mp4",
},
],

// ---------------------------------------------------
//                    PROJECTS
// ---------------------------------------------------
projects: [
{
title: "Briefly.ai",
href: "\#",
dates: "2025",
active: true,
video: "/briefly.mp4",
description:
"AI-powered PDF summarizer built using OpenAI API with modern UI and optimized file processing.",
technologies: ["Next.js", "OpenAI API", "Tailwind", "Shadcn", "React Hook Form"],

},

{
title: "Adowise",
href: "\#",
dates: "2025",
active: true,
video: "/adowise.mp4",
description:
"Mentorship platform offering services, bookings, priority DMs, and secure role-based workflows.",
technologies: ["React", "Express.js", "MongoDB", "Redux", "Tailwind", "Shadcn"],

},
{
title: "Invozo",
href: "https://invozo-pges.vercel.app/generate",
dates: "2025",
active: true,
video: "/invozo.mp4", // add your video if available
description:
"Create invoices in minutes, not hours. Simple, fast, and professional invoice generator built with clean UI and smooth workflows.",
technologies: ["Next.js", "TypeScript", "Tailwind", "Shadcn", "Prisma"],

},
{
title: "Carelytics",
href: "https://carelytics-three.vercel.app/",
dates: "2025",
active: true,
video: "/carelytics.mp4", // add your demo if available
description:
"Smart clinic performance dashboard showing patient insights, visit trends, revenue stats, and powerful analytics in one place.",
technologies: [
"Next.js",
"React",
"MongoDB",
"Tailwind",
"Shadcn",
"Recharts"
],

}
,

{
title: "WordFlow",
href: "\#",
dates: "2025",
active: true,
video: "/workflow.mp4",
description:
"Full-stack blogging platform with GraphQL, Prisma, PostgreSQL, advanced filters and authentication.",
technologies: [
"Next.js",
"GraphQL",
"Prisma",
"PostgreSQL",
"Tailwind",
"TanStack Query",
],

},

{
title: "Connectify",
href: "\#",
dates: "2024",
active: true,
video: "/connectify.mp4",
description:
"Social platform with posts, notifications, real-time updates, image uploads, and user profiles.",
technologies: [
"React",
"Express.js",
"MongoDB",
"TanStack Query",
"Tailwind",
"Cloudinary",
],

},

{
title: "JobGo",
href: "\#",
dates: "2025",
active: true,
video: "/jobgo.mp4",
description:
"Job platform with smart search, company dashboards, role-based auth, and clean UI workflows.",
technologies: ["Next.js", "MongoDB", "Prisma", "Redux", "Tailwind", "Shadcn"],

},
{
title: "WryTit",
href: "https://wrytit.vercel.app",
dates: "2025",
active: true,
video: "/wrytit.mp4", // optional if you add later
description:
"A modern storytelling and blogging platform with a beautifully crafted UI. A space to explore ideas, express thoughts, and read meaningful stories with a clean, reader-focused experience.",
technologies: ["Next.js", "Tailwind", "Shadcn", "React", "TypeScript"],

}

],

// ---------------------------------------------------
//                   HACKATHONS (EMPTY)
// ---------------------------------------------------
hackathons: [],

} as const;

resadme bnao pleasem e profile kai liye github kai readme kai pliye

I'll create a professional GitHub README for your portfolio that showcases your skills, projects, and experience using your data config.

***

# 👋 Hi, I'm Altaf!

<img src="https://avatars.githubusercontent.com/u/178491093?s=400&u=54809017fc5993a4448a1a1ecb1eb4dda2c315fa&v=4" alt="Altaf" width="150" style="border-radius: 50%;"/>
**Full-stack developer and founder of Adowise**
Passionate about building scalable products, clean UI, and high-performance web apps from India 🇮🇳

## 🚀 About Me

I'm a MERN/Next.js developer and the founder of **Adowise** - a full-stack mentorship and services platform. Previously worked with **Tradylytics** and **Explorin**, where I built responsive UIs, REST APIs, optimized databases, and shipped full-stack features.

**What I love building:**

- Scalable SaaS platforms
- Modern UIs with Tailwind \& Shadcn
- Full-stack applications with Next.js
- Real-time features with WebSockets
- Analytics dashboards \& AI tools

**📫 How to reach me:**
[Email](mailto:reachmohdaltaf@gmail.com) | [+91 7876637551](tel:+917876637551)

<p align="center">
  <a href="https://github.com/code-with-altaf?tab=following">
    <img src="https://img.shields.io/github/followers/code-with-altaf?label=Followers&style=for-the-badge" />
  </a>
  <a href="https://github.com/code-with-altaf?tab=repositories">
    <img src="https://img.shields.io/github/repo-size/code-with-altaf/next-template-portfolio?color=orange&label=Repo%20size&style=for-the-badge" />
  </a>
  <a href="https://adowise.in">
    <img src="https://img.shields.io/badge/Portfolio-000?style=for-the-badge&logo=react&logoColor=white" />
  </a>
</p>

## 🛠️ Tech Stack

### Frontend

<img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" /> 
<img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white" alt="Next.js" /> 
<img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" /> 
<img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind" /> 
<img src="https://img.shields.io/badge/Shadcn-000000?style=for-the-badge&logo=shadcn&logoColor=white" alt="Shadcn" />

### Backend

<img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js" /> 
<img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express.js" /> 
<img src="https://img.shields.io/badge/Prisma-3987C5?style=for-the-badge&logo=prisma&logoColor=white" alt="Prisma" /> 
<img src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" /> 
<img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />

### Tools \& Others

<img src="https://img.shields.io/badge/Redux-593D88?style=for-the-badge&logo=redux&logoColor=white" alt="Redux" /> 
<img src="https://img.shields.io/badge/GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white" alt="GraphQL" /> 
<img src="https://img.shields.io/badge/Zod-00D4AA?style=for-the-badge&logo=zod&logoColor=white" alt="Zod" /> 
<img src="https://img.shields.io/badge/WebSockets-00D4AA?style=for-the-badge&logo=websocket&logoColor=white" alt="WebSockets" />

## ✨ Featured Projects

### 🔥 Live Projects

| Project | Description | Tech Stack | Demo |
| :-- | :-- | :-- | :-- |
| **[Invozo](https://invozo-pges.vercel.app/generate)** | Professional invoice generator with clean UI | Next.js, TypeScript, Prisma |  |
| **[Carelytics](https://carelytics-three.vercel.app/)** | Clinic performance dashboard with analytics | Next.js, MongoDB, Recharts |  |
| **[WryTit](https://wrytit.vercel.app)** | Modern storytelling platform | Next.js, Tailwind, Shadcn |  |

### 🏗️ Building

| Project | Description | Tech Stack |
| :-- | :-- | :-- |
| **[Adowise](https://adowise.in)** | Mentorship platform with bookings \& DMs | React, Express, MongoDB, Redux |
| **[Briefly.ai]** | AI-powered PDF summarizer | Next.js, OpenAI API |
| **[WordFlow]** | Full-stack blogging with GraphQL | Next.js, Prisma, PostgreSQL |

## 💼 Work Experience

### Adowise *(Jan 2025 - Present)*

**Founder \& Full-Stack Developer**
Building a mentorship platform with secure auth, booking workflows, and role-based access.

### Tradylytics *(Jan 2025 - Dec 2025)*

**Full-Stack Developer Intern** *(Remote)*
Designed UI components, implemented charts, and improved UX with Shadcn UI.

### Explorin *(Sep 2024 - Nov 2024)*

**MERN Stack Developer** *(Roorkee, India)*
Optimized database queries and scaled backend systems.

## 🎓 Education

- **Bachelor of Computer Applications (BCA)**
SGGSJ Govt. College *(2021 - 2024)*
- **Higher Secondary (11th-12th)**
Bibi Jeet Kaur College *(2019 - 2021)*


## 🌐 Connect With Me

<div align="center">
  ```
  <a href="https://github.com/code-with-altaf"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" /></a>
  ```
  ```
  <a href="https://linkedin.com/in/reachmohdaltaf"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  ```
  ```
  <a href="https://x.com/reachmohdaltaf"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" /></a>
  ```
  ```
  <a href="https://youtube.com/@codewithaltaf"><img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" /></a>
  ```
  ```
  <a href="https://adowise.in"><img src="https://img.shields.io/badge/Portfolio-15A7E1?style=for-the-badge&logo=todoist&logoColor=white" /></a>
  ```
  ```
  <a href="mailto:reachmohdaltaf@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  ```
</div>
<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=code-with-altaf&show_icons=true&theme=radical&hide_border=true" alt="Altaf's GitHub stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=code-with-altaf&layout=compact&theme=radical&hide_border=true" alt="Top Languages" />
</div>

***

⭐ **Star this repository if you found it helpful!**

***

Would you like me to customize any specific section, add more project details, or adjust the styling for your GitHub profile?
<span style="display:none">[^1]</span>

<div align="center">⁂</div>

[^1]: https://your-portfolio.com

