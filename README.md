%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
% Developer CV
% LaTeX Template
% Version 1.0 (28/1/19)
%
% This template originates from:
% http://www.LaTeXTemplates.com
%
% Authors:
% Jan Vorisek (jan@vorisek.me)
% Based on a template by Jan Küster (info@jankuester.com)
% Modified for LaTeX Templates by Vel (vel@LaTeXTemplates.com)
%
% License:
% The MIT License (see included LICENSE file)
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

%----------------------------------------------------------------------------------------
%	PACKAGES AND OTHER DOCUMENT CONFIGURATIONS
%----------------------------------------------------------------------------------------

\documentclass[9pt]{developercv} % Default font size, values from 8-12pt are recommended

%----------------------------------------------------------------------------------------

\begin{document}

%----------------------------------------------------------------------------------------
%	TITLE AND CONTACT INFORMATION
%----------------------------------------------------------------------------------------

\begin{minipage}[t]{0.45\textwidth} % 45% of the page width for name
	\vspace{-\baselineskip} % Required for vertically aligning minipages
	
	% If your name is very short, use just one of the lines below
	% If your name is very long, reduce the font size or make the minipage wider and reduce the others proportionately
	\colorbox{black}{{\HUGE\textcolor{white}{\textbf{\MakeUppercase{Yi Tian (Leo)}}}}} % First name
	
	\colorbox{black}{{\HUGE\textcolor{white}{\textbf{\MakeUppercase{Liu}}}}} % Last name
	
	\vspace{6pt}
	
	{\huge Software Engineer} % Career or current job title
\end{minipage}
\begin{minipage}[t]{0.275\textwidth} % 27.5% of the page width for the first row of icons
	\vspace{-\baselineskip} % Required for vertically aligning minipages
	
	% The first parameter is the FontAwesome icon name, the second is the box size and the third is the text
	% Other icons can be found by referring to fontawesome.pdf (supplied with the template) and using the word after \fa in the command for the icon you want
	\icon{MapMarker}{12}{Richmond, BC, Canada}\\
	\icon{Phone}{12}{+1 604 724 9000}\\
	\icon{At}{12}{\href{mailto:leoyitianliu@gmail.com}{leoyitianliu@gmail.com}}\\	
\end{minipage}
\begin{minipage}[t]{0.275\textwidth} % 27.5% of the page width for the second row of icons
	\vspace{-\baselineskip} % Required for vertically aligning minipages
	
	% The first parameter is the FontAwesome icon name, the second is the box size and the third is the text
	% Other icons can be found by referring to fontawesome.pdf (supplied with the template) and using the word after \fa in the command for the icon you want
	\icon{Globe}{12}{\href{https://leoyitianliu.com}{leoyitianliu.com}}\\
	\icon{Github}{12}{\href{https://github.com/illidan333}{github.com/illidan333}}\\
	\icon{Twitter}{12}{\href{https://twitter.com/@leoyitianliu}{@leoyitianliu}}\\
\end{minipage}

\vspace{0.5cm}

%----------------------------------------------------------------------------------------
%	INTRODUCTION, SKILLS AND TECHNOLOGIES
%----------------------------------------------------------------------------------------

\cvsect{Who Am I?}

\begin{minipage}[t]{0.4\textwidth} % 40% of the page width for the introduction text
	\vspace{-\baselineskip} % Required for vertically aligning minipages
	Over 10 years of work experience in IT\newline\newline
    Specialized in Full Stack WebDev\newline\newline
    Expert in both on-premises and cloud
\end{minipage}
\hfill % Whitespace between
\begin{minipage}[t]{0.5\textwidth} % 50% of the page for the skills bar chart
	\vspace{-\baselineskip} % Required for vertically aligning minipages
	\begin{barchart}{5.5}
		\baritem{JavaScript}{80}
		\baritem{PHP}{80}
		\baritem{MySQL}{90}
		\baritem{CSS}{70}
	\end{barchart}
\end{minipage}

\begin{center}
	\bubbles{4/Laravel, 5/RESTful, 6/Git, 4/SCSS, 6/React, 3/Redux, 3/PostgreSQL, 4/Linux, 4/Scalability, 6/SASS}
\end{center}

%----------------------------------------------------------------------------------------
%	EXPERIENCE
%----------------------------------------------------------------------------------------

\cvsect{Experience}

\begin{entrylist}
	\entry
		{2022 -- 2024\\\footnotesize{full time}}
		{Senior Software Engineer}
		{Offworld Industries}
		{
            - Delivered a web application called \textit{Robomerge} to boost development productivity by 90\%\newline
            - Led website and game web services development and operation to increase reliability by 40\%\newline
            \texttt{PostgreSQL}\slashsep\texttt{React}\slashsep\texttt{TypeScript}\slashsep\texttt{AWS}\slashsep\texttt{Git}
        }
	\entry
		{2016 -- 2022\\\footnotesize{full time}}
		{Intermediate Software Engineer}
		{Readymode}
		{
            - Built a infra provision tool to help the company to save engineers 100+ hours per week\newline
            - Built a deployment tool to help the company to increase system reliability by 200\%\newline
            - Led a team to build a sales pipeline system to help users to grow their sales by 200\%\newline
            - Led a team to create a gamification system to train 100k+ users to learn software features\newline
            - Led a team to create an advance search system to improve lead info search speed by 70+ \%\newline
            - Built a licensing system to help the company to collect 30+ thousands dollars missing revenue\newline
            - Built a licensing system to help the company to collect 30+ thousands dollars missing revenue\newline
            - Created a system to track tech support agents stat to reduce management workload by 80\%\newline
            \texttt{PHP}\slashsep\texttt{Python}\slashsep\texttt{MySQL}\slashsep\texttt{Linux}\slashsep\texttt{Ansible}
            \slashsep\texttt{AWS}\slashsep\texttt{CSS}\slashsep\texttt{Laravel}\slashsep\texttt{React}
        }
	\entry
		{2014 -- 2016\\\footnotesize{full time}}
		{Junior Software Engineer}
		{Readymode}
		{
            - Developed a payment website to help over 1000+ clients to make payment online easily\newline
            - Developed call center data reports to improved data visibility to gain 100+ user complements\newline
            \texttt{PHP}\slashsep\texttt{JavaScript}\slashsep\texttt{CSS}\slashsep\texttt{JQuery}\slashsep\texttt{MySQL}
        }
\end{entrylist}

%----------------------------------------------------------------------------------------
%	EDUCATION
%----------------------------------------------------------------------------------------

\cvsect{Education}

\begin{entrylist}
	\entry
		{2008 -- 2012}
		{Bachelor's Degree}
		{University of British Columbia}
		{Computer Engineering Software Option}
	\entry
		{2018}
		{Professional Training}
		{Agile 42}
		{Introduction to Agile and Scrum}
	\entry
		{2019}
		{Online Course}
		{CloudxLab}
		{Introduction on Deep Learning}
\end{entrylist}

%----------------------------------------------------------------------------------------
%	ADDITIONAL INFORMATION
%----------------------------------------------------------------------------------------

\begin{minipage}[t]{0.3\textwidth}
	\vspace{-\baselineskip} % Required for vertically aligning minipages

	\cvsect{Languages}
	
	\textbf{English} - native\\
	\textbf{Chinese} - native\\
\end{minipage}
\hfill
\begin{minipage}[t]{0.3\textwidth}
	\vspace{-\baselineskip} % Required for vertically aligning minipages
	
	\cvsect{Hobbies}
	
	I love build website and software to help my friends to run their business and automate some of my daily tasks.
\end{minipage}
\hfill
\begin{minipage}[t]{0.3\textwidth}
	\vspace{-\baselineskip} % Required for vertically aligning minipages
	
	\cvsect{Non profit}
	
	I volunteer at a non-profit organization called \textit{Career Up Club} to help them organize event and develop and operate their online presences.
\end{minipage}

%----------------------------------------------------------------------------------------

\end{document}
