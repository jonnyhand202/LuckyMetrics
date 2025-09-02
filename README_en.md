Number Suggester v14.0
An advanced desktop application for generating statistical and intelligent coupon suggestions for lottery games by analyzing historical data.

This is not just a simple random number generator. It is a powerful analysis tool that performs a deep dive into past draw data to create meaningful and strategic coupons that adhere to your custom statistical rules. With server integration and multi-game support introduced in v14.0, you can now sync your suggestions with other users and perform analyses for various lottery games.

(You can replace this with a screenshot of your application)

🚀 Key Features
📊 Advanced Statistical Analysis: Calculates over 50 statistical metrics for loaded data (e.g., Sum, Mean, Standard Deviation, Entropy, Prime Number Distribution, Decade Spread).

⚙️ Three Different Suggestion Modes:

Random Score: Generates a set number of random coupons and lists the best-scoring ones.

Smart Suggestion (Best Choice): Uses an AI-assisted search algorithm to find the "perfect" coupons that match your defined rules.

Fast Smart Suggestion (First Found): Combines speed and performance by finding the first valid coupon that meets the criteria.

✍️ Force Mode (Custom Rule Engine): A powerful engine allowing you to define the minimum/maximum statistical values, tolerances, and weights that the generated coupons must follow.

🌐 Server Integration (Share & Sync):

Share your generated coupons on a central server to prevent other users from playing the same numbers.

Automatically filter out or penalize coupons shared by other users from your suggestion list.

🌍 Multi-Game Support: Generate analyses and suggestions for different lottery games like "Sayısal Loto," "Powerball," or "SuperEnalotto." Shared coupons are categorized by game.

⚡ Efficient Caching System: The list of shared coupons downloaded from the server is stored in a local cache file. This makes the application faster and reduces unnecessary internet traffic.

🇹🇷🇬🇧 Bilingual Support: Switch between Turkish and English with a single click.

📂 Data Import/Export: Easily load historical data from .csv and .xlsx (Excel) files. Export your generated suggestions with all their statistics to Excel or CSV.

📈 Detailed Analysis Panels: Analyze specific row or date ranges of your data instead of the entire dataset.

🛠️ Getting Started
Follow these steps to get the application up and running.

Prerequisites
Python 3.8 or newer

Required Python libraries. You can install them all at once with the following command:

pip install numpy pandas scipy openpyxl requests tkcalendar

Running the Application
Download or clone the project to your local machine.

Open a terminal or command prompt in the project directory.

Run the application with the following command:

python your_script_name.py

(Note: Replace your_script_name.py with the actual name of your file)

📖 Usage
Load Data: Click Browse to select your .csv or .xlsx file containing historical draw data, then click Load & Analyze. In the preview window, ensure you have correctly selected the number and date columns.

Analyze & Set References: Once the data is loaded, the "Summary Statistics" table will be populated. You can right-click any row in this table (e.g., "Mean") to set its values as the reference for "Force Mode".

Define Rules (Optional): Check the Force Statistics box and click Settings to open the "Force Mode" panel. Here, you can specify in detail the statistical ranges your coupons should fall into.

Select Game & Generate: Choose the lottery type you want to analyze from the Select Game dropdown menu. Then, click one of the generation buttons ("Random", "Smart Suggestion", or "Fast Smart Suggestion") based on your strategy.

Share & Sync:

In the Server Settings panel, choose whether to "Ban" or "Score Down" coupons shared by others.

Select the coupons you intend to play from the suggestion list and click Share on Server to sync them with other users.

⚙️ Server Configuration
The application connects to a central server via the SERVER_URL and API_KEY constants. If you wish to set up your own server, simply change these variables in the code to your server's address and key.

✍️ Contributing
Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated. Please feel free to open a pull request or an issue.

📄 License
This project is licensed under the MIT License. See the LICENSE file for details.

👤 Author
İslam - Lead Developer
