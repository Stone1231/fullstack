# Fullstack Start

git clone https://github.com/Stone1231/fullstack.git  
git submodule init  
git submodule update  
git submodule status

## Backend

### core-be：ASP.NET core web api

- ORM init  
  dotnet ef migrations add <migration_name>  
  dotnet ef database update

### django-be：Django rest

- python env setting
  .vscode/settings.json **python.pythonPath**

- pip install -r requirements.txt

- ORM init  
  python manage.py makemigrations  
  python manage.py migrate

### go-be：gin gorm

go run main.go

## Frontend

### ng-fe：Angular

- vscode chrome debug
  https://github.com/Microsoft/vscode-chrome-debug  
  <chrome_path>>chrome.exe --remote-debugging-port=9222 --user-data-dir=<some_folder>

- chrome folder setting  
  .vs-code/launch.json **userDataDir**

- npm install

### vue-fe：VUE3
- npm install
- npm run dev