#  Regex Matching Web App

This is a web-based tool to test and validate **regular expressions (regex)**, built using **Flask** and **Python's `re` module**. 

##  Features
✅ Enter a regex pattern and a test string  
✅ View matches instantly  
✅ Validate email format using built-in regex  
✅ Clean and responsive interface

 Technology  Purpose                      
 Python        Core programming            
 Flask         Web framework                
 HTML/CSS      Frontend (with Jinja2 templating) 
 `re` module   Regex processing and matching 
 
pip install flask
Run the app
python app.py

How It Works
Enter a regex pattern.
Enter a test string.
The app returns all matches found in the string.
Optionally, click to validate email format using a predefined regex.

Project Structure

regex-matching-web-app/
app.py               # Main Flask application
templates/
index.html       # HTML form for regex input/output

 Example Use Cases
Test regex for email validation: ^[a-zA-Z0-9._%+-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,}$

Match digits: \d+

Extract hashtags: #\w+




