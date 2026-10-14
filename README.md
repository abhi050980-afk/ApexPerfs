 Apex Car Evaluator

Multi-AI-Style Vehicle Telemetry, Performance Analysis & Ownership Cost Estimation

Apex Car Evaluator is a browser-based sports car evaluation dashboard designed to help users compare high-performance vehicles from two perspectives: track performance and everyday ownership.

The application combines vehicle specifications, performance scoring, interactive telemetry visualizations, pros-and-cons analysis, a simulated AI debate, and an ownership cost estimator in a premium automotive-themed interface.

✨ Features

🚗 Vehicle Selection

Choose from a collection of predefined sports cars.

Enter a custom vehicle name for an evaluation.

Explore featured vehicles through the homepage dashboard.

🏁 Dual-Perspective Evaluation

Evaluate each vehicle through two specialized perspectives:

Agent 1 — Track & Performance Specialist

Aerodynamics and mechanical grip

Power delivery and handling

Track suitability

Performance advantages and drawbacks

Agent 2 — Daily Ownership & Value Critic

Ride comfort and daily usability

Maintenance and running costs

Practicality and storage

Depreciation and ownership trade-offs

The interface presents five pros and five cons for each perspective, alongside suitability scores.

📊 Interactive Performance Radar

Visualize six vehicle attributes:

Power

Handling

Comfort

Technology

Heritage

Value

💬 AI Debate Arena

Explore a debate-style presentation of performance advantages versus everyday ownership compromises.

💰 Ownership Cost Estimator

Estimate projected ownership expenses using inputs such as annual mileage and track-day usage.

🎨 Automotive Dashboard UI

Dark carbon-fiber-inspired theme

Responsive layouts for desktop and mobile

Animated background effects

Interactive navigation and dashboard tabs

Optional interface sound effects

Copyable vehicle dossier

Browser print/export functionality

🛠️ Technology Stack

Technology

Purpose

HTML5

Application structure

CSS3

Custom styling, animations, and visual effects

JavaScript

Vehicle data, calculations, interactions, and rendering

Tailwind CSS CDN

Utility-based styling

Font Awesome

Interface icons

Google Fonts

Inter and Space Grotesk typography

HTML Canvas

Performance radar visualization

🚀 Getting Started

Prerequisites

A modern web browser, such as Chrome, Edge, Firefox, or Safari

An internet connection to load the external CSS, icon, and font resources

Installation

Download or clone the project files.

Locate apex_car_evaluator_professional_1.html.

Open the HTML file in your browser.

Alternatively, serve the file through a local development server:

python -m http.server 8000

Then open:

http://localhost:8000/apex_car_evaluator_professional_1.html

Run the command from the directory containing the HTML file.

No Node.js installation, package manager, or build step is required for the current standalone version.

📖 How to Use

Open the application and explore the homepage.

Select Launch Apex Evaluator.

Choose a predefined sports car or enter a custom model name.

Click Evaluate to display its vehicle information and evaluation.

Review the performance and ownership pros and cons.

Open the Performance Radar to inspect the six-axis scoring.

Explore the AI Debate Arena.

Adjust the ownership estimator inputs to examine projected costs.

Copy the dossier or use the browser's print option to export it.

🧩 Project Architecture

The current project is implemented as a single HTML application containing its page structure, styles, and JavaScript logic.

The main functional components include:

Navigation: switches between the homepage and evaluator workspace.

Vehicle data layer: supplies predefined vehicle information and generates fallback data for custom vehicle names.

Evaluation renderer: displays vehicle specifications, scores, pros, and cons.

Radar renderer: draws the vehicle's performance profile on an HTML Canvas.

Debate renderer: constructs a debate-style presentation from the available vehicle data.

Ownership calculator: estimates costs from user-selected inputs.

Utility functions: handle sound effects, dossier copying, filtering, and tab navigation.

🔐 AI Integration and Authentication

Although the interface is presented as a dual-AI evaluation suite, the current HTML implementation uses local JavaScript vehicle data and generated fallback content to populate the evaluation.

The inspected file does not show calls to an external AI API, an authentication service, or a backend server. It also does not define an API-key configuration or token-based authentication flow.

Consequently, the current version does not require API credentials to run its evaluation features.

For a future version with real AI integration, consider adding:

A backend API to communicate with the chosen AI provider.

Server-side storage for API keys and other secrets.

Input validation and rate limiting.

Error handling for failed or unavailable AI requests.

Clear labeling that distinguishes generated AI analysis from verified vehicle specifications.

⚠️ Limitations

Evaluations should not be treated as verified automotive engineering reports.

Custom vehicle names do not necessarily trigger a live search for real-world specifications.

Ownership estimates depend on the assumptions and formulas implemented in the application.

External CDN resources may not load without an internet connection.

The current implementation is a frontend application without a documented backend or persistent database.

 Potential Improvements

Integrate a real AI provider through a secure backend.

Retrieve specifications from reliable automotive data sources.

Add side-by-side comparisons between multiple vehicles.

Allow users to save and revisit evaluations.

Add currency, region, fuel-price, and insurance-cost settings.

Introduce downloadable PDF reports and data exports.

Add automated tests for evaluation logic and ownership calculations.
 License

No license is specified in the supplied project file. Add a LICENSE file before distributing the project if you want to define how others may use, modify, and redistribute it.

Apex Car Evaluator — Analyze the performance. Understand the trade-offs. Choose your machine. 🏁
