# Car Search Application

This application demonstrates an implementation of a search and filtering system using Django, Elasticsearch, and Django Elasticsearch DSL.

## Features

- **Search**: Full-text search on car names and descriptions.
- **Filters**: Range, equality, and comparison filters on car attributes.
- **Suggestions**: Autocomplete suggestions for car names using Elasticsearch's completion suggester.
- **Custom Logic**: Example of custom field preparation (e.g., assigning points based on car color).
- **Elasticsearch Integration**: Efficient indexing and querying of car data.

## Setup

### Prerequisites

- Python 3.x
- Elasticsearch (version compatible with `django-elasticsearch-dsl`)
- Django

### Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-folder>

2. pip install -r requirements.txt

3. ELASTICSEARCH_DSL = {
    'default': {
        'hosts': 'localhost:9200'
    },
}


4. python manage.py migrate

5. python manage.py search_index --rebuild

6. python manage.py runserver

