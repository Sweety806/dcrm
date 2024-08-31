# Django CRM App
### Installation
Cloning from GitHub Repository
To get started with the Django CRM App, you can clone the repository from GitHub using the following steps:

###  Clone the repository:

```
git clone https://github.com/Sweety806/dcrm.git

```

### Navigate to the project folder:

```
cd dcrm

```

### Install virtualenv using (if not installed):

```
pip install virtualenv

```
### Create and activate a virtual environment:

```
virtualenv env
.\env\Scripts\activate.ps1
```
### Install project dependencies:

```
pip install -r requirements.txt

```

### Run database migrations:

```
python manage.py makemigrations
python manage.py migrate

```

### Create a superuser account (for admin access)<BR>

```
python manage.py createsuperuser

```

### Start the development server:

```
python manage.py runserver

```

Open your web browser and go to http://localhost:8000 to access the Django CRM App.
