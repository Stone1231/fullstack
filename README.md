# Fullstack Start

git clone https://github.com/Stone1231/fullstack.git  
git submodule init  
git submodule update  
git submodule status  

## Backend

### core-be：ASP.NET core web api

* ORM init
dotnet ef migrations add <migration_name>  
dotnet ef database update  

### django-be：Django rest

* python env setting
.vscode/settings.json __python.pythonPath__  

* pip install -r requirements.txt

* ORM init
python manage.py makemigrations  
python manage.py migrate  

## Frontend

### ng-fe：Angular

* vscode chrome debug
https://github.com/Microsoft/vscode-chrome-debug  
<chrome_path>>chrome.exe --remote-debugging-port=9222 --user-data-dir=<some_folder>  

* chrome folder setting  
.vs-code/launch.json  __userDataDir__  

* npm install  
