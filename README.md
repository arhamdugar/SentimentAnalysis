# SentimentAnalysis
Sentiment analysis POC
    1. We install vscode, create a clone for repo and open that 
    2. We do a Ctrl + '  or open terminal and create a virtual environment using: 
 python -m venv venv
    3. Then we switch to that virtual environment :
 .\venv\Scripts\activate
    4. Now we can either install libraries required or we can create a requirements.txt and do a 
pip install -r requirements.txt
    5. We can run : pip freeze > requirements.txt, This will update requirements.txt with the new packages you've installed.
    • Generate a requirements.txt file with pip freeze > requirements.txt.(this creates the file itself)
    • Install all dependencies from it using pip install -r requirements.txt. 
(example of dependecnies in requirements file : 
    ﻿aiohappyeyeballs==2.4.0
aiohttp==3.10.5
    aiosignal==1.3.1
    annotated-types==0.7.0
    anyio==4.4.0
    asttokens==2.4.1)
    • Keep it updated by running pip freeze > requirements.txt after installing new libraries. (so we install new libraries via terminal and just run this command, it will update the requirements file, so another day another setup can be done easily)
    6.  
    
    

