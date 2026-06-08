## Learning Outcomes Assessment App

This repository contains the files required to run and test a web-based application for Learning Outcomes assessment.

The application was developed to support academic assessment processes through an institutional Excel matrix, course-specific test files, automated analysis, and Excel report generation. It allows users to connect academic programs, courses, and Learning Outcomes in a single browser-based environment.

The system is intended for academic programs that need to organize assessment evidence, analyze student performance, review Learning Outcome achievement, and generate structured reports for curriculum monitoring, institutional improvement, or accreditation-related processes.

## 1. Purpose of the Repository

The main purpose of this repository is to provide a functional web application and the required supporting files for Learning Outcomes assessment.

The repository allows users to:

* Open the assessment application directly in a web browser.
* Load the institutional assessment matrix from Excel.
* Select an academic program and course.
* Display the Learning Outcomes associated with the selected course.
* Use course-specific test files to validate the assessment workflow.
* Analyze academic performance based on Learning Outcomes.
* Generate institutional analysis from the processed data.
* Export the results to an Excel report.

The application is not intended to replace official academic information systems. Instead, it is designed as a complementary tool for academic analysis, evidence organization, and curriculum assessment.

## 2. Repository Contents

The repository contains the following main files and folders:

* `RA_App_Robusta_ConAnalisis_y_IA...html`
* `AssesmentRACircuitos.xlsx`
* `Pruebas Campos Elec/`
* `Pruebas Circuitos Digitales 1/`
* `Pruebas Circuitos Digitales 2/`
* `Pruebas Digital Signal P 1/`
* `Pruebas Electronica III/`

The HTML file contains the web application. The Excel file contains the institutional assessment matrix. The folders contain test files organized by course.

## 3. Main Application File

The file `RA_App_Robusta_ConAnalisis_y_IA...html` contains the complete web application.

This file includes the user interface, the Excel loading process, the Learning Outcomes reading logic, the academic analysis functions, and the Excel export option.

The application runs locally in a browser. No database, server installation, or additional software is required for basic use.

Users should open this file in a modern browser such as Google Chrome, Microsoft Edge, or Mozilla Firefox.

## 4. Institutional Assessment Matrix

The file `AssesmentRACircuitos.xlsx` is the institutional assessment matrix used by the application.

This file defines the academic structure that the app reads when it starts the assessment process. It contains the information required to connect programs, courses, and Learning Outcomes.

The application uses this file to load:

* Academic programs.
* Courses.
* Learning Outcomes.
* Relationships between courses and Learning Outcomes.

This file is required for the application to work correctly. If the structure, sheet names, or column names of this Excel file are changed, the application code may also need to be updated.

## 5. Course Test Folders

The repository includes several test folders. Each folder contains files associated with a specific course or subject area. These files are used to verify that the application can load, process, analyze, and export assessment information correctly.

### 5.1 Pruebas Campos Elec

The folder `Pruebas Campos Elec/` contains test files for the Electric Fields or Electromagnetic Fields course.

These files are used to validate the assessment workflow for this course and to verify that the app can process the corresponding Learning Outcomes and assessment information.

### 5.2 Pruebas Circuitos Digitales 1

The folder `Pruebas Circuitos Digitales 1/` contains test files for Digital Circuits I.

These files are used to test the course selection process, the display of Learning Outcomes, the academic analysis, and the Excel export for this course.

### 5.3 Pruebas Circuitos Digitales 2

The folder `Pruebas Circuitos Digitales 2/` contains test files for Digital Circuits II.

These files provide an additional validation scenario and help verify that the application works consistently with different course data.

### 5.4 Pruebas Digital Signal P 1

The folder `Pruebas Digital Signal P 1/` contains test files for Digital Signal Processing I.

These files are used to validate the assessment workflow for a course related to signal processing and technical performance analysis.

### 5.5 Pruebas Electronica III

The folder `Pruebas Electronica III/` contains test files for Electronics III.

These files help verify the processing of assessment data, the relationship between the course and its Learning Outcomes, and the generation of academic reports.

## 6. General Workflow

The application follows a simple assessment workflow.

First, the user opens the HTML application in a browser. Then, the institutional Excel matrix is loaded. After that, the user selects the academic program and the course to be analyzed. The application displays the Learning Outcomes assigned to the selected course and allows the user to process the corresponding assessment information.

Once the data has been processed, the application generates academic indicators, institutional analysis, and an Excel report that can be used as assessment evidence.

The general workflow is:

1. Open the HTML application.
2. Load `AssesmentRACircuitos.xlsx`.
3. Select the academic program.
4. Select the course.
5. Verify that the Learning Outcomes are displayed correctly.
6. Use the corresponding course test files.
7. Generate the academic analysis.
8. Export the results to Excel.
9. Save the exported report as institutional evidence.

## 7. How to Use the Application

The application is designed to run directly from a web browser. The user does not need to install a database, configure a server, or manually load the institutional assessment matrix.

The file AssesmentRACircuitos.xlsx is already included in the repository and is automatically loaded by the application when the system starts. This file contains the institutional structure required to display academic programs, courses, and Learning Outcomes.

The user workflow consists of six main stages:

Open the web application.
Wait for the institutional matrix to load automatically.
Select the academic program.
Select the course.
Enter the assessment grades in the application table.
Generate the analysis locally or with AI support.
Export the final Excel report.
7.1 Open the Application

To start using the system, open the main HTML file in a modern web browser:

RA_App_Robusta_ConAnalisis_y_IA...html

Recommended browsers are Google Chrome, Microsoft Edge, or Mozilla Firefox.

If the application is published through GitHub Pages, the user can open it directly from the public GitHub Pages link.

For GitHub Pages deployment, it is recommended to rename the main HTML file as:

index.html

This allows GitHub Pages to open the application automatically as the main page of the repository.

7.2 Automatic Loading of the Institutional Matrix

When the application starts, it automatically loads the institutional Excel file:

AssesmentRACircuitos.xlsx

The user does not need to upload this file manually.

This file provides the academic structure used by the app, including:

Academic programs.
Courses.
Learning Outcomes.
Relationships between courses and Learning Outcomes.

After the automatic loading process is completed, the program and course selection options become available in the interface.

If the programs or courses do not appear, the user should verify that AssesmentRACircuitos.xlsx is located in the correct repository path and that the file name has not been changed.

7.3 Select the Academic Program

After the institutional matrix has been loaded automatically, the user must select the academic program to be analyzed.

The program selection allows the app to filter the available courses according to the selected academic structure.

Once the program is selected, the corresponding list of courses becomes available.

7.4 Select the Course

After selecting the academic program, the user must select the course to be analyzed.

Once the course is selected, the application displays the Learning Outcomes assigned to that course.

This step confirms that the course and its Learning Outcomes were correctly read from the institutional Excel matrix.

If the selected course does not display Learning Outcomes, the user should verify that the course has Learning Outcomes correctly assigned in AssesmentRACircuitos.xlsx.

7.5 Enter the Assessment Grades

After selecting the course, the user must enter the assessment grades directly in the application table.

The grade table is organized according to the assessment structure of the course. The user should complete the available cells with the corresponding student grades or assessment values.

The grades should be entered according to the institutional grading scale used by the application. In the current institutional configuration, the expected scale is from 0 to 50.

The user should verify that:

Each grade is entered in the correct cell.
The values correspond to the correct assessment period or component.
The entered values use the expected numerical format.
Empty cells are avoided when they correspond to required assessment data.
The grades are consistent with the selected course and Learning Outcomes.

The application uses the entered grades to calculate academic indicators and to generate the Learning Outcomes assessment analysis.

7.6 Review the Entered Data

Before generating the analysis, the user should review the information displayed in the app.

The user should confirm:

The selected academic program.
The selected course.
The Learning Outcomes displayed for the selected course.
The grades entered in the assessment table.
The consistency between the grades and the assessment structure.

This review is important because the analysis and the exported Excel report are generated from the information entered in the application.

If a grade is missing or entered incorrectly, the user should correct it before generating the analysis.

7.7 Generate the Local Analysis

The application can generate a local academic analysis using the data entered by the user.

The local analysis is produced by the application without using external AI services. It is based on the internal calculations, indicators, and assessment rules implemented in the app.

The local analysis may include:

General course performance.
Learning Outcome achievement.
Results by assessment period.
Academic risk indicators.
Performance trends.
Institutional interpretation based on the calculated results.

This option is useful when the user wants to process the information directly in the browser without depending on external AI providers.

The local analysis should be reviewed before exporting the final report.

7.8 Generate the AI-Assisted Analysis

The application also supports AI-assisted analysis when the corresponding API services are configured.

The AI-assisted analysis uses the results calculated by the application and generates a written academic interpretation with the support of an external AI provider.

Depending on the configuration, the app may support services such as:

Gemini.
Groq.
OpenRouter.

To use the AI-assisted analysis, the user must select the desired AI provider in the application and make sure that the corresponding API configuration is available.

The AI-assisted analysis does not replace the numerical calculations performed by the application. The app first processes the grades and calculates the academic indicators. Then, the AI layer uses those results to produce a clearer institutional interpretation.

For researchers who wish to reproduce the AI-assisted analysis tests but do not have their own API key, the authors may provide temporary API keys upon reasonable request. These keys are intended only for academic testing, reproducibility, and validation of the application workflow. Users are expected to use them responsibly and with discretion, avoiding unnecessary requests, excessive consumption, public disclosure, or inclusion of the keys in public repositories. For long-term use, institutional deployment, or extensive experimentation, users are strongly encouraged to configure their own API keys.
Gemini:  AIzaSyBtbvE-f6yZE-viUvzicsAKy8ju9YSMF2w
Grok:  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
Open Router:  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


The AI-assisted analysis may help describe:

The general academic performance of the group.
The level of Learning Outcome achievement.
Strengths and weaknesses observed in the results.
Possible academic risk patterns.
Recommendations for improvement.
Institutional interpretation of the assessment evidence.

If the AI service does not respond, the user can still use the local analysis and export the report with the results generated by the application.

7.9 Export the Excel Report

After entering the grades and generating the analysis, the user can export the final report to Excel.

The exported Excel file may include:

Program information.
Course information.
Learning Outcomes.
Entered grades.
Assessment results.
Academic indicators.
Local analysis.
AI-assisted analysis, if generated.
Institutional interpretation and recommendations.

The exported report can be used as academic evidence for course assessment, curriculum monitoring, institutional reporting, academic committees, or accreditation-related processes.

7.10 Recommended User Workflow

The recommended workflow is:

Open the web application.
Wait for AssesmentRACircuitos.xlsx to load automatically.
Select the academic program.
Select the course.
Verify that the Learning Outcomes appear correctly.
Enter the assessment grades in the application table.
Review the entered grades.
Generate the local analysis.
If required, generate the AI-assisted analysis.
Review the generated interpretation.
Export the Excel report.
Save the exported file as academic evidence.

## 7. Basic Validation Before Using Official Data

Before using the application with official institutional data, the user should test the complete workflow.

The user should verify that:

The application opens correctly in the browser.
AssesmentRACircuitos.xlsx loads automatically.
The academic programs appear correctly.
The courses appear correctly.
The selected course displays its Learning Outcomes.
The grade table is available for data entry.
The entered grades are processed correctly.
The local analysis is generated.
The AI-assisted analysis is generated, if enabled.
The Excel report is exported correctly.
The exported report is readable and complete.

If any of these steps fails, the user should first check that AssesmentRACircuitos.xlsx is still available in the repository, that the file name has not been modified, and that the selected course has Learning Outcomes correctly assigned in the institutional matrix.

## 8. Expected Results

When the application is used correctly, it should allow the user to:

* Load the institutional Excel matrix without errors.
* Display the available academic programs.
* Display the available courses.
* Show the Learning Outcomes assigned to the selected course.
* Process the assessment information.
* Generate academic indicators.
* Produce an institutional interpretation of the results.
* Export a readable Excel report.

The exported report can be used for course assessment, curriculum monitoring, academic committees, institutional reporting, or accreditation-related documentation.

## 9. Recommendations for Use

Before using the application with official institutional data, users should test the complete workflow with the files included in the course test folders.

This helps verify that the Excel matrix, the course structure, the Learning Outcomes, and the report export process work correctly.

Users should not modify the structure of `AssesmentRACircuitos.xlsx` unless they also update the application code. The app depends on the structure of this file to identify programs, courses, and Learning Outcomes.

If AI-assisted analysis is enabled, private API keys should not be published in a public GitHub repository. For public deployment, a secure configuration method should be used.

## 10. GitHub Pages Recommendation

If the application will be published using GitHub Pages, it is recommended to rename the main HTML file as `index.html`.

GitHub Pages automatically opens `index.html` as the main page of the repository. This makes it easier for users to access the application through the public GitHub Pages link.

A recommended structure for GitHub Pages is:

* `index.html`
* `AssesmentRACircuitos.xlsx`
* `Pruebas Campos Elec/`
* `Pruebas Circuitos Digitales 1/`
* `Pruebas Circuitos Digitales 2/`
* `Pruebas Digital Signal P 1/`
* `Pruebas Electronica III/`

Renaming the HTML file is not required for local use, but it is recommended for web publication.

## 11. Scope and Limitations

This application is a support tool for Learning Outcomes assessment. It helps organize, analyze, interpret, and export academic assessment evidence.

The application does not replace official grading platforms, institutional academic systems, or formal evaluation procedures. Final academic decisions should be reviewed by faculty members, program coordinators, or institutional assessment committees.

The quality of the results depends on the consistency of the institutional matrix, the accuracy of the assessment data, and the correct use of the application workflow.

## 12. Suggested Repository Description

Web application for Learning Outcomes assessment using an institutional Excel matrix, course-specific test files, academic analysis, and Excel report export.

## 13. Suggested GitHub Topics

Suggested topics for this repository include:

* learning-outcomes
* assessment
* curriculum-assessment
* academic-analytics
* engineering-education
* excel
* javascript
* html
* institutional-reporting
* ai-assisted-analysis

## 14. License

A formal license should be added before public distribution.

For open academic reuse, an MIT License may be appropriate. For internal institutional use, an institutional license may be preferred. If derivative works should remain open source, a GPL License may be considered.

## 15. Summary

This repository provides a browser-based Learning Outcomes assessment application, an institutional Excel matrix, and course-specific test folders.

The app supports the loading of academic structures, the selection of programs and courses, the visualization of Learning Outcomes, the processing of assessment data, the generation of academic analysis, and the export of results to Excel.

It is designed to support academic assessment, curriculum monitoring, institutional evidence generation, and continuous improvement processes.
