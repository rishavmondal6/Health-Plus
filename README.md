Live Hosting Link - https://gentle-haupia-3bf3a8.netlify.app/

🏥 Health Plus - Medical Report Generator Health Plus is a web-based medical report generation system that allows diagnostic centers or healthcare professionals to create, preview, and download detailed medical reports in PDF format. The application includes a structured form for patient data collection and automatically generates a stylized, printable medical report complete with a QR code, lab number, doctor's signature, and fit/unfit status.

📌 Features ✅ Interactive medical report form with structured sections:

Candidate Information

Medical Examination

Laboratory Examination

🧾 Automatic report generation using localStorage for data persistence

📤 Image upload support for passport photo

📅 Auto-generated LAB SR NO, Examined Date & Expiry Date

🔍 QR Code embedded in the report linking key summary data

👨‍⚕️ Doctor's signature and status (FIT/UNFIT) with dynamic rendering

📄 Downloadable and printable PDF version of the report

💡 Responsive and print-optimized design

🛠️ Tech Stack Frontend: HTML, CSS, JavaScript

Libraries:

QRCode.js for QR code generation

jsPDF and html2canvas for PDF export

🚀 How It Works Fill Out the Medical Form:

Open application.html

Fill in patient details, upload passport photo, and submit

Generate the Report:

On submission, data is stored in localStorage

Automatically redirects to report.html

Preview & Download:

The report is populated with the form data

Click the Download Report button to export the report as a PDF

📂 Project Structure bash Copy Edit 📁 HealthPlus/ ├── application.html # Medical data input form ├── report.html # Generated report with auto-filled data ├── Image.png # (Add your logo here) ├── Signature.png # (Doctor's signature image)

🧪 Sample Data If the form hasn't been filled, a default sample report for "John Doe" is displayed for demonstration purposes.

📌 Important Notes This project does not require a backend.

All data is temporarily saved in localStorage for the session.

Ensure browser allows JavaScript and localStorage for proper functionality.

Designed to work offline once resources are cached.

🧑‍💻 Author Rishav Mondal
