

% Start a document with the here given default font size and paper size.
\documentclass[10pt,a4paper]{article}

% Set the page margins.
\usepackage[a4paper,margin=0.75in]{geometry}

% Setup the language.
\usepackage[english]{babel}
\hyphenation{Some-long-word}

% Makes resume-specific commands available.
\usepackage{resume}




\begin{document}  % begin the content of the document
\sloppy  % this to relax whitespacing in favour of straight margins


% title on top of the document
\maintitle{Jiarui Xu}{}{Last update on \today}

\nobreakvspace{0.3em}  % add some page break averse vertical spacing

% \noindent prevents paragraph's first lines from indenting
% \mbox is used to obfuscate the email address
% \sbull is a spaced bullet
% \href well..
% \\ breaks the line into a new paragraph
\spacedhrule{0.9em}{-0.4em}  % a horizontal line with some vertical spacing before and after

\roottitle{Contact}  % a root section title

\vspace{-1.4em}  % some vertical spacing
\begin{multicols}{2}  % open a multicolumn environment
\noindent
Email: jxu57@illinois.edu\\
Cell: (217) 417-1190\\
Website: \href{http://www.jiaruixu.com}{http://www.jiaruixu.com}\\
\columnbreak
\begin{flushright}
1010 West Stoughton St., Apt. 312, \\
Urbana, IL 61801\\
\end{flushright}
\end{multicols}


\spacedhrule{-1em}{-0.4em}

\roottitle{Education}

\headedsection
  {\href{http://www.illinois.edu}{University of Illinois at Urbana-Champaign}}
  {\textsc{May, 2016}} {%
  \headedsubsection
    {Bachelor of Science in Mathematics and Computer Science, Statistics, Economics}
    {GPA: 3.77}
    {\bodytext{
        \begin{itemize}
            \item Dean's List, LAS Abroad Scholarship
            \item Senior Theses (in progress) on Entity Search with Professor Kevin C. Chang, Wikification and Entity Linking with Professor Dan Roth, Literature Network with Professor James Allison
        \end{itemize}
        }}
        
}

\headedsection
  {\href{http://www.ust.hk}{The Hong Kong University of Science and Technology}}
  {\textsc{Hong Kong, SAR}} {%
  \headedsubsection
    {International Summer Exchange Program}
    {2014 Summer}
    {\bodytext{Coursework in Machine Learning, Internet Computing, Globalization}}
}

\spacedhrule{0.4em}{-0.8em}
\roottitle{Experience}

\headedsection  % sets the header for the section and includes any subsections
  {\href{http://www.epic.com}{Epic Systems Corpration}}
  {\textsc{Verona \& Madison, Wisconsin}} {%
  \headedsubsection
    {Software Developer Intern \textnormal{Predicative Analytics Cogito Data Warehouse}}
    {Apr \apo12 -- present}
    {\bodytext{
        \begin{itemize}
            \item Created de-identification framework to process data for predictive modeling
            \item Designed User Interface and implemented connection with anonymization function library
            \item Researched free-text de-identification methods
        \end{itemize}
    }}
}

\headedsection  % sets the header for a subsection and contains usually body text
  {\href{http://www.ncsa.illinois.edu/}{National Center for Supercomputing Applications} (NCSA)}
  {\textsc{Urbana, Illinois}} {%
  \headedsubsection
    {SPIN Intern \textnormal{(Students Pushing Innovation fellowship program)}} 
    {Jan 2015 -- May 2015}
    {\bodytext{
        \begin{itemize}
            \item Applied CART (Classification And Regression Tree) for crop yields prediction
            \item Researched on using Machine Learning models to analyze the growth pattern of Miscanthus
            \item Supervised by \href{https://sites.google.com/site/dlebauer/}{Dr. David LeBauer}
        \end{itemize}
    }}
}

\headedsection
  {\href{http://www.illinois.edu}{University of Illinois at Urbana-Champaign}}
  {\textsc{Champaign \& Urbana, Illinois}} {%

  \headedsubsection
    {{Course Staff}}
    {Sep 2014 -- Present}
    {\bodytext{
        \begin{itemize}
            \item Grade assignments of CS 446 Machine Learning (2015 Fall)
            \item Design and teach CS 241 System Programming Honor (2015 Fall)
            \item Assist discussion section and grade assignments of CS 374 Algorithms (2015 Fall)
            \item Graded assignments of MATH 231 Calculus II (2014 Fall)
        \end{itemize}
    }}
}


\vspace{-0.2em}
\begin{center}
  \emph{\small Please refer to my \href{http://www.linkedin.com/in/jiaruixu}{Linkedin profile} for a more complete list of work experiences}
\end{center}


\spacedhrule{0.5em}{-0.4em}
\roottitle{Research \& Project}

\headedsection  % sets the header for the section and includes any subsections
  {\href{}{Entity Search in PubMed Corpus}}
  {\textsc{}} {%
  \headedsubsection
    {FORWARD Group \textnormal{Advised by \href{https://wiki.cites.illinois.edu/wiki/display/kevinchang/Kevin+C.+Chang}{Professor Kevin C. Chang}}}
    {Jan 2015 -- Present}
    {\bodytext{
        \begin{itemize}
            \item Implement relation extraction methods using linguistic patterns (POS \& Chunks)
            \item Extract Relation Phrase Candidates for all entity pairs
            \item Research on indexing relation as entities at corpus level
        \end{itemize}
    }}
}




\headedsection  % sets the header for the section and includes any subsections
  {\href{}{Gesture Recognition in Energy Game}}
  {\textsc{}} {%
  \headedsubsection
    {College of Education \textnormal{Advised by  \href{http://www.music.illinois.edu/faculty/guy-garnett}{Prof.Guy Garnett} \& \href{http://education.illinois.edu/faculty/robblind}{Prof.Robb Lindgren}}}
    {Feb 2015 -- May 2015}
    {\bodytext{
        \begin{itemize}
            \item Built OSC connection between Matlab, Unity and Visual Studio
            \item Implemented programs to detect gestures including climbing, eating, punching and jumping 
            \item Part of NSF project: "DIP: Developing Crosscutting Concepts in STEM with Simulation and Embodied Learning"
        \end{itemize}
    }}
}

\headedsection  % sets the header for the section and includes any subsections
  {\href{http://www.math.illinois.edu/~hildebr/fakerandomness/}{Detecting Non-randomness}}
  {\textsc{}} {%
  \headedsubsection
    {Illinois Geometry Lab \textnormal{Advised by \href{http://www.math.uiuc.edu/~hildebr/}{Professor AJ Hildebrand}}}
    {May 2015 -- present}
    {\bodytext{
        \begin{itemize}
            \item Work in a team to develop a suite of statistical tests to detect fake randomness
            \item Scrape and visualize stock market data for pattern identification
            \item Build machine learning classification models to analyze the binary data
            \item Presentations in MAA MathFest 2015, GLU 2015 (incoming: JMM 2016)
        \end{itemize}
    }}
}

\headedsection  % sets the header for the section and includes any subsections
  {\href{http://gear.math.illinois.edu/}{Collaboration Graphs and Cluster Analysis}}
  {\textsc{}} {%
  \headedsubsection
    {Illinois Geometry Lab \textnormal{Advised by \href{http://www.math.uiuc.edu/~bradlow/}{Professor Steven Bradlow}}}
    {May 2015 -- present}
    {\bodytext{
        \begin{itemize}
            \item Collected and parsed authorship and citation data from MathSciNet
            \item Visualize authorship and literature network of GEAR (mathematician network) members
            \item Applied Modularity Clustering and Fast Algorithm to group members in GEAR network
            \item Presentations in Rose-Hulman Undergraduate Mathematics Conference, GLU 2015
        \end{itemize}
    }}
}

\headedsection  % sets the header for the section and includes any subsections
  {\href{}{Sentiment Analysis on Yelp Reviews}}
  {\textsc{}} {%
  \headedsubsection
    {Computational Linguistics courss (LING 406) \textnormal{Instructed by  \href{http://compsem.ai.uiuc.edu/girju/}{Roxana Girju}}}
    {Jan 2015 -- May 2015}
    {\bodytext{
        \begin{itemize}
            \item Constructed a model to predict restaurant ratings based on sentiment analysis of review text
            \item Used Word2Vec (a deep-learning inspired method) to construct word vectors 
            \item Applied Random Forest model for classification using scikit-learn package
        \end{itemize}
    }}
}

\spacedhrule{0.5em}{-0.4em}
\roottitle{Honor \& Award}
  \bodytext{\textbf{Honorable Mention}, Mathematical Contest in Modeling (COMAP) \hfill{April 2015}}
  \bodytext{\textbf{Grand Prize}, 13th "Challenge Cup" National University Academic Science and \\Technology Work Competition ("Olympiad" of Science and Technology for Chinese \\college students) \hfill{September 2013}}
  \bodytext{\textbf{3rd in ranking}, Rose-Hulman Undergraduate Mathematics Conference Hackathon\\ sponsored by Allstate Insurance Company \hfill{April 2015}}
  \bodytext{\textbf{Excellence Award}, ICBC Nationwide University Banking Products Design Contest \hfill{December 2012}}
  \bodytext{\textbf{Dean's List} \hfill{2013 Fall, 2014 Spring, 2015 Spring}}
  \bodytext{\textbf{LAS Abroad Scholarship} \hfill{2013}}
  \bodytext{\textbf{Academics and Technology Scholarship} \hfill{2012}}


\spacedhrule{0.5em}{-0.4em}

\roottitle{Computer Skills}
\vspace{0.5em}
\inlineheadsection
  {Programming \& Scripting:}{ C, C++, C\#, Java, Python, R, MySQL, Transact-SQL, \LaTeX}
\inlineheadsection
  {Web Programming:}{ JavaScript, HTML, CSS, Django framework}
\inlineheadsection
  {Softwares:}{MATLAB, SAS, Mathematica}
\inlineheadsection
  {Operating Systems:}{Linux, Microsoft Windows}


\spacedhrule{1em}{-0.4em}
\roottitle{Presentation}

\headedsection  % sets the header for the section and includes any subsections
  {\normalsize\textbf{Detecting non-randomness: A suite of statistical tests to detect fake coin flips and identify patterns in real-world data}}
  {\textsc{}} {%
  \headedsubsection
    {\textnormal{Joint Mathematics Meetings (JMM)}}
    {Jan.8th, 2016}
    {}
}



\headedsection  % sets the header for the section and includes any subsections
  {\normalsize\textbf{Detecting Non-randomness: How to Detect Fake Coin Flips and Identify Patterns in Real-world Data}}
  {\textsc{}} {%
  \headedsubsection
    {\textnormal{Geometry Labs United (GLU) Conference}}
    {Aug.28th, 2015}
    {}
}

\headedsection  % sets the header for the section and includes any subsections
  {\normalsize\textbf{Detecting Non-randomness: A Suite of Statistical Tests to Detect Fake Coin Flips and Identify Patterns in Real-world Data}}
  {\textsc{}} {%
  \headedsubsection
    {\textnormal{Mathematical Association of America (MAA) MathFest}}
    {Aug.7th, 2015}
    {}
}

\headedsection  % sets the header for the section and includes any subsections
  {\normalsize\textbf{Application of Machine Learning Algorithm in Understanding Growth Pattern of Miscanthus}}
  {\textsc{}} {%
  \headedsubsection
    {\textnormal{NCSA SPIN Poster Session}}
    {Apr.29th, 2015}
    {}
}

\headedsection  % sets the header for the section and includes any subsections
  {\normalsize\textbf{Predictive Analytics Competition (winners' talks)}}
  {\textsc{}} {%
  \headedsubsection
    {\textnormal{Rose-Hulman Institute of Technology Undergraduate Mathematics Conference}}
    {Apr.24th, 2015}
    {}
}

\headedsection  % sets the header for the section and includes any subsections
  {\normalsize\textbf{Collaboration Graph and Cluster Analysis}}
  {\textsc{}} {%
  \headedsubsection
    {\textnormal{Rose-Hulman Institute of Technology Undergraduate Mathematics Conference}}
    {Apr.24th, 2015}
    {}
}

\headedsection  % sets the header for the section and includes any subsections
  {\normalsize\textbf{Text Information Retrieval and NLP (FlagWall, PURE program project)}}
  {\textsc{}} {%
  \headedsubsection
    {\textnormal{PURE Research Symposium}}
    {Dec.4th, 2014}
    {}
}

\spacedhrule{1.6em}{-0.4em}
\roottitle{Others}

\inlineheadsection
  {Time management:}
  {Have taken 32 credits in Spring 2015}
\inlineheadsection
  {Interests:}
  {Basketball, Calligraphy, Chinese Painting, Cooking, Kayaking, Movies, Study Broad, The Big Bang Theory (TV Show), Three Kingdom (board game), Traveling, Voluntary Trips, Warcraft III, Watching funny videos}


\end{document}

% cv from template file on ShareLatex

＀
