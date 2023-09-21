<h1 align="center">SMART INDIA HACKATHON 2023</h1>
<h2 align="center">Tekathon 2.0 @ Chandigarh University (CU)</h2>
<h3 align="center">Domain - Blockchain & Cybersecurity (SIH1455)</h3>

# Problem Statement
*Create an intelligent system using AI/ML to detect phishing domains which imitate look and feel of genuine domains.*

## Overview

Phishing Domain Detection is an intelligent system that uses AI/ML, specifically a Random Forest Classifier, to identify potentially malicious domains that imitate genuine ones. This README provides an overview of the project's components, procedures, and progress up to the current stage.

## Table of Contents

- [Overview](#overview)
- [Components](#components)
- [Procedure](#procedure)
- [User Interface](#ui-screenshot)
- [Accuracy Comparison](#accuracy-comparison)
- [UI Screenshot](#ui-screenshot)
- [Contributors](#contributors)

## Components

Our project comprises several key components:

1. **Machine Learning Model**: We employ a Random Forest Classifier to analyze URLs and classify them as either phishing or legitimate based on learned patterns.

2. **Docker Containerization**: URLs flagged as potentially malicious are opened within secure Docker containers to isolate any threats.

3. **User Interface**: A user-friendly web interface allows users to input URLs for analysis with real-time feedback.

## Procedure

The project's workflow involves:

1. User submits a URL via the UI.
2. The URL is sent to the machine learning model for analysis.
3. The model classifies the URL as phishing or legitimate.
4. If flagged as potentially malicious, the URL is executed within a Docker container for security.
5. Real-time feedback is provided to the user.

## Accuracy Comparison

Our model aims for an accuracy rate exceeding 91.4%. We continuously refine the model using feedback from users. 
In addition to our model's accuracy, let's compare it to other machine learning models commonly used in the field. Here are some of the models we have tested:

1. Logistic Regression - 86%
2. Support Vector Machine (SVM) - 82%
3. Decision Tree - 90%
4. Naïve Bayes Classifier - 78%

## UI Screenshot
<p align="center">URL Input (Main Page) </p>
<p align="center">
  <img src="https://github.com/cu-sanjay/crispy-octo-happiness/assets/96792511/d20768b4-b3bf-4932-90ac-d9b3d8c67912" width="500" alt="Team Phoenix UI INPUT">
</p>
<p align="center">1. Output - Safe/Legitimate <b>[https://www.youtube.com]</b></p>
<p align="center">
  <img src="https://github.com/cu-sanjay/crispy-octo-happiness/assets/96792511/113ce1e8-8155-4e56-9421-0d00b2ef9d8f" width="500" alt="Team Phoenix UI OUTPUT 1">
</p>
<p align = "center"> 2. Output - Phishing/Malicious <b>[https://www.y0utube.com]</b></p>
<p align="center">
  <img src="https://github.com/cu-sanjay/crispy-octo-happiness/assets/96792511/5877af49-e77e-4e90-9eb7-7b5941ade9da" width="500" alt="Team Phoenix UI OUTPUT 2">
</p>

## Ongoing and Future Work

Our project is continually evolving, with several key implementation enhancements in progress. Here's a glimpse of what we're currently working on and what you can expect in the future:

1. **Integration with User Interface (UI)**:
   - We're in the process of seamlessly integrating our AI/ML model with the user interface. This will allow users to conveniently check URLs and receive real-time feedback.

2. **Blockchain Integration with Smart Contracts**:
   - Our blockchain integration is taking shape with the development of Smart Contracts using Solidity. This will ensure immutable and secure storage of analysis results and user feedback.

3. **Real-Time Detection (Automation)**:
   - We're working on automating the detection process to replace manual checking of doubtful URLs. Real-time scanning will provide instant alerts and enhanced protection.

4. **Browser Extensions**:
   - We have plans to extend our project's reach by developing browser extensions. This will allow users to check URLs directly from their browsers.

5. **Mobile Application Development**:
   - In the pipeline is the development of mobile applications to provide users with on-the-go URL analysis and protection.

These ongoing efforts aim to make our phishing domain detection system more advanced, user-friendly, and effective in countering evolving cybersecurity threats.

### Contributors

Our project is a collaborative effort by a dedicated team. Here are the team members with their GitHub profiles:

1. [Himanshu Singla - GitHub Profile](insert-Jane's-GitHub-link-here)
2. [Sanjay Choudhary - GitHub Profile](insert-Sam's-GitHub-link-here)
3. [Bikash Kumar - GitHub Profile](insert-Michael's-GitHub-link-here)
4. [Mayank Kumar - GitHub Profile](insert-Emily's-GitHub-link-here)
5. [Raghav - GitHub Profile](insert-Emily's-GitHub-link-here)
6. [Muskan Agarwal - GitHub Profile](insert-Emily's-GitHub-link-here)
