# Automating Browser Interaction with Selenium
Experimenting with Selenium to extract a Report from SalesForce

## Setup:
- Download Chromedriver corresponding to your chrome browser version

https://sites.google.com/a/chromium.org/chromedriver/downloads

- create a virtualenv:
    ````
    virtualenv venv
    # Activate Virtualenvironment:
    venv\Scripts\activate
    pip install jupyter notebook
    pip install selenium
    pip freeze > requirements.txt
    ````
- or create virtualenv with requirement file:
    ````
    virtualenv venv
    venv\Scripts\activate
    pip install -r requirements.txt
    ````

- Create an .env based on .env_example

## Running the script:

- fire up your command line
````
venv\Scripts\activate
jupyter notebook
````
- Run the [Selenium.ipynb](Selenium.ipynb)


## Further Reading and excellent Resources:
- https://selenium-python.readthedocs.io/getting-started.html
- http://jonathansoma.com/lede/foundations-2018/classes/selenium/selenium-windows-install/
- http://jonathansoma.com/lede/foundations-2018/classes/selenium/selenium-snippets/
- https://youtu.be/PjDQ_MIL8JI
- https://pythonspot.com/selenium-click-button/
- https://stackoverflow.com/questions/12323403/how-do-i-find-an-element-that-contains-specific-text-in-selenium-webdriver-pyth
