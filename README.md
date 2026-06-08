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

To use the application, open the file `RA_App_Robusta_ConAnalisis_y_IA...html` in a web browser.

After the application opens, load the file `AssesmentRACircuitos.xlsx` using the Excel loading option available in the interface.

Once the Excel file has been loaded, select the academic program. Then select the course that will be analyzed. The application should display the Learning Outcomes associated with that course.

After verifying that the Learning Outcomes are shown correctly, use the corresponding test files from the course folder. For example, use the files in `Pruebas Circuitos Digitales 1/` when testing Digital Circuits I, or the files in `Pruebas Electronica III/` when testing Electronics III.

Finally, review the generated analysis and export the results to Excel.

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
