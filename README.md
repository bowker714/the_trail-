Oregon Trail (Python Edition)

A text-based Python implementation of the classic Oregon Trail game! Guide your traveler from NYC to Oregon (2,000 miles) before winter sets in. Balance your resources, endure random events, manage your health, and survive the arduous journey.

Author: Yudong Lin

Version: 1.3.1

Contact / Bug Reports: yoshino1347716570@gmail.com

Repository: GitHub - yoshino-lin/Oregon-Trail

🎮 Game Features

Multiple Difficulty Modes: Choose from easy, normal, hard, impossible, or customize your starting food and health to your liking.

Dynamic Calendar & Days Tracker: Tracks days, months, and total time elapsed as you make decisions on the trail.

Resource & Health Management: Every action costs food and time. Random health drops and accidents keep you on your toes!

Randomized Events & Accidents: Cross rivers, fall ill with dysentery, or experience unexpected delays along the way.

In-Game Actions:

travel: Advance 30–60 miles (takes 3–7 days).

rest: Recover 1 health point up to maximum capacity (takes 2–5 days).

hunt: Hunt for food to gain +100 lbs (takes 2–5 days).

status: Check your remaining food, health, distance traveled, and total days passed.

help: View commands during gameplay.

quit / suicide: Exit the game with confirmation prompts.

Easter Eggs: Special secrets hidden within character names and gameplay inputs!

🚀 How to Run

Prerequisites

Python 2.7+ or Python 3.x installed on your system.

Instructions

Clone the repository:

git clone https://github.com/yoshino-lin/Oregon-Trail.git
cd Oregon-Trail


Run the script:

python oregon_trail.py


Play: Follow the on-screen prompts to enter your name, pick a starting year, select your game mode, and begin your journey!

📜 Version History

v1.3.1 (April 6):

Fixed input handling bugs in customize mode and year inputs.

Improved date formatting and player validation prompts.

Compatible with Python 2 and Python 3 environments.

March 28–30:

Added random events once per month (river crossing, dysentery, etc.).

Added low health and low food warnings.

Implemented random monthly health decline mechanics.

Added fake loading screen animations for immersion.

March 23–27:

Added difficulty modes (easy, normal, hard, impossible, customize).

Improved date/month tracking.

Added Easter egg for Meriwether Lewis.

Added double-confirmation on quitting/suicide.

🗺️ Future Roadmap

[ ] Selectable starting month and date.

[ ] Leap year calculation support.

[ ] Replay/restart option upon Game Over.

[ ] Sound effects and background music support.

[ ] In-game store to purchase supplies during the journey.

[ ] Multilingual support (Chinese version).

[ ] Analytics telemetry (sending game stats to author for balance tuning).

💬 Feedback & Contributions

Contributions, bug reports, and feature requests are welcome! Feel free to open an issue or submit a pull request on GitHub, or send feedback directly via email.
