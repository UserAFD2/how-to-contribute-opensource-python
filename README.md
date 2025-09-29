# 🌤️ PyWeather App

This is a simple weather application written in Python.

## Setup

First, install the dependencies. You can use either:

### Option 1: With [uv](https://github.com/astral-sh/uv) (recommended)

```bash
pip install uv
uv pip sync uv.lock
```

### Option 2: With pip

```bash
pip install -r requirements.txt
````

## API Endpoint

### GET /api/weather

This endpoint returns the current weather for a given city and country.

**Query Parameters:**

* `city`: The city to get the weather for.
* `country`: The country to get the weather for.

**Example:**

```
/api/weather?city=London&country=Uk
```
