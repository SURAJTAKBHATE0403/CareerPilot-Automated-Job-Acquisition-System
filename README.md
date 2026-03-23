CareerPilot: Automated Job Acquisition System
CareerPilot is a Python-based browser automation bot designed to streamline the job application process on LinkedIn and Naukri.com. It specifically targets roles suitable for freshers and automates the repetitive task of searching and applying for jobs.

Key Features (Current)
Multi-Platform Support: Seamlessly automates job searches across both LinkedIn and Naukri.com.

Targeted Search: Specifically optimized for Java, Spring Boot, and Backend Developer roles.

Human Simulation: Mimics human behavior with random pauses and human-like scrolling to minimize detection.

Automated Form Filling: Automatically handles basic screening questions (e.g., Experience: 0, Location: Pune/Mumbai, Notice Period: Immediate) to speed up the process.

🛠 Tech Stack
Language: Python 3.x

Automation: Selenium WebDriver

Driver Management: webdriver-manager (for automated Chrome setup)

Configuration: python-dotenv (to keep login credentials secure and private)

📂 Project Structure
Plaintext
├── main.py            # LinkedIn automation logic
├── naukri_pilot.py    # Naukri automation logic
├── .env               # Private credentials (Not uploaded to GitHub)
├── requirements.txt   # List of required Python libraries
└── README.md          # Project documentation
⚙️ How to Run
Clone the Repository:
git clone https://github.com/your-username/CareerPilot.git

Install Dependencies:
pip install -r requirements.txt

Setup .env file:
Create a .env file and add your EMAIL and PASSWORD.

Execute:
python main.py
