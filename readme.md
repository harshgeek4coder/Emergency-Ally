<p align="center">
	<h1 align="center"> Emergency Ally </h2>
	<h4 > 2020 has been a rough year. We started with a wildfire in Australia , saw half of our world die due to COVID, migrant workers moved across states in our country,skies in California turned orange as the state choked up the fire fumes and what not. We have faced every calamity possible in this year and we , Team Myth Busters think , it would be stupid not to prepare ourselves for the future. So, lo and behold , Emergency Ally, a smart website designed to always be there for you in the time of emergency and get you out of it as soon as possible. <h4>Built using Natural Language Processing and Machine Learning,Emergency Ally is a Comprehensive Web App which can help you provide SOS or Emergency Level Solutions , In Case You encounter or see someone in any Danger or Disaster Situtations. 
</p>

---

## Preview
- <img src="https://github.com/harshgeek4coder/SLAC-2.0-Hackathon-Team-Myth-Busters-/blob/main/images/1.png">
- <img src="https://github.com/harshgeek4coder/SLAC-2.0-Hackathon-Team-Myth-Busters-/blob/main/images/pi2.png">
- <img src="https://github.com/harshgeek4coder/SLAC-2.0-Hackathon-Team-Myth-Busters-/blob/main/images/pi3.png">
- <img src="https://github.com/harshgeek4coder/SLAC-2.0-Hackathon-Team-Myth-Busters-/blob/main/images/pi4.png">
- <img src="https://github.com/harshgeek4coder/SLAC-2.0-Hackathon-Team-Myth-Busters-/blob/main/images/pi5.png">
## Functionalities
- [x]  Input Emergency
- [x]  Classification of emergency:Classifies your emergency to a bunch of other related emergency types 
- [x]  Priority Sorting:our model understands how urgent your search is and assigns it a priority level 
- [x]  Location Based Results:Gives you location based suggestions of nearest help centers and their contact information.

<br>
## File Description

    .
    ├── app     
    │   ├── run.py                           # Flask file that runs app
    │   └── templates   
    │       ├── go.html                      # Classification result page of web app
    │       └── master.html                  # Main page of web app    
    ├── data                   
    │   ├── disaster_categories.csv          # Dataset including all the categories  
    │   ├── disaster_messages.csv            # Dataset including all the messages
    │   └── process_data.py                  # Data cleaning
    ├── models
    │   └── train_classifier.py              # Train ML model           
    └── README.md

### Instructions: (Run run.py directly if DisasterResponse.db and claasifier.pkl already exist.)
1. Run the following commands in the project's root directory to set up your database and model.

    - To run ETL pipeline that cleans data and stores in database
        `python data/process_data.py data/disaster_messages.csv data/disaster_categories.csv data/DisasterResponse.db`
    - To run ML pipeline that trains classifier and saves
        `python models/train_classifier.py data/DisasterResponse.db models/classifier.pkl`

2. Run the following command in the app's directory to run your web app.
    `python run.py`

3. Run at http://0.0.0.0:3001/ <br>
NOTE : If the 3rd Step Doesn't Work , Try Running at  http://localhost:3001/
<br>

## Contributors

<table>
<tr align="center">


<td>

Harsh Sharma

<p align="center">
<img src = "https://github.com/harshgeek4coder/SLAC-2.0-Hackathon-Team-Myth-Busters-/blob/main/images/Harsh.jpg"  height="120" alt="Harsh">
</p>
<p align="center">
<a href = "https://github.com/harshgeek4coder"><img src = "http://www.iconninja.com/files/241/825/211/round-collaboration-social-github-code-circle-network-icon.svg" width="36" height = "36"/></a>
<a href = "https://www.linkedin.com/in/harsh-sharma-484a4ab6/">
<img src = "http://www.iconninja.com/files/863/607/751/network-linkedin-social-connection-circular-circle-media-icon.svg" width="36" height="36"/>
</a>
</p>
</td>

<td>

Akshat Anand

<p align="center">
<img src = "https://github.com/harshgeek4coder/SLAC-2.0-Hackathon-Team-Myth-Busters-/blob/main/images/akshat1.jpg"  height="120" alt="Your Name Here (Insert Your Image Link In Src">
</p>
<p align="center">
<a href = "https://github.com/cipheraxat"><img src = "http://www.iconninja.com/files/241/825/211/round-collaboration-social-github-code-circle-network-icon.svg" width="36" height = "36"/></a>
<a href = "https://www.linkedin.com/in/akshatanand1999">
<img src = "http://www.iconninja.com/files/863/607/751/network-linkedin-social-connection-circular-circle-media-icon.svg" width="36" height="36"/>
</a>
</p>
</td>


<td>

Ananya Negi

<p align="center">
<img src = "https://github.com/harshgeek4coder/SLAC-2.0-Hackathon-Team-Myth-Busters-/blob/main/images/ananya.png"  height="120" alt="Your Name Here (Insert Your Image Link In Src">
</p>
<p align="center">
<a href = "https://github.com/AnanyaNegi"><img src = "http://www.iconninja.com/files/241/825/211/round-collaboration-social-github-code-circle-network-icon.svg" width="36" height = "36"/></a>
<a href = "https://www.linkedin.com/in/ananya-negi-42922018a/">
<img src = "http://www.iconninja.com/files/863/607/751/network-linkedin-social-connection-circular-circle-media-icon.svg" width="36" height="36"/>
</a>
</p>
</td>



<td>

Tarushi Pathak

<p align="center">
<img src = "https://media-exp1.licdn.com/dms/image/C5103AQEZiMZveCVrzg/profile-displayphoto-shrink_200_200/0?e=1610582400&v=beta&t=Et_VdmR2Rxaseukc-qoPjI7FTHL21Pk3dbzfvV0epZA"  height="120" alt="Your Name Here (Insert Your Image Link In Src">
</p>
<p align="center">
<a href = "https://github.com/tarushi98"><img src = "http://www.iconninja.com/files/241/825/211/round-collaboration-social-github-code-circle-network-icon.svg" width="36" height = "36"/></a>
<a href = "https://www.linkedin.com/in/tarushi-pathak-6b7b5b177/">
<img src = "http://www.iconninja.com/files/863/607/751/network-linkedin-social-connection-circular-circle-media-icon.svg" width="36" height="36"/>
</a>
</p>
</td>
</tr>
  </table>
  
## License
[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)



