
# Deploy water classifier using flask on heroku

[![](https://img.shields.io/badge/python-3.5%2B-green.svg)]()


> A web app to predict whether water is clean or dirty using fastai library.

------------------


Demo:

<p align="center">
  <img src="screenshot1.png" width="600px" alt="">
</p>

<p align="center">
  <img src="screenshot2.png" width="600px" alt="">
</p>

------------------


## Getting started

- Fork and clone this repo on to your system


## Customization

### Put your model inside path/models folder

- Place your trained `.pth` file under path/models/ directory.

### Change the class and path name

- Open "app.py" and search for a variable called classes and change that with your own classes

- If your path name is different that "stage-2.pth", then change the learn.load("with_your_file_name.pth") in "app.py"




### UI Change

Modify files in `templates` and `static` directory.

`index.html` for the UI and `main.js` for all the behaviors



## Heroku Installation

- Make sure that heroku is installed on your system, if you want to install then follow this https://devcenter.heroku.com/articles/heroku-cli#download-and-install

- Go to https://www.heroku.com/ then login or signup into heroku.

- Once you are logged in, you will have to click on new and click on create a new app as given in the screenshot below
<p align="center">
  <img src="screenshot3.png" width="600px" alt="">
</p>

- Give your app name and click on create app

- Go to the folder where you have cloned my repo and follow the steps given on the page




## Future Roadmap
- Add unit test.
- Add CI/CD integration.
- Create a robust image classifier using the more data or using some advance technique.
- Adding celery and redis as a message brocker to handle the long task.


