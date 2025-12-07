Mess Manager App

A robust, client-side single-page application designed to streamline the management of mess finances, meals, and utilities. Built for transparency and efficiency, this application features real-time cloud synchronization via Firebase, role-based access control (Manager/Member), and automated financial reporting.

Visit the live application here: [Your Live Link Here]

(Note: You can take a screenshot of your live application, upload it to a site like Imgur, and replace the link above to show a preview!)

Features

This application is packed with features to give you full control over your mess management:

📊 Interactive Dashboard: Get an at-a-glance overview of your Meal Rate, Total Expenses, Utility Totals, and Cash in Hand for the selected month.

🍽️ Meal Management:

Interactive Monthly Spreadsheet: A grid-based interface for logging daily meals for all members.

Direct Editing: Click-and-type functionality for quick updates.

Auto-Calculations: Total meals and individual meal costs are calculated instantly based on the dynamic meal rate.

💸 Financial Tracking:

Expense Logging: Detailed logging for groceries (Bazar) and operational costs.

Fund Separation: Distinct tracking for Meal Fund (consumption-based) and Utility Fund (shared equally).

Contribution in Kind: Support for members paying expenses directly, automatically adjusting their deposit balance.

⚡ Utility Tracking: Dedicated dashboard for monitoring Gas, Electricity, and Internet bill payments.

📢 Notice Board: Manager-controlled announcements for important updates.

🔐 Role-Based Access:

Member View: Read-only access to transparency reports.

Manager Mode: PIN-protected access for editing data and managing settings.

🔄 Month Closing: Automated carry-forward of balances to the next month for accurate accounting.

📜 Audit Log: Comprehensive activity history tracking who changed what and when.

🖨️ Printable Reports: Generate clean, black-and-white monthly status reports and meal sheets for physical notice boards.

💾 Data Management: Your data is important. You can export all your mess data to a JSON file for backup and import it back (in local mode) at any time.

How It Works

This is a fully client-side application, meaning it runs entirely in your web browser. It uses Firebase for cloud synchronization and data persistence.

✅ Cloud Sync: Integrated with Google Firebase (Firestore & Auth) for real-time data persistence across devices.

✅ Offline Capable: The application logic runs in the browser, ensuring speed and responsiveness.

Technologies Used

HTML5: For the structure of the application.

Tailwind CSS: For modern, responsive styling via CDN.

React 18: UI Library via CDN for zero-build setup.

Babel Standalone: In-browser JSX compilation.

Firebase SDK: Authentication & Firestore Database for backend services.

GitHub Pages: For hosting the live application.

Usage Guide

Manager Mode: Click the "Manager Mode" button in the sidebar. The default PIN is 1234 (Changeable in Settings).

Logging Bazar: Go to "Log Bazar", select "Individual" if a member paid from their pocket to adjust their deposit automatically.

Closing a Month: At the end of the month, go to Settings -> Month Closing to freeze current data and carry forward balances.

License

This project is licensed under the MIT License.

Developed by Talismati Dev Contact: talismati.dev@gmail.com