# Countries-API
### List All Countries
```http
GET /api/countries
```
### Create a Country with it's Capital
```http
POST /api/countries
```
Send with json body:
```json
{
"name": "India",
"capital": "Delhi"
}
```
### Details of a Country (with id=1)
```http
GET /api/countries/1
```
### Change capital of a Country (with id=1)
```http
PUT /api/countries/1
```
Send with json body:
```json
{
"capital": "New Delhi"
}
```
### Delete of a Country (with id=1)
```http
DELETE /api/countries/1
```

# Run Locally

1. Clone this repository:
```
git clone https://github.com/abidalikp/countries-api.git
```

2. Create a virtual environment:
```
py -m venv virtual
```

3. Activate virtual environment:
```
source virtual/Scripts/activate
```

4. Install requirements using pip:
```
pip install -r requirements.txt
```

5. Run django server:
```
py manage.py runserver
```

6. Go to browser and type:
```
http://localhost:8000/
```
