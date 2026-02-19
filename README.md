🏢 CODERS-OF-BANGALORE: The Funding Challenge
Welcome to the Coders-of-Bangalore (CoB) repository. This project is a narrative-driven Data Science simulation where you must prove your technical worth to Sam Altman to secure a fictional $2.2 Billion USD in funding.

The mission is clear: Analyze a raw data dump of OpenAI's followers on Instagram and extract business-critical insights within 24 hours—using Pure Python.

📌 Project Scenario
After a public challenge from Sam Altman, you are tasked with auditing the digital footprint of a massive follower base. You’ve hired a specialized team from Hebbal and HSR Layout to meet at Rameshwaram Cafe to build a custom parsing engine from scratch.

The Objectives
To win the funding, your script must answer:


Content Leadership: Who has the maximum posts? 


Influence Mapping: Who has the maximum followers? 


Networking Density: Who follows the maximum number of people? 


Ecosystem Diversity: How many distinct categories (Digital Creators, Nonprofits, etc.) exist in the dataset? 

📂 Repository Structure

coders-of-bangalore.ipynb: The main engine containing the parsing logic, data cleaning, and analytical queries.


finaldata.txt: The raw, unstructured Instagram data dump containing bios, follower counts, and categories.


data.json: The final structured dataset exported after processing.

🛠️ Technical Implementation
1. Intelligent Parsing & Cleaning
The core of this project is a custom function designed to handle the "messy" reality of raw web-scraped data.


Unit Conversion: The script detects strings like "K" (Thousands) or "M" (Millions) in follower counts and converts them into pure integers for mathematical operations.


Separation Logic: Uses specific delimiter-based splitting to isolate usernames, post counts, and categories.

2. Ecosystem Analysis
The project identifies 34 distinct categories within the Bangalore tech scene, showcasing the incredible diversity of the city's digital network.

🚀 Constraints
No Libraries: Strictly prohibited from using Pandas or NumPy.


Standard Library Only: Relies entirely on json for data serialization and built-in Python string methods for manipulation.
