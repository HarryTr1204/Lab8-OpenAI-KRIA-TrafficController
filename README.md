# Lab8-OpenAI-KRIA-TrafficController
Lab8-OpenAI-KRIA-TrafficController


Reference: Laboratory 8

About this lab: there are three parts in this lab, the first part is about OpenAI File Q&A. The second one is about OpenAI Web Crawl Q&A. The last one is hardware part, it is about Traffic Controller.

A)OpenAI FileQ&A
1)Obtain OpenAI and Pinecone API keys by following the instructions in the links provided in the setup guide.
2)Download the source code from the openai-cookbook GitHub repository and unzip it.
3)Navigate to the server directory in the PowerShell window and run the following commands:
pip install openai
npm install openai
python -m venv venv
.\venv\Scripts\activate
pip install -r .\requirements.txt
pip install python-dotenv
python .\app.py
4)Fill out the config.yaml file with your Pinecone API key, index name, and environment.
5)Navigate to the client directory in a new PowerShell window and run the following commands:
pip install openai
npm install
6)Open a web browser and navigate to http://localhost:3000 to use the application.
7)Create a file which include all questions and answer, then save it as text. Upload that file text into " Click to upload or drag and drop"
8) After that, type questions that you created as file text. It will answer it at below
 
B)OpenAI Web Crawl Q&A
Prerequisites:
Windows OS
PowerShell
Python 3.6 or later
OpenAI API key (https://beta.openai.com/signup)
Git (https://git-scm.com/downloads)
Instructions:
1) Create an OpenAI API key by signing up for an account on the OpenAI website.
2)Install the OpenAI Python package by running this command:
pip install openai
3)Retrieve your OpenAI API key from the API Keys page (https://platform.openai.com/account/api-keys).
4)Create a new folder, for example C:\web-crawl-q-and-a, using the command md (make directory).
5)Navigate into the new directory using the cd (change directory) command.
6)Create a new file called .env in the directory using a text editor like Notepad++ or any other text editor that allows you to save in .env format. Add this line to the file: OPEN_API_KEY = "YOUR_API_KEY".
7)Clone the full code for this tutorial from GitHub and put it in the directory you just created:
git clone https://github.com/openai/openai-cookbook.git
8)Install the virtualenv package using this command: python install virtualenv.
9)Create a virtual environment for the project using this command: python -m venv env.
10)Activate the virtual environment using this command: .\env\Scripts\activate.
11)Install the required packages using this command: pip install -r requirements.txt.
12)Customize the web crawler by editing the web-qa.py file with your own domain and URL:
a. Import necessary libraries at the top of the file.
b. Set your OpenAI API key in the file.
c. Define your root domain and URL to crawl.
13)Run the code by using the command python web-qa.py and inputting a question when prompted.
 


C) Traffic Controller:
In this part, the state machine we built in the hardware component (the traffic light controller) is replaced by programming code with KRIA. The code should be set to the condition that, when the code is run, the light color will change based on how traffic lights operate.





