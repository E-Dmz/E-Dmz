# Hi there 👋
## About me
After a first career in research (🧬💊🧠) and education (👨‍🎓👷‍♀️👨‍⚕️), I recently completed a [Data Science training](https://www.lewagon.com/data-science-course/full-time) at Le Wagon.

I'm thrilled by the latest development of Deep Learning and passionate about learning, designing tools and automating tasks.
## Sample projects
### 🚒 AntiFakeScience
Final student project at Le Wagon, partnering with fact-checking organization [ScienceFeedback](https://sciencefeedback.co). In a team of 4, we designed a web app aimed at screening contents that match the claims from a database. We used MPNET transformer embedding, web scraping and GCP.

[link to repos](https://github.com/antifakescience) | [link to demo app](http://antifakescience.herokuapp.com/) | [link to demo slideshow](https://docs.google.com/presentation/d/1ebWiQwunrS-YNUi-8BIkRfkMZBjW9CD2oQK_mX6O304/edit?usp=sharing) | [link to demo video](https://www.youtube.com/embed/iL4D2hWe05o?start=3435)
### 🚲 MaStationVelib
*Vélib'* is a popular bike-rental service in Greater Paris. For several months, I've collected the state of 1300+ docking points (*stations*) with a 5-minute time interval. Project aims:
- handle a dataset with tens of millions entries
- share this dataset through an API
- display (webapp) a summary for your favorite docking-station
- report the insights from a global analysis (*in progress*)
- implement ML models to predict the state of a docking point (*not quite done yet*)
I'm using my own NAS server (Synology DS720+) on a CRON task for data sourcing, pandas and matplotlib for dataviz, streamlit, Heroku for front-end and fastapi, Docker, GCP for back-end.
### 📉 DisplayCovidData
SantéPubliqueFrance is a government agency that releases Covid data on a daily basis. This project aims at visualizing this data in a somewhat original way. An early version of this project included fully-automated daily fetching, plotting and publishing on Twitter (cron task, requests, pandas/matplotlib, twitter API). I am currently refactoring, api-ing and simple-webapp-ing this.
## 📒 Gists, Cheatsheets, Examples
- [Neural Networks](http://placeholder.edmz.fr)
- [DataViz](http://placeholder.edmz.fr)
- [Example PCA](http://placeholder.edmz.fr)
![Demo-dataset](pca-demo-iris.png)
<!--
  - 📈 #dataviz suite:
    * ![DisplayDataCovid: Tweets a dataviz of Covid-19 in France](https://github.com/E-Dmz/DisplayDataCovid)

  - 🐦 #twitterapi suite:
    * ![ThreadFromATextFileScript: Tweets a thread from a simple text file (very useful)](https://github.com/E-Dmz/ThreadFromATextFileScript)
    * ![SelfTweetingScript: A script that tweets itself when executed (absolutely useless)](https://github.com/E-Dmz/SelfTweetingScript)
    * ![PingPong: Replies automatically "pong" when you're mentionned in a tweet that contains "ping" (even more useless)](https://github.com/E-Dmz/PingPong)
    * ![WakeUp: Politely greets your followers in the morning](https://github.com/E-Dmz/WakeUp)
  
  - 💡 #miscellaneous:
    * ![PiPoem: A piece of code showing that a simple 4-verse poem (in French) can provide you with a most precise approximation of pi](https://github.com/E-Dmz/PiPoem)


<!--
**E-Dmz/E-Dmz** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
I want to train as a data scientist because i think AI is going to reshape our world, for better and for worse  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  I'm also passionate about 💡🔧🧮 and 🙋‍♀️🙋‍♂️🚀  
🧬💊🧠 = "biochemistry, pharmacology and neuroscience"   ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·
👨‍🎓👷‍♀️👨‍⚕️ =  "high school students, water treatment technicians and radiology technicians"   ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·
💡🔧🧮 = "learning, designing new tools, automating tasks"   ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·
🙋‍🙋‍♂️🚀 = "collaborating on impactful projects"

Hi! I'm 37. I spent 10 years studying biology and doing research in biochemistry/pharmacology/neuroscience. I spent another 10 years teaching science and techniques to high-school students, water treatment technicians and radiology technicians. I'm training as a data scientist because i think AI is going to reshape our world, for better and for worse. I'm also passionate about learning, designing tools and automating tasks. After the bootcamp, i'd like to collaborate on meaningful and impactful projects.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
