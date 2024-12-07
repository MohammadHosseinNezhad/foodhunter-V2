FoodHunter: Automated Script to Hunt "سبد سبز" from SAMAD Reservation Service

FoodHunter is an automated Python script designed to help you secure the highly sought-after "سبد سبز" (Green Basket) from the SAMAD Reservation Service. Using Selenium, this script simulates user interaction with the service's website to streamline the process of reserving food.

Features:
- Automated Login: Supports both new and existing users, offering easy access via username, password, or QR code login.
- Real-Time Reservation: Automatically selects and reserves the "سبد سبز" food item once available, optimizing your chances.
- Selenium Powered: Uses Selenium WebDriver for dynamic interaction with the SAMAD reservation service.
- Multiple Self-Services: Provides easy selection between various university self-service options.
- Food List Management: Allows users to select and reserve food from a pre-defined list.

Requirements:
Before running the script, make sure you have the following installed:

- Python 3.x (preferred version: 3.8+)

Required Python Libraries:
You can install the required libraries by using the requirements.txt file provided.

Install the dependencies:
pip install -r requirements.txt

The following libraries will be installed:
- selenium: The package for automating web browsers, which provides the WebDriver API used in your script.
- webdriver-manager: Automatically manages the WebDriver binaries (like GeckoDriver for Firefox).
- colorama: Used for colored output in the terminal.
- bidi: Handles bidirectional text rendering for right-to-left languages like Persian.

Installation:
1. Clone the Repository:
   git clone https://github.com/yourusername/foodhunter.git
   cd foodhunter

2. Install Dependencies:
   pip install -r requirements.txt

3. Set Up User Credentials:
   The script supports saving user credentials in a file called usersnew.txt. You can input your information manually or load it from the file.

4. Run the Script:
   To start the food hunting process:
   python main.py

   The script will guide you through the login and reservation process, providing real-time feedback in the terminal.

How it Works:
1. Login:
   The script prompts you to choose between creating a new user, selecting an existing user, or using QR code login.

2. Reservation Process:
   Once logged in, the script accesses the SAMAD reservation page, interacts with dropdowns, and selects the desired food (such as "سبد سبز") from available options.

3. Dynamic Interaction:
   The script uses Selenium's WebDriver to interact with dynamically changing elements on the reservation page, such as food items and availability.
   If credit balance is insufficient, the script alerts the user.

4. Notifications & Alerts:
   Real-time terminal output provides information on the process, including food selections and confirmation of successful reservation.

Customization:
You can modify the food list by editing the foodList.txt file. The script allows users to select a self-service location based on the given options and can be customized for other services as well.

Troubleshooting:
- Error Handling: The script includes robust error handling to guide you through common issues, such as invalid credentials or insufficient balance.
- QR Code Issue: If the QR code login method is invalid, the script will notify you and ask for an alternative login.

Contributing:
If you encounter bugs or want to add new features, feel free to fork the repository, submit issues, and make pull requests.

License:
FoodHunter is licensed under the MIT License. See the LICENSE file for more details.

Enjoy using FoodHunter to make sure you never miss the coveted "سبد سبز" on SAMAD's reservation system!
