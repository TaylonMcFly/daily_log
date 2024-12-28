Daily Logger App
Daily Logger App is a simple application for recording daily events, saving them in a text file (daily_log.txt). The app provides a minimalistic interface to log your activities and events in chronological order.

📋 Features
Input field for event logging.
Save button to store events with a timestamp.
Automatic addition of date and time to each event.
All data is saved in the daily_log.txt file.


🛠️ Technologies
Python 3
Kivy: For creating the user interface.
Buildozer (optional): For building the app for Android.


🚀 Installation and Usage
Install Dependencies
script:
Ensure Python 3 is installed on your system.


Install the Kivy library:
script:
pip install kivy
Run the Application

Clone the repository:
script:
git clone https://github.com/<username>/daily-logger-app.git
cd daily-logger-app

Launch the app:
script:
python main.py
Build for Android (Optional)
Set up WSL2 and Ubuntu for building using Buildozer.
Follow the Buildozer documentation to set up your environment.


Build the APK:
script:
buildozer -v android debug

📂 Project Structure
daily-logger-app/
│
├── main.py          # Main application code
├── daily_log.txt    # Log file (created automatically)
└── README.md        # Project description

📌 Example Usage
Start the app.
Enter an event, such as Woke up.
Press the "Save Event" (only one button).
Check the daily_log.txt file for saved events.
Example content of daily_log.txt:
[28.12.2024 08:00] Woke up
[28.12.2024 08:05] Brushed teeth

🖋️ Author
Taylon McFly
📄 License
This project is licensed under the MIT License. See the LICENSE file for details.
