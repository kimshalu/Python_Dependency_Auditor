# Python_Dependency_Auditor
🔹 Project Overview
The Software Dependency Auditor is a Python-based web tool designed to analyze, audit, and manage project dependencies efficiently. It helps developers:

✅ Identify outdated libraries and suggest updates
✅ Detect illegal or restricted dependencies
✅ Check for security vulnerabilities using safety
✅ Verify license compliance using pip-licenses
✅ Generate detailed audit reports in CSV and JSON formats
✅ Provide a web-based UI for easy interaction

This tool ensures that software projects remain secure, compliant, and up-to-date, improving overall software maintainability.

🔹 Why is This Needed?
Software projects often depend on multiple third-party libraries, which:
❌ Become outdated, leading to compatibility issues
❌ Contain security vulnerabilities, exposing risks
❌ Include restricted licenses, causing legal concerns

The Software Dependency Auditor automates dependency tracking and validation, eliminating the need for manual checks.

🔹 Key Functionalities
1️⃣ Upload & Analyze Dependencies
Users upload a requirements.txt file via a web-based UI.
The system reads all dependencies and versions.
2️⃣ Identify Outdated Packages
Compares installed versions with the latest versions available on PyPI.
Highlights dependencies that require updates.
3️⃣ Security & License Compliance Checks
Security Check: Uses safety to detect known vulnerabilities.
License Compliance: Uses pip-licenses to verify package licenses.
4️⃣ Generate Reports
Audit results are stored and downloadable as CSV and JSON files.
5️⃣ Update Outdated Dependencies
Users can update packages directly from the web interface.
🔹 How It Works
1️⃣ Start the Web Application
Install dependencies:

sh
Copy
Edit
pip install -r requirements.txt
Run the web server:

sh
Copy
Edit
python app.py
The frontend is accessible at:
🔗 http://127.0.0.1:8000

2️⃣ Perform a Dependency Audit
Upload requirements.txt via the UI.
The system scans for outdated, insecure, or illegal dependencies.
3️⃣ View & Export Reports
Results are displayed in a structured dashboard.
Users can export reports in CSV/JSON formats.
4️⃣ Update Outdated Dependencies
Click "Update" on an outdated package to install the latest version.
🔹 Technologies Used
Frontend
✔ HTML, CSS, JavaScript
✔ Bootstrap (for UI components)
✔ AJAX (for API calls)

Backend
✔ Flask (Python web framework)
✔ Pip, Safety, Pip-Licenses (dependency auditing tools)
✔ SQLite (for storing results)

📌 Conclusion
The Software Dependency Auditor is a powerful web-based solution that helps developers analyze, audit, and manage dependencies efficiently. By ensuring that all dependencies are secure, updated, and compliant, it enhances software security and maintainability.
