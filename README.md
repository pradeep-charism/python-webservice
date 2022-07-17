# python-webservice


# Install dependencies
pipenv install Flask
pipenv shell

 python .\app.py
 
# Unit testing
http://127.0.0.1:5000/query-example?language=Python&framework=Flask&website=DigitalOcean

## Json
POST http://127.0.0.1:5000/json-example
Body
raw JSON
{
    "language" : "Python",
    "framework" : "Flask",
    "website" : "Scotch",
    "version_info" : {
        "python" : "3.9.0",
        "flask" : "1.1.2"
    },
    "examples" : ["query", "form", "json"],
    "boolean_test" : true
}



