🔍 T&C Squash — AI-Powered Terms & Conditions SummarizerA Chrome extension that scans Terms & Conditions (T&C) and Privacy Policy pages and instantly delivers clear, concise summaries of the most important clauses — helping users make informed decisions quickly.

📁 Project Structure
tc_squash_extension/
├── popup/
│   ├── popup.html         # Extension popup interface
│   ├── popup.js           # Frontend logic to interact with background
│   └── popup.css          # Styling for the popup UI
├── background.js          # Main background script triggering extraction
├── content.js             # Injected into webpages to extract T&C text
├── summarizer.js          # Summarization logic for key points
├── icon.png               # Unique purple magnifier icon
├── manifest.json          # Chrome extension manifest
├── README.md              # This file
└── .gitignore             # Ignore config

🚀Features

Smart Detection: Detects if the current webpage contains T&C content.

Important Sentence Extraction: Uses AI-powered logic to extract and display key legal, privacy, and billing terms.

Full Page Summary: If no T&C found, still returns top important clauses based on contextual analysis.

Floating Popup UI: Sleek interface appears automatically and can be triggered manually.
