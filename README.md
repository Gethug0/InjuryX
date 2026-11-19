# InjuryX
AI-powered athlete injury risk analysis platform that evaluates sleep, resting heart rate, nutrition and training load to identify potential injury risks.


## Project Overview

InjuriX is a smart athlete injury-risk analysis platform designed to evaluate lifestyle, recovery and training-related factors that may influence an athlete's injury risk.

The application analyses important athlete parameters, including sleep duration, resting heart rate, nutritional intake and training hours. Using a weighted rule-based assessment approach, it evaluates the submitted information and generates an estimated injury-risk level.

The primary objective is to help athletes understand the relationship between recovery, nutrition and training load through an accessible digital platform.

## Live Demo

**Project Link:** https://happy-body-scan.lovable.app/

## Problem Statement

Athletes regularly experience physical stress due to intensive training, insufficient recovery, inadequate nutrition and irregular sleep patterns.

Without consistent monitoring, these factors may contribute to increased physical strain and potential injury risks.

InjuriX aims to provide a digital platform that evaluates these factors and presents understandable risk-assessment insights.

## Project Objectives

- Evaluate athlete lifestyle and training parameters.
- Analyse sleep and recovery patterns.
- Monitor resting heart rate.
- Assess nutritional intake.
- Evaluate training intensity and duration.
- Generate estimated injury-risk levels.
- Promote awareness of recovery and athlete wellness.

## Key Features

### 1. Athlete Data Input
Allows users to enter relevant lifestyle and training information.

### 2. Sleep Analysis
Evaluates sleep duration as one of the recovery-related parameters.

### 3. Heart Rate Monitoring
Uses resting heart rate information as an input for risk assessment.

### 4. Nutrition Analysis
Considers nutritional and calorie-related information.

### 5. Training Load Assessment
Evaluates training duration and workload.

### 6. Risk Assessment
Uses a weighted rule-based system to evaluate submitted parameters.

### 7. Risk-Level Results
Displays an estimated risk category based on the assessment logic.

## Parameters Analysed

| Parameter | Purpose |
|---|---|
| Sleep Duration | Recovery assessment |
| Resting Heart Rate | Physiological indicator |
| Nutrition / Calories | Nutritional intake assessment |
| Training Hours | Training workload assessment |

## Technology Stack

The following technologies are associated with the project. Exact versions and implementation details should be confirmed from the source code.

| Technology                   | Application 
| React                        | Frontend user interface 
| TypeScript / JavaScript      | Application programming 
| HTML5                        | Web structure 
| CSS3                         | Styling and layout 
| Supabase                     | Backend and database services, where configured 
| Lovable                      | Initial application development 

## Risk Assessment Methodology

InjuriX uses a weighted rule-based assessment approach.

The application evaluates multiple input parameters and processes them according to predefined conditions and weights.

The assessment produces an estimated risk category.

The system is intended for educational and awareness purposes. It is not a clinically validated injury prediction model.

## Application Workflow

1. User accesses the InjuriX platform.
2. User enters athlete-related information.
3. The application processes the submitted parameters.
4. The risk-assessment logic evaluates the inputs.
5. The platform presents the resulting risk category.

## Project Structure

The repository structure will reflect the actual application source code.

Example:

```text
InjuriX-Smart-Injury-Risk-Analysis/
│
├── public/
├── src/
│   ├── assets/
│   ├── components/
│   ├── pages/
│   ├── hooks/
│   ├── integrations/
│   ├── App.tsx
│   ├── main.tsx
│   └── index.css
│
├── supabase/
├── README.md
├── package.json
├── package-lock.json
├── index.html
└── .gitignore
```

## Installation and Setup

### Prerequisites

- Node.js
- npm
- Git
- Code editor such as Visual Studio Code

### Step 1: Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/InjuriX-Smart-Injury-Risk-Analysis.git
```

### Step 2: Navigate to the Project

```bash
cd InjuriX-Smart-Injury-Risk-Analysis
```

### Step 3: Install Dependencies

```bash
npm install
```

### Step 4: Configure Environment Variables

If the project requires Supabase credentials, configure the environment variables using the names expected by the application.

Never upload private API keys or service-role keys to GitHub.

### Step 5: Run the Application

```bash
npm run dev
```

## Future Enhancements

- Integration with wearable fitness devices.
- Athlete activity tracking.
- Advanced recovery analysis.
- Historical assessment reports.
- Personalised athlete dashboards.
- Machine learning-based risk assessment after appropriate model development and validation.

## Applications

- Athlete wellness monitoring.
- Sports training awareness.
- Recovery tracking.
- Educational sports analytics.

## Live Application

https://happy-body-scan.lovable.app/
