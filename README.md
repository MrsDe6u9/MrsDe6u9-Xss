# MrsDe6u9-Xss
"Experience the Automation With this tool"
<img width="1536" height="1024" alt="1" src="https://github.com/user-attachments/assets/4a9fe8c9-e735-4973-abfe-72823ecbb415" />
<img width="1359" height="732" alt="2" src="https://github.com/user-attachments/assets/e320e1a7-6b81-4f49-8954-1c0352f7b729" />
🚀 Features
Quickly scan for reflected XSS vulnerabilities.

Add custom payloads via adder.py.

Multithreaded scanning for speed (up to 10 threads).

🛠️ Installation
# 1. Clone the repository
git clone https://github.com/MrDe6u9/MrDe6u9-Xss.git

# 2. Change directory
cd MrDe6u9-Xss

# 3. Install dependencies
pip3 install -r requirements.txt

⚙️ Usage
python3 main.py -f <input_file> -o <output_file> [-t <threads>]
-f: File containing URLs to test.

-o: File to save vulnerable endpoints.

-t: Number of threads (default is low, max: 10)

➕ Add Payloads
python3 adder.py

📂 Example
python3 main.py -f urls.txt -o vulnerable.txt -t 5

