# Python language with selenium.

## Overview

We will use python download: https://www.python.org/

## Setup and Install

1. Install Python
- Windows
- Mac

To verify that Python is installed already on your computer.

```
MAC:~ doaitran$ python --version
Python 2.7.13
```
2. Install Selenium
You can download Python bindings for Selenium from the PyPI page for selenium package. However, a better approach would be to use pip to install the selenium package.Using pip, you can install selenium like this:

```
pip install selenium
```

3. Download WebDriver

- Chrome:	https://sites.google.com/a/chromium.org/chromedriver/downloads
- Edge:	https://developer.microsoft.com/en-us/microsoft-edge/tools/webdriver/
- Firefox:	https://github.com/mozilla/geckodriver/releases
- Safari:	https://webkit.org/blog/6900/webdriver-support-in-safari-10/


4. Basic SELENIUM with PYTHON

- Open browser:

- Navigate to a URL
```
driver.get("http://www.google.com")
```

- Find Elements - Interact with PAGES
```
element = driver.find_element_by_id("passwd-id")
element = driver.find_element_by_name("passwd")
element = driver.find_element_by_xpath("//input[@id='passwd-id']")
```
- Close browser:

Click on Elemment

*_References:_*
http://selenium-python.readthedocs.io/

