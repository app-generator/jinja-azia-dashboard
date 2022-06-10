# [Azia Dashboard](https://appseed.us/generator/azia-dashboard/) Flask/Jinja

Open-source **Flask/Jinja Template** generated by `AppSeed` op top of **[Azia Dashboard](https://appseed.us/generator/azia-dashboard/)**, an iconic `Bootstrap` dashboard design. The project is a super simple Flask project WITHOUT database, ORM, or any other hard dependency. The project can be used as a codebase for future project or to migrate the Jinja files and assets to a legacy Python-based project that uses Jinja as template engine (Flask, Bottle, Django).

- 👉 [Azia Dashboard Flask](https://appseed.us/product/azia-dashboard/flask/) - product page
- 👉 [Azia Dashboard Flask](https://jinja-azia-dashboard.appseed-srv1.com/) - LIVE deployment
- 👉 [Complete documentation](https://docs.appseed.us/boilerplate-code/boilerplate-jinja) - `Learn how to use and update the product`
  - ✅ [Set up the environment](https://docs.appseed.us/boilerplate-code/boilerplate-jinja#environment)
  - ✅ [Start in Docker](https://docs.appseed.us/boilerplate-code/boilerplate-jinja#start-the-app-in-docker)
  - ✅ [Codebase structure](https://docs.appseed.us/boilerplate-code/boilerplate-jinja#codebase-structure)
  - ✅ [UI Assets and Templates](https://docs.appseed.us/boilerplate-code/boilerplate-jinja#ui-assets-and-templates)
  
<br />

> Built with [Azia Dashboard Generator](https://appseed.us/generator/azia-dashboard/)

- Timestamp: `2022-06-10 13:03`
- Build ID: `d9d729d0-a5d7-4f34-a8e1-04284cb23e04`
- **Free [Support](https://appseed.us/support/)** (registered users) via `Email` and `Discord`

<br />

> Features

- `Up-to-date dependencies`
- Render Engine: Flask / [Jinja2](https://jinja.palletsprojects.com/)

<br />

![Azia Dashboard - Starter generated by AppSeed.](https://user-images.githubusercontent.com/51070104/173038166-f2d50d19-75c7-4511-bf3b-b408bdbeafef.png)

<br />


## ✨ Start the app in Docker

> **Step 1** - Download the code from the GH repository (using `GIT`) 

```bash
$ # Get the code
$ git clone https://github.com/app-generator/jinja-azia-dashboard.git
$ cd jinja-azia-dashboard
```

<br />

> **Step 2** - Edit `.env` and set `DEBUG=True`. This will activate the `SQLite` persistance. 

```txt
DEBUG=True
```

<br />

> **Step 3** - Start the APP in `Docker`

```bash
$ docker-compose up --build 
```

Visit `http://localhost:5085` in your browser. The app should be up & running.

<br />


## ✨ How to use it

> Download the code 

```bash
$ # Get the code
$ git clone https://github.com/app-generator/jinja-azia-dashboard.git
$ cd jinja-azia-dashboard
```

<br />

### 👉 Set Up for `Unix`, `MacOS` 

> Install modules via `VENV`  

```bash
$ virtualenv env
$ source env/bin/activate
$ pip3 install -r requirements.txt
```

<br />

> Set Up Flask Environment

```bash
$ export FLASK_APP=run.py
$ export FLASK_ENV=development
```

<br />

> Start the app

```bash
$ flask run
```

At this point, the app runs at `http://127.0.0.1:5000/`. 

<br />

### 👉 Set Up for `Windows` 

> Install modules via `VENV` (windows) 

```
$ virtualenv env
$ .\env\Scripts\activate
$ pip3 install -r requirements.txt
```

<br />

> Set Up Flask Environment

```bash
$ # CMD 
$ set FLASK_APP=run.py
$ set FLASK_ENV=development
$
$ # Powershell
$ $env:FLASK_APP = ".\run.py"
$ $env:FLASK_ENV = "development"
```

<br />

> Start the app

```bash
$ flask run
```

At this point, the app runs at `http://127.0.0.1:5000/`. 

<br />

## ✨ Code-base structure

The project has a simple, intuitive structure presented bellow:

```bash
< PROJECT ROOT >
   |
   |-- apps/__init__.py
   |-- apps/
   |    |-- static/
   |    |    |-- <css, JS, images>         # CSS files, Javascripts files
   |    |
   |    |-- templates/
   |         |
   |         |-- includes/                 # Page chunks, components
   |         |    |
   |         |    |-- navigation.html      # Top bar
   |         |    |-- sidebar.html         # Left sidebar
   |         |    |-- scripts.html         # JS scripts common to all pages
   |         |    |-- footer.html          # The common footer
   |         |
   |         |-- layouts/                  # App Layouts (the master pages)
   |         |    |
   |         |    |-- base.html            # Used by common pages like index, UI
   |         |    |-- base-fullscreen.html # Used by auth pages (login, register)
   |         |
   |      index.html                       # The default page
   |      page-404.html                    # Error 404 page (page not found)
   |      page-500.html                    # Error 500 page (server error)
   |         *.html                        # All other pages provided by the UI Kit
   |
   |-- requirements.txt
   |
   |-- run.py
   |
   |-- ************************************************************************
```

<br />


## ✨ PRO Version

> For more components, pages and priority on support, feel free to take a look at this amazing starter:

Azia Dashboard is a premium Bootstrap Design now available for download in Flask. Made of hundred of elements, designed blocks, and fully coded pages, `Azia Dashboard PRO` is ready to help you create stunning websites and web apps.

- 👉 [Azia Dashboard PRO Flask](https://appseed.us/product/azia-dashboard-pro/flask/) - Product Page
- 👉 [Azia Dashboard PRO Flask](https://flask-azia-dashboard-pro.appseed-srv1.com/) - LIVE Demo

<br >

![Azia Dashboard PRO - Starter generated by AppSeed.](https://user-images.githubusercontent.com/51070104/173038278-320569fd-810f-4100-bdaa-501f70113ed1.png)

<br />

---
[Azia Dashboard](https://appseed.us/generator/azia-dashboard/) Flask/Jinja - Open-source starter generated by **[AppSeed Generator](https://appseed.us/generator/)**.
