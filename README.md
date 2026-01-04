%-------------------------
% Resume in Latex
% Author : Jake Gutierrez
% Based off of: https://github.com/sb2nov/resume
% License : MIT
%------------------------

\documentclass[letterpaper,11pt]{article}
\documentclass{article}
\usepackage{hyperref}
\usepackage{url}
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


%----------FONT OPTIONS----------
% sans-serif
% \usepackage[sfdefault]{FiraSans}
% \usepackage[sfdefault]{roboto}
% \usepackage[sfdefault]{noto-sans}
% \usepackage[default]{sourcesanspro}

% serif
% \usepackage{CormorantGaramond}
% \usepackage{charter}


\pagestyle{fancy}
\fancyhf{} % clear all header and footer fields
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

% Adjust margins
\addtolength{\oddsidemargin}{-0.6in}
\addtolength{\evensidemargin}{-0.5in}
\addtolength{\textwidth}{1.19in}
\addtolength{\topmargin}{-.7in}
\addtolength{\textheight}{1.4in}

\urlstyle{same}

\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

% Sections formatting
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large\bfseries
}{}{0em}{}[\color{black}\titlerule \vspace{-5pt}]

% Ensure that generate pdf is machine readable/ATS parsable
\pdfgentounicode=1

%-------------------------
% Custom commands
\newcommand{\resumeItem}[1]{
  \item\small{
    {#1 \vspace{-2pt}}
  }
}

\newcommand{\classesList}[4]{
    \item\small{
        {#1 #2 #3 #4 \vspace{-2pt}}
  }
}

\newcommand{\resumeSubheading}[4]{
  \vspace{-2pt}\item
    \begin{tabular*}{1.0\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{#1} & \textbf{\small #2} \\
      \textit{\small#3} & \textit{\small #4} \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubSubheading}[2]{
    \item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \textit{\small#1} & \textit{\small #2} \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeProjectHeading}[2]{
    \item
    \begin{tabular*}{1.001\textwidth}{l@{\extracolsep{\fill}}r}
      \small#1 & \textbf{\small #2}\\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubItem}[1]{\resumeItem{#1}\vspace{-4pt}}

\renewcommand\labelitemi{$\vcenter{\hbox{\tiny$\bullet$}}$}
\renewcommand\labelitemii{$\vcenter{\hbox{\tiny$\bullet$}}$}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.0in, label={}]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}
\usepackage{hyperref}
\hypersetup{
    colorlinks=true,
    urlcolor=blue
}


%-------------------------------------------
%%%%%%  RESUME STARTS HERE  %%%%%%%%%%%%%%%%%%%%%%%%%%%%


\begin{document}

%----------HEADING----------
% \begin{tabular*}{\textwidth}{l@{\extracolsep{\fill}}r}
%   \textbf{\href{http://sourabhbajaj.com/}{\Large Sourabh Bajaj}} & Email : \href{mailto:sourabh@sourabhbajaj.com}{sourabh@sourabhbajaj.com}\\
%   \href{http://sourabhbajaj.com/}{http://www.sourabhbajaj.com} & Mobile : +1-123-456-789


% \end{tabular*}

\begin{center}
    {\Huge \scshape RUTWIK SATPUTE } \\ \vspace{1pt}
    Pune, Maharashtra. \\ \vspace{1pt}
    \small \raisebox{-0.1\height}\faPhone\ 9970546063 ~ \href{mailto:x@gmail.com}{\raisebox{-0.2\height}\faEnvelope\  \underline{rutwiksatpute3034@gmail.com}} ~ 
    \href{https://linkedin.com/in//}{\raisebox{-0.2\height}\faLinkedin\ \underline{\textbf{\href{https://www.linkedin.com/in/rutwik-satpute-89835b243/}{Linkdin}}}}  ~
    \href{https://github.com/}{\raisebox{-0.2\height}\faGithub\ \underline{\textbf{\href{https://github.com/rutwik30usr}{Github}}}}
    \vspace{-8pt}
\end{center}




%------RELEVANT COURSEWORK-------
    %\resumeSubHeadingListStart
 %       \begin{multicols}{4}
%            \begin{itemize}[itemsep=-5pt, parsep=3pt]
 %               \item\small Data Structures
%                \item Software Methodology
%                \item Algorithms Analysis
%                \item Database Management
%                \item Artificial Intelligence
%                \item Internet Technology
%                \item Systems Programming
%                \item Computer Architecture
%            \end{itemize}
%        \end{multicols}
%        \vspace*{2.0\multicolsep}
    %\resumeSubHeadingListEnd
     
     %\rule{\textwidth}{1.0pt} 
% -------- Summary ------ 
\section{Summary}
\vspace{-3pt}

{\small
Cloud-focused IT professional with 3.10 years of experience in Windows Server Administration and
Cloud Operations across VMware and AWS. Skilled in VM/EC2 provisioning and decommissioning,
managing instances, backup and recovery for VMs/EC2 and snapshots, and storage platforms including
Datastores, VM files, Managed Disks, and AWS S3. Hands-on experience with IAM, Active Directory,
VMware, patching, vulnerability remediation, and incident/change management processes.

Experienced in supporting and improving hybrid IT infrastructures with a focus on system reliability,
high availability, and cloud cost optimization. Actively learning modern cloud operational practices to
strengthen automation and performance.

Seeking opportunities in VMware/AWS Administration and Cloud Operations.

\vspace{4pt}
\begin{itemize}[leftmargin=0.15in]

\item \textbf{Cloud Operations:} VM/EC2 provisioning and decommissioning, backup and recovery (VMs/EC2),
AWS Elastic File System, Managed Disks, AWS S3, instance management, monitoring and troubleshooting,
governance, and cost optimization.

\item \textbf{Windows \& Infrastructure Administration:} Windows Server Administration,
DNS, DHCP, patching, and performance tuning.

\item \textbf{Virtualization:} VMware

\item \textbf{IT Service Management:} Incident, request, and change management using ServiceNow.

\end{itemize}
}

\vspace{-16pt}
%-----------PROGRAMMING SKILLS-----------
 \section{Technical Skills}

\begin{itemize}[leftmargin=0.15in, label={}]
    \small{
        \item \textbf{Cloud platforms} : AWS
        \item \textbf{Virtualization} : VMWare ESXi 6.7/7.0/8.0
        \item \textbf{Monitoring Tools} : AWS CloudWatch, SolarWinds
        \item \textbf{Deployments} : Public Clouds, On-Premises
        \item \textbf{Infrastructure as Code} : Terraform
        \item \textbf{Operating System} : Windows, Linux
        \item \textbf{Ticketing Tool} : ServiceNow
        \item \textbf{Other Tools} : Jenkin, Git hub, putty, git bash, CyberArk
        
    }
\end{itemize} 


%-----------Experience-----------
\section{EXPERIENCE}
  \resumeSubHeadingListStart

\resumeSubheading
      {Infosys}{May 2025 -- Present}
      {Associate consultant}{Pune, Maharashtra}
  \resumeSubHeadingListEnd


    
    \resumeSubheading
      {Tata Consultancy Services}{Feb 2022 -- May 2025}
      {System Engineer}{Pune, Maharashtra}
  \resumeSubHeadingListEnd

  


%-----------EXPERIENCE-----------
\section{Project Experience}
\resumeSubHeadingListStart

\resumeProjectHeading
  {\textbf{Project: Enterprise Cloud Infrastructure Management}}{}
\resumeItemListStart
\resumeItem{\textbf{Cloud and Infrastructure Administrator}}
        \resumeItemListStart
         \resumeItem{Performed provisioning, decommissioning, and lifecycle management of AWS EC2 instances and
VMware virtual machines, including OS installations, upgrades, and migration from end-of-life
operating systems to supported versions.} 
          \resumeItem{Windows Server Support: Providing L1/L2 support for Windows Servers (2012/2016/2019/2022) globally, including troubleshooting and resolving OS-related issues, slow boot problems, server hang, and performance issues}
          \resumeItem{Executed backup, restore, and disaster recovery operations using AWS snapshots, AMIs,
and VMware backup solutions like snapshots and other windows server backups , improving recovery readiness and minimizing downtime risks} 
          \resumeItem{Managed identity and access controls using AWS IAM and Active Directory,
designing and enforcing least-privilege access through roles and policies
to strengthen security across hybrid AWS and on-prem VMware environments.}
          \resumeItem{Supported high availability and resilience through VMware HA/DRS configurations,
AWS Auto Scaling, and load balancing, along with proactive performance monitoring and tuning.}
          \resumeItem{Monitored and troubleshot AWS and VMware environments using CloudWatch, vCenter,
and enterprise monitoring tools to ensure system reliability and optimal performance.}
          \resumeItem{Handled incident, request, and change management with end-to-end ownership using
ServiceNow, ensuring timely resolution, root cause analysis, and adherence to SLAs}     
          \resumeItem{Identified and implemented optimization opportunities in AWS and VMware environments,
including rightsizing EC2 instances, storage optimization, and cost control measures,
contributing to improved resource utilization and reduced operational costs.}
          \resumeItem{Cross-Functional Collaboration: Coordinating with multiple teams to ensure the smooth operation of servers and services.}
          \resumeItem {patch management and vulnerability remediation activities across 
VMware-hosted systems, maintaining security compliance and operational stability.
}
\resumeItem{Designed and implemented Terraform PoC to provision EC2 instances, networking, and storage resources using reusable modules.integrated Terraform state management with AWS S3 backend.}
          \resumeItem{Respond to the emails and tickets raised by customers related to 
Windows Server operations and work towards closure.}  
       
      \resumeItemListEnd
    
  \resumeSubHeadingListEnd
\textbf{Technologies Used:} Cloud Computing, AWS (EC2, VPC, SG, NAT GW, VPC Peering, AWS Backup,snapshots, AMIs, S3 , CloudWatch, IAM )VMware, VMware vSphere (ESXi, vCenter Server), Windows server, linux \\
  
\vspace{-5pt}


%-----------EDUCATION-----------
\section{Education}
  \resumeSubHeadingListStart
    \resumeSubheading
      {Bachelor of Engineering |Sant Gadge Baba Amravati University}{Aug 2017 – Aug 2021}
      {Bachelor of Engineering  $|$ CGPA: 9.95}{Amravati, Maharashtra}
  \resumeSubHeadingListEnd


%-----------CERTIFICATIONS-----------
\section{Certifications}

\textbf{1. AWS Certified Solutions Architect – Associate} – aws.amazon.com  
\textbf{\href{https://cp.certmetrics.com/amazon/en/public/verify/credential/1604b24e201f491eb8dd618ffaad4ba1}{Link}}

\vspace{2pt}

\textbf{2. Associate Cloud Engineer} – Google Cloud  
\textbf{\href{https://google.accredible.com/382a9ad9-04ef-4ff8-981f-7d9e5723128c#acc.pnVTK4ca}{Link}}

\vspace{2pt}

\textbf{3. Complete Windows Server Administration} – Udemy  
\textbf{\href{https://tcsglobal.udemy.com/certificate/UC-a202a500-9c5f-4768-9c74-be59e4bb1b3a/}{Link}}

\vspace{-6pt}

%-----------PROFESSIONAL SKILLS-----------
\section{Professional Skills}

\begin{itemize}[leftmargin=0.15in]
\small{
\item Strong troubleshooting and analytical skills for resolving cloud and infrastructure issues.
\item Reliable and detail-oriented, consistently delivering error-free work with adherence to
processes and standards.
\item Clear communication and teamwork abilities, with experience collaborating across global and
client-facing environments.
\item Able to prioritize and manage multiple operational activities effectively in fast-changing
environments.
\item Adaptable and quick to learn new tools, technologies, and cloud practices.
\item Use authorized AI tools to troubleshoot faster and improve day-to-day efficiency.
\item Demonstrates strong ownership and accountability, proactively driving issues to resolution
and continuously improving operational processes to enhance service quality and system reliability.
}
\end{itemize}

\vspace{-10pt}

\end{document}
