# health-insurance-cross-sell-prediction

\documentclass[12pt]{article}
\usepackage{geometry}
\geometry{a4paper, margin=1in}
\usepackage{hyperref}

\begin{document}

\title{\textbf{Predicting Vehicle Insurance Interest Among Health Policyholders}}
\author{}
\date{}
\maketitle

\section*{Overview}
This project aims to predict vehicle insurance interest among health policyholders, providing actionable insights into customer behavior and potential engagement strategies.

\section*{Analysis Features}
\begin{enumerate}
    \item \textbf{Problem Understanding and Hypothesis}: Laying the groundwork for predictive insights.
    \item \textbf{Exploratory Data Analysis (EDA)}:
    \begin{itemize}
        \item Analysis of trends, traits, and feature distributions.
        \item Development of customer personas.
        \item Identification of potential engagement channels.
    \end{itemize}
    \item \textbf{Feature Engineering}:
    \begin{itemize}
        \item Techniques such as binning and categorical encoding.
    \end{itemize}
    \item \textbf{Feature Selection}:
    \begin{itemize}
        \item Insights from EDA and statistical methods (e.g., \texttt{mutual\_info\_classif}).
    \end{itemize}
    \item \textbf{Imbalance Handling}:
    \begin{itemize}
        \item Oversampling using SMOTE and ADASYN.
    \end{itemize}
    \item \textbf{Model Development and Evaluation}:
    \begin{itemize}
        \item Algorithm selection and optimization.
        \item Evaluation metrics: PR AUC, F1 score, precision, recall (emphasizing false negatives).
    \end{itemize}
    \item \textbf{Feature Importance and Prediction}:
    \begin{itemize}
        \item Identification of key predictors for better targeting.
    \end{itemize}
\end{enumerate}

\section*{Outcome}
\begin{itemize}
    \item Recommendations to improve customer engagement and raise vehicle insurance interest.
\end{itemize}

\end{document}
