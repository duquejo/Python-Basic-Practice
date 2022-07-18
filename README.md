# Useful venv commands

* Install venv
`{py|python|python3} -m venv {venv|custom_name}`

* Activate virtualenv (Windows)
`.\venv\Scripts\activate.bat`

* (Optional | One-timer) Create alias for virtualenv (Windows)
`alias {avenv|custom_name}=.\{venv|custom_folder}\Scripts\activate`

* Exit virtualenv (Inside it)
`deactivate`

* Install packages (inside virtualenv)
`{pip|pip3} install {package_name}`

* Save into requirements file
`pip freeze > requirements.txt`

* Just for checking actual virtualenv installed packages
`pip freeze`"# Python-Basic-Practice" 
