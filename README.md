# Technician Installation Survey

This is a simple web-based survey application used by field technicians to collect installation information. The app allows the technician to enter data for equipment, network configurations, workstation setup, and more. The data can then be saved as a PDF document for reporting purposes.

## Features
- Collects installation details like equipment ID, make/model, network information, IT setup, and more.
- Allows for dynamic addition of devices and related information.
- Uses [jsPDF](https://github.com/parallax/jsPDF) to generate and download a PDF of the survey results.

## How to Access
You can access the app via the following URL:

[Tech Install Survey](https://brobinson404.github.io/Tech-Install-Survey/)

## Screenshots

### Application Interface
![App Screenshot](![Field Tech Survery 1](https://github.com/user-attachments/assets/804f9cb1-809e-4990-a954-a01304be99b9)
)

### Generated PDF Example
![PDF Screenshot](![Field Tech Survey 2](https://github.com/user-attachments/assets/b0c83953-d2ae-433c-b9e0-6ee898a09494)
)

## Technologies Used
- HTML5
- JavaScript
- jsPDF (for PDF generation)

## How It Works
1. Enter customer and device information into the form.
2. Add multiple devices as needed by clicking the "Add Another Device" button.
3. Once the survey is completed, click "Save as PDF" to generate the document.
4. The resulting PDF will be named with the customer's name and the date of the survey.

## Installation
To run this app locally:
1. Clone the repository:
   ```bash
   git clone https://github.com/brobinson404/Tech-Install-Survey.git
