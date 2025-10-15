\documentclass[letterpaper,11pt]{article}

\usepackage{latexsym}
\usepackage[empty]{fullpage}
\usepackage{titlesec}
\usepackage{marvosym}
\usepackage[usenames,dvipsnames]{color}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref}
\usepackage{fancyhdr}
\usepackage[english]{babel}
\usepackage{tabularx}
\usepackage{setspace}
\input{glyphtounicode}

\pagestyle{fancy}
\fancyhf{} % clear all header and footer fields
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

% Adjust margins
\addtolength{\oddsidemargin}{-0.5in}
\addtolength{\evensidemargin}{-0.5in}
\addtolength{\textwidth}{1in}
\addtolength{\topmargin}{-.5in}
\addtolength{\textheight}{1.0in}

\urlstyle{same}
\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

% Section formatting
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large
}{}{0em}{}[\color{black}\titlerule \vspace{-5pt}]

% PDF readable
\pdfgentounicode=1

% Custom commands
\newcommand{\resumeItem}[1]{\item\small{{#1 \vspace{-2pt}}}}
\newcommand{\resumeSubheading}[4]{
  \vspace{-2pt}\item
  \begin{tabular*}{0.97\textwidth}[t]{l@{\extracolsep{\fill}}r}
    \textbf{#1} & #2 \\
    \textit{\small#3} & \textit{\small#4} \\
  \end{tabular*}\vspace{-7pt}
}
\newcommand{\resumeSubSubheading}[2]{
  \item
  \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
    \textit{\small#1} & \textit{\small#2} \\
  \end{tabular*}\vspace{-7pt}
}
\newcommand{\resumeProjectHeading}[2]{
  \item
  \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
    \small#1 & #2 \\
  \end{tabular*}\vspace{-7pt}
}
\newcommand{\resumeSubItem}[1]{\resumeItem{#1}\vspace{-4pt}}
\renewcommand\labelitemii{$\vcenter{\hbox{\tiny$\bullet$}}$}
\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.15in, label={}]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}

%-------------------------------------------
%%%%%%  RESUME STARTS HERE  %%%%%%%%%%%%%%%%%%%%%%%%%%%%
\begin{document}

%----------HEADING----------
\begin{center}
    \textbf{\Huge \scshape Ahmed Talaat} \\ \vspace{1pt}
    \small Cairo, Egypt $|$ 01097411201 $|$ 
    \href{mailto:ahmedtalaat20011@gmail.com}{\underline{ahmedtalaat20011@gmail.com}} $|$ 
    \href{https://www.linkedin.com/in/ahmed-talaat-b2aba6223/}{\underline{LinkedIn}} $|$
    \href{https://github.com/ahmedtalaat-s/}{\underline{GitHub}}
\end{center}

%-----------CAREER OBJECTIVE-----------
\section{Career Objective}
Motivated and detail-oriented \textbf{Software Engineer} with strong experience in full-stack web development using \textbf{Angular} and \textbf{.NET}. Adept at designing, developing, and maintaining scalable, user-focused systems. Passionate about problem-solving, clean architecture, and continuous learning. Seeking to contribute to a forward-thinking team that values innovation and technical excellence.

%-----------EDUCATION-----------
\section{Education}
\resumeSubHeadingListStart
  \resumeSubheading
    {Tanta University}{2019 -- 2024}
    {B.Sc. in Computer Engineering, Faculty of Engineering}{Grade: Very Good}
  \resumeSubheading
    {Graduation Project: MoltaqaTech (E-learning System)}{Grade: Excellent}
    {}{}
\resumeSubHeadingListEnd

%-----------TRAINING & INTERNSHIPS-----------
\section{Training and Internships}
\resumeSubHeadingListStart
  \resumeSubheading
    {Information Technology Institute (ITI) – Tanta Branch}{Jul 2025 -- Present}
    {Intensive Training Program (ITP) – Full Stack .NET Track}{4-Month Camp}
    \resumeItemListStart
      \resumeItem{Gaining hands-on experience in full-stack development using ASP.NET Core, Angular, and SQL Server.}
      \resumeItem{Developing real-world projects with focus on best practices, design patterns, and clean code principles.}
    \resumeItemListEnd

  \resumeSubheading
    {Web Masters}{Feb 2025 -- June 2025}
    {Frontend Development Internship – Angular}{Remote}
    \resumeItemListStart
      \resumeItem{Building and optimizing dynamic web interfaces using Angular, TypeScript, and RESTful APIs.}
      \resumeItem{Collaborating with team members using Git and Agile workflow.}
    \resumeItemListEnd

  \resumeSubheading
    {Menofia ITI Summer Training}{Jul 2023 -- Sep 2023}
    {Backend Development (.NET Core, SQL Server)}{Menofia, Egypt}
    \resumeItemListStart
      \resumeItem{Developed backend services and APIs using ASP.NET Core and Entity Framework.}
      \resumeItem{Practiced database design, LINQ queries, and server-side logic implementation.}
    \resumeItemListEnd
\resumeSubHeadingListEnd

%-----------EXPERIENCE-----------
\section{Experience}
\resumeSubHeadingListStart
  \resumeSubheading
    {\textbf{\href{https://www.linkedin.com/company/ischooltech}{Ischool}}}{Feb 2023 -- Present}
    {Coding Instructor}{Cairo, Egypt}
    \resumeItemListStart
      \resumeItem{Delivered coding sessions to students aged 10–18, covering Python, web development, and problem-solving.}
      \resumeItem{Guided project-based learning and helped students build real applications.}
      \resumeItem{Enhanced teaching materials and introduced interactive learning methods.}
    \resumeItemListEnd
\resumeSubHeadingListEnd

%-----------PROJECTS-----------
\section{Projects}
\resumeSubHeadingListStart

% ===== E-Commerce Platform (Amazon Clone) =====
  \resumeProjectHeading
    {\textbf{\href{https://github.com/ahmedtalaat-s/Amazon-ecommerce-app}{E-Commerce Platform (Amazon Clone)}} $|$ Angular, Firebase, REST APIs}{}
  \setstretch{1.2}
  \textbf{Role:} Team Leader
  \begin{itemize}
    \item Led a team to develop a full-featured e-commerce web app following Agile Incremental methodology.
    \item Designed scalable architecture and implemented Firebase authentication for secure user management.
    \item Conducted code reviews, optimized performance, and managed deployment for production readiness.
  \end{itemize}

% ===== MoltaqaTech =====
  \resumeProjectHeading
    {\textbf{\href{https://github.com/ahmedtalaat-s/Multaqa_Tech}{MoltaqaTech (E-learning Platform – Graduation Project)}} $|$ Angular, TypeScript, Bootstrap, ASP.NET Core}{}
  \setstretch{1.2}
  \textbf{Role:} Front-End Developer
  \begin{itemize}
    \item Designed and developed a full-featured E-learning system similar to Udemy.
    \item Implemented course creation, video lectures, quizzes, assignments, and AI chatbot.
    \item Integrated payment system and ensured responsive UI across all devices.
  \end{itemize}

% ===== CST Project =====
  \resumeProjectHeading
    {\textbf{\href{https://github.com/ahmedrooshdii/CST-Project}{CST Project – E-Commerce Frontend}} $|$ HTML, CSS, JavaScript, LocalStorage, SessionStorage}{}
  \setstretch{1.2}
  \textbf{Role:} Team Leader
  \begin{itemize}
    \item Led a team to build a complete e-commerce frontend app using only client-side storage.
    \item Implemented authentication, product management, and cart functionality using LocalStorage and SessionStorage.
    \item Oversaw design consistency, feature integration, and task delegation across the team.
  \end{itemize}

% ===== Examination Management System =====
  \resumeProjectHeading
    {\textbf{Examination Management System (Desktop App)} $|$ C\#, Windows Forms, SQL Server, Entity Framework}{}
  \setstretch{1.2}
  \textbf{Role:} Team Leader \& Database Designer
  \begin{itemize}
    \item Led the development of a desktop system to automate exam management for educational institutions.
    \item Designed and implemented the SQL Server database schema, relationships, and constraints.
    \item Developed role-based authentication for Admins, Teachers, and Students.
    \item Implemented automated report generation, exam result exports, and error handling mechanisms.
  \end{itemize}

\resumeSubHeadingListEnd


%-----------TECHNICAL SKILLS-----------
\section{Technical Skills}
\resumeItemListStart
  \resumeItem{\textbf{Frontend:} HTML5, CSS3, JavaScript, TypeScript, Bootstrap, jQuery, Angular}
  \resumeItem{\textbf{Backend:} C\#, ASP.NET Core, LINQ, Entity Framework, SQL Server}
  \resumeItem{\textbf{Concepts:} OOP, RESTful APIs}
  \resumeItem{\textbf{Tools:} Git, GitHub, Visual Studio, VS Code, Postman}
  \resumeItem{\textbf{Languages:} C++, C\#}
\resumeItemListEnd

%-----------VOLUNTEERING-----------
\section{Volunteering}
\resumeSubHeadingListStart
  \resumeSubheading
    {OC Team Member}{Aug 2022 -- Mar 2024}
    {STP Student Activity}{}
  \resumeSubheading
    {PR \& FR Team Member}{Aug 2023 -- Jan 2024}
    {IEEE Tanta Student Branch}{}
  \resumeSubheading
    {Technical Team Member}{Nov 2023 -- Jul 2024}
    {IEEE Tanta Student Branch}{}
\resumeSubHeadingListEnd

\end{document}

<!--
**abdelrahman499/abdelrahman499** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
