
<h1 align="center">
  <br>
  <img src="https://www.signavio.com/wp-content/uploads/2013/03/Logo-Fraunhofer-WEB1.png" alt="Fraunhofer" width="500">
  <br>
</h1>

<h4 align="center">:star:	A site for one of Fraunhofers sub-projects.:star:	</h4>

<p align="center">
  <a href="#setup">:question: Setup</a> •
  <a href="#notes">:exclamation: Notes</a> •
  <a href="#utilities">:collision: Utilities</a>
</p>

# Setup

Okay listen up follow this and you're done
1. Download pycharm
2. Clone the repo
3. Open the repo with pycharm
4. Go to settings -> Project: fraunhofer -> Project interpreter. And click the wheel and select add local. I recommend you put the environment in ```~/.virtualenv/fraunhofer``` but you do you. Make sure your environment is python 3.6.x
5. hit ***alt + f12*** to open a terminal. (We're using the built in terminal because it automatically knows our virtual environment, you should see (fraunhofer) at the start of your terminal)
6. ```pip install -r requirements.txt``` to install the dependencies
7. hit ***ctrl + alt + r*** (command + r on mac). In this special terminal (it's a terminal that interacts with django) execute ```migrate```, this is gonna create a sqlite database for you.
8. in the top right (probably) from the dropdown  click edit configurations and make sure it looks like this

![alt text](https://i.imgur.com/VWnBitq.png "Use this pls")

9. Now use that configuration and click the green play button

# Notes

1. Don't edit main.css. It's the compiled sass.
2. Develop on a branch that is not master and when you're done create a pull request.

# Utilities

2. To compile the sass run the script ```compile-sass.sh``` in the utilities folder.
