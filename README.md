FinTrack -- Personal Finance Management System
FinTrack is a responsive personal finance management dashboard designed
to help users organise their money in one place. It brings income,
expenses, accounts, budgets, savings goals, recurring payments, and
financial reports into a single interface.
Features
Dashboard
- View net worth, monthly income, monthly expenses, and savings rate.
- Compare income and expenses with cash-flow charts.
- Review spending by category.
- View financial health indicators and automatic insights.
- Track upcoming bills, recent transactions, budgets, and savings
  goals.
Transactions
- Add income, expense, and transfer records.
- Search and filter transactions by type, category, account, and
  period.
- Sort records by date or amount.
- Edit or bulk-delete transactions.
- Import and export transaction data using CSV.
Calendar
- View transactions on a monthly calendar.
- Identify higher-spending days through the calendar heatmap.
- Select a day to review or add transactions.
- Review spending by weekday.
Accounts and Wallets
- Organise cash, bank accounts, cards, and mobile wallets.
- Set an opening balance and account colour.
- Transfer money between accounts.
- Review account balances and balance history.
Budgets and Savings Goals
- Create monthly spending limits for expense categories.
- Generate suggested budgets from average spending.
- Monitor budget usage.
- Create savings goals with target amounts and optional deadlines.
- Add funds to or withdraw funds from goals.
Recurring Payments and Bills
- Create recurring income or expense entries.
- Set daily, weekly, monthly, or yearly frequency.
- Review upcoming payments over the next 30 days.
- Recurring transactions are added when the app is opened after their
  scheduled date.
Reports and Settings
- View annual financial summaries and monthly trends.
- Review income sources and spending by category.
- Print or save reports as PDF through the browser print dialog.
- Personalise the profile, currency, accent colour, dark mode, and
  animations.
- Optionally protect the app on the device with a four-digit PIN.
- Add custom income and expense categories.
- Export or import a JSON backup, export transactions as CSV, load
  demo data, or reset app data.
Interface and usability
- Responsive sidebar navigation.
- Light and dark themes.
- Search/command palette (Ctrl + K).
- Keyboard shortcuts for common actions.
- Notifications, confirmation dialogs, and toast messages.
- Bootstrap Icons and animated interface elements.
Technology Stack
The supplied application page uses:
- HTML5 -- application structure.
- CSS3 -- custom styling (css/style.css).
- Bootstrap 5.3.3 -- responsive layout, components, and
  modal/dropdown behaviour.
- JavaScript -- application interactions and data handling
  (js/app.js).
- Chart.js 4.4.1 -- financial charts.
- Bootstrap Icons 1.11.3 -- interface icons.
- Google Fonts (Inter) -- typography.
Project Structure
The HTML page references the following files and folders:
FinTrack/
├── index.html
├── assets/
│   ├── logo.svg
│   └── hero.svg
├── css/
│   └── style.css
└── js/
    └── app.js
Make sure the referenced asset, stylesheet, and JavaScript files are
present at these paths. The HTML file also loads Bootstrap, Bootstrap
Icons, Google Fonts, and Chart.js from external CDNs.
Getting Started
1. Download or clone the project
If the project is hosted in a Git repository:
git clone <repository-url>
cd FinTrack
Alternatively, download and extract the project ZIP.
2. Check the project files
Confirm that index.html, css/style.css, js/app.js, and the
required files in assets/ exist.
3. Run the application
You can open index.html in a modern web browser. For a local
development server, use VS Code's Live Server extension or run:
python -m http.server 8000
Then open:
http://localhost:8000
An internet connection is needed to load the external CDN libraries and
Google Fonts.
First-Time Use
1. Open FinTrack in your browser.
2. Enter your name and choose your currency.
3. Select Explore with demo data to inspect sample records, or
   Start fresh for a clean setup.
4. Add accounts and record your income, expenses, or transfers.
5. Create budgets and savings goals to monitor your progress.
6. Use Reports to review your financial activity.
Data and Privacy
The application interface describes data as being stored privately in
the current browser. It also provides JSON backup import/export and CSV
transaction import/export options.
- Export a JSON backup regularly to keep a copy of your data.
- Keep backup files in a secure location.
- Avoid using a shared or public device for personal financial
  records.
- Clearing browser site data may affect locally stored application
  data.
The supplied HTML references client-side application logic; it does not
document a server-side database or account synchronisation service.
Keyboard Shortcuts
  Shortcut     Action
  N          Create a new transaction
Ctrl + K   Open the command palette
D          Toggle dark mode
← / →    Change the selected month
1--`9`     Switch between pages
Browser Support
Use a modern browser with JavaScript enabled. The page uses Bootstrap
5.3.3, Chart.js 4.4.1, and modern browser features.
Important Notes
- FinTrack is a personal finance tracking interface; the supplied page
  does not describe bank API integration or automatic bank-account
  synchronisation.
- Currency selection controls how amounts are presented in the app; it
  should not be assumed to perform live foreign-exchange conversion.
- The four-digit PIN is described as device-level app protection. Do
  not treat it as a substitute for encrypted storage or account-level
  authentication.
- Recurring entries are processed when the application is opened after
  their scheduled date, according to the interface instructions.
Contributing
Contributions are welcome.
1. Fork the repository.
2. Create a feature branch:
   git checkout -b feature/your-feature
3. Make and test your changes.
4. Commit your work:
   git commit -m "Add your feature"
5. Push the branch and open a pull request.
License
No license information was included in the supplied project page. Add a
LICENSE file before distributing or reusing the project under specific
open-source terms.
