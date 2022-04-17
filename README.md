# Django 3.2 Custom Template

A custom Django template to quickstart new projects and avoid reinventing wheel everytime


## Tech Stack

* Python 3.8
* Django 3.2
* PostgreSQL
* Love 💙


## Environment

In `src/config/settings/` add an `.env` file with your environment variables


## Run Locally

👉 Before, you need to install [Tox](https://tox.readthedocs.io/en/latest/)

Clone the project

```bash
  git clone https://github.com/CamClrt/django-3.2_custom_template
```

Go to the root of the project and start the server

```bash
  tox -e py39
```


## Running Tests

To run tests, run the following command

```bash
  tox -e test
```

To run coverage and build HTML report, run the following command

```bash
  tox -e coverage
```


## Author

- **Camille Clarret** aka **Camoulty** or **CamClrt** : https://github.com/CamClrt