# bcrm

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/7c032761c2404903ade6efe638f6e8de)](https://www.codacy.com/app/cedar-technologies/bcrm?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=skalpel-tech/bcrm&amp;utm_campaign=Badge_Grade)

Open Source Business CRM Solution

## docker

Run the application in docker

```bash
docker-compose up --build
```

## developement

Create a virtual environment

```bash
mkvirtualenv bcrm
```

Install the dependencies

```bash
cd src
pip install -r requirements.txt
```

Set the flask app root

```bash
FLASK_APP=app
```

Run the application

```bash
flask run
```

import [postman collection](postman/BCRM.postman_collection.json)  [postman environment](postman/BCRM.postman_environment.json)

or start building an application: [swagger](docs/BCRM.swagger.yml)