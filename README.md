AI-Powered Travel Planner Automation

This project is an AI-driven travel planner built during my internship at Mirai School of Technology. It automates the process of creating a personalized, day-by-day itinerary from a single form submission and delivers it directly via email. The goal was to reduce the hassle of manual trip planning by combining AI, automation, and cloud services into one seamless solution.

Features!

This system was designed to bring together multiple tools into a single workflow:

• A user-friendly intake form powered by Lovable.ai
• n8n workflow automation to orchestrate the entire process
• LLM-based AI agent that generates detailed, human-like itineraries
• Google Sheets for structured logging and analytics
• Gmail API integration for professional, ready-to-use itinerary delivery

Workflow Overview!

The automation follows a simple but powerful pipeline:

• A user submits trip details through the Lovable.ai form
• A Webhook (POST request) triggers the n8n workflow
• The LLM agent processes inputs and creates a structured, day-by-day itinerary
• Results are logged into Google Sheets, enabling debugging and quality checks
• The finalized itinerary is sent to the user’s inbox via Gmail in a clean format

This design ensures scalability, transparency, and consistency while requiring no manual intervention.

Benefits of Automation!

The system delivers clear advantages over traditional manual planning:

• Reduced planning time from hours to just seconds
• Consistent, scalable outputs across use cases
• Transparent logging for continuous improvements
• Fully automated with no manual effort required

Key Learnings!

Working on this project helped me understand how AI + automation can solve real-world problems:

• The structure and design of prompts directly influence the quality of AI outputs
• Early logging practices greatly reduce debugging and speed up iteration
• It is essential to design for the “happy path” but build safeguards for edge cases

Tech Stack!

• AI & LLMs: Prompt Engineering, Itinerary Generation
• Automation Platform: n8n, Webhooks
• User Intake: Lovable.ai
• Cloud & Data Handling: Google Sheets, Gmail API
• Workflow Design: End-to-end orchestration of AI, automation, and cloud services

Repository Structure 
AI-Travel-Planner/
│── README.md
│── workflow-diagram.png   # Workflow overview image
│── itinerary-sample.pdf   # Example output
│── automation-n8n.json    # Export of n8n workflow (if shareable)
│── prompts/               # Prompt templates used for LLM
└── logs/                  # Sample Sheets data (anonymized)

Future Improvements!

This project is just the beginning. Some extensions I plan to add include:

• Maps API integration for routes and distances
• Fetching live pricing from travel APIs
• Exporting itineraries as PDFs or WhatsApp shares
• Adding notifications and real-time updates

Author!

Subasri B – Internship @ Mirai School of Technology
• Open to collaborations & new ideas
• Contact: shubkutt23@gmail.com


Acknowledgments!

Special thanks to Mirai School of Technology, Mr. Gautam Ahuja, and Mr. Arpit Sarda for mentorship, reviews, and guidance throughout the internship.
