%-------------------------
% Resume in Latex
% Author: Shakra Shamim
%------------------------

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
\usepackage{fontawesome5}
\usepackage{multicol}
\setlength{\multicolsep}{-3.0pt}
\setlength{\columnsep}{-1pt}
\input{glyphtounicode}

\pagestyle{fancy}
\fancyhf{}
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

\addtolength{\oddsidemargin}{-0.6in}
\addtolength{\evensidemargin}{-0.5in}
\addtolength{\textwidth}{1.19in}
\addtolength{\topmargin}{-.7in}
\addtolength{\textheight}{1.4in}

\urlstyle{same}
\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

\titleformat{\section}{
  \vspace{-6pt}\scshape\raggedright\large\bfseries
}{}{0em}{}[\color{black}\titlerule \vspace{-5pt}]

\pdfgentounicode=1

\newcommand{\resumeItem}[1]{\item\small{{#1 \vspace{-2pt}}}}
\newcommand{\resumeSubheading}[4]{
  \vspace{-2pt}\item
    \begin{tabular*}{1.0\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{#1} & \textbf{\small #2} \\
      \textit{\small#3} & \textit{\small #4} \\
    \end{tabular*}\vspace{-6pt}
}
\newcommand{\resumeProjectHeading}[2]{
    \item
    \begin{tabular*}{1.001\textwidth}{l@{\extracolsep{\fill}}r}
      \small#1 & \textbf{\small #2}\\
    \end{tabular*}\vspace{-6pt}
}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}
\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.0in, label={}]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}

\begin{document}

%----------HEADING----------
\begin{center}
    {\Huge \scshape Abhi Ranjan Kumar} \\ \vspace{4pt}
    \textbf{\Large \scshape Frontend Developer} \\ \vspace{4pt}
    \small 
    \faPhone\ +91-6202532945 ~ 
    \href{mailto:chaudharyabhiranjan129@gmail.com}{\faEnvelope\ \underline{chaudharyabhiranjan129@gmail.com}} ~
    \href{https://github.com/Ravi62025}{\faGithub\ \underline{github.com/Ravi62025}}
\end{center}


%-----------SUMMARY-----------
\section{Summary}
Aspiring Frontend Developer with hands-on skills in modern web technologies. Proficient in building responsive, interactive user interfaces using HTML, CSS, JavaScript, and React. Experienced in styling with Tailwind CSS and equipped with foundational knowledge of C++ for understanding core programming logic. Passionate about creating clean, efficient code and continuously expanding expertise in frontend development.

%-----------SKILLS-----------
\section{Skills}
\textbf{Frontend Stack:} HTML5, CSS3, JavaScript, React, Tailwind CSS  \\
\textbf{Development & Tools:} VS Code, Git, GitHub, npm, Responsive Design \\
\textbf{Programming:} C++ (Programming Fundamentals)



%-----------PROJECTS-----------
\section{Projects}
\resumeSubHeadingListStart

  \resumeProjectHeading
      {\textbf{Weather App} $|$ \emph{HTML, CSS, JavaScript, Weather API}}{2025}
      \resumeItemListStart
        \resumeItem{Developed a responsive weather application that displays real-time weather information based on user-entered city names.}
        \resumeItem{Integrated external Weather API to fetch temperature, humidity, and weather conditions using asynchronous JavaScript.}
        \resumeItem{Implemented clean UI and responsive layout for seamless use across mobile and desktop devices.}
        \resumeItem{Strengthened skills in API integration, async/await, and DOM manipulation.}
      \resumeItemListEnd

  \resumeProjectHeading
      {\textbf{Notes App} $|$ \emph{HTML, CSS, JavaScript}}{2025}
      \resumeItemListStart
        \resumeItem{Built a notes management application allowing users to create, edit, and delete notes efficiently.}
        \resumeItem{Used browser localStorage to persist notes data across sessions.}
        \resumeItem{Designed a user-friendly and responsive interface focused on simplicity and usability.}
        \resumeItem{Improved understanding of JavaScript logic and state handling.}
      \resumeItemListEnd

  \resumeProjectHeading
      {\textbf{Quiz App} $|$ \emph{HTML, CSS, JavaScript}}{2025}
      \resumeItemListStart
        \resumeItem{Developed an interactive quiz application with multiple-choice questions and real-time score calculation.}
        \resumeItem{Implemented dynamic question rendering and answer validation using JavaScript.}
        \resumeItem{Enhanced user engagement through instant feedback and result display.}
        \resumeItem{Practiced event handling and DOM manipulation techniques.}
      \resumeItemListEnd

  \resumeProjectHeading
      {\textbf{To-Do List App} $|$ \emph{HTML, CSS, JavaScript}}{2025}
      \resumeItemListStart
        \resumeItem{Created a task management application to add, delete, and mark tasks as completed.}
        \resumeItem{Designed a responsive layout to ensure smooth usage across different screen sizes.}
        \resumeItem{Focused on clean UI and intuitive user interaction.}
        \resumeItem{Strengthened JavaScript event handling and logical flow implementation.}
      \resumeItemListEnd

\resumeSubHeadingListEnd


%-----------AWARDS-----------
\section{Certifications}
\resumeSubHeadingListStart
  \resumeProjectHeading
      {\textbf{Bits and Bytes of Computer Networking} $|$ \emph{Coursera}}{2025}
      \resumeItemListStart
        \resumeItem{Completed a foundational course covering computer networking concepts including OSI and TCP/IP models, IP addressing, DNS, and HTTP/HTTPS.}
        \resumeItem{Gained understanding of how data is transmitted across networks and the basics of internet infrastructure.}
      \resumeItemListEnd
\resumeSubHeadingListEnd


%-----------EDUCATION-----------
\section{Education}
\resumeSubHeadingListStart
  \resumeSubHeading
      {\textbf{Vellore Institute of Technology, Bhopal}}{Bhopal, India}
      {Bachelor of Technology (B.Tech) in Computer Science}{2023 -- 2027}
      \resumeItemListStart
        \resumeItem{Third-year undergraduate student.}
        \resumeItem{CGPA: 7.68}
      \resumeItemListEnd
\resumeSubHeadingListEnd


\end{document}
