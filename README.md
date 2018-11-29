# Simple Python scraping with using Selenium

### Task:
I have a large number of **uid** that would like to scrape the company information from a Company Register.  
The url of the Company Register is: https://zh.chregister.ch/cr-portal/auszug/auszug.xhtml?uid=CHE-116.234.691  
Parse the HTML to extract the bottom table (In|Mo|Ca|Personal Data|Function|Signature)  
Sould run for a list of CompanyId/uid saved in a .xlsx file

### .xlsx file with UIDs

![uids](https://i.imgur.com/ggj5MMh.jpg)

### Target site

![table](https://i.imgur.com/englpiI.png)

### Scraping result

![result](https://i.imgur.com/vBWgjWn.jpg)

### Instruction for client
<pre>
Create virtual env with Python 3.6.x

Install modules in your venv by the command: pip install -r requirements.txt  
Will be installed 2 modules:selenium and openpyxl  

Also you need to download and unzip on your pc chromedriver
Chromedriver vrsion must be corresponding to your Chrome browser:  
http://chromedriver.chromium.org/  
https://chromedriver.storage.googleapis.com/index.html 
</pre>

![webdriver](https://i.imgur.com/B0EWCDh.jpg)
