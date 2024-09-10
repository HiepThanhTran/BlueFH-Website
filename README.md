# Private Clinic Management System

The project provides a website for private clinics. Allows patients to choose a doctor to make an appointment.

## Installation

- Clone project

```bash
  git clone https://github.com/HiepThanhTran/Website-PCMS.git
  cd Website-PCMS
```

- Create a virtual environment

```bash
python3 -m venv venv
```

- Activate the environment

```bash
source venv/bin/activate   # On Windows: venv\Scripts\activate
```

- Install packages from requirements.txt

```bash
pip install -r requirements.txt
```

## Usage/Examples

- Go to __init__.py change something below:
    - SQLALCHEMY_DATABASE_URI: change user, password, host, and database name
```bash
app.config['SQLALCHEMY_DATABASE_URI'] = f'mysql+pymysql://<user>:<password>@<host>/<database name>?charset=utf8mb4'
```

- Create database schema by run **models.py** file

- Then run **index.py** file and go to [http://127.0.0.1:5000/](http://127.0.0.1:5000/)

## Screenshots

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)