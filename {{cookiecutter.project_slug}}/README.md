{% set is_open_source = cookiecutter.open_source_license != 'Not open source' -%}

# {{ cookiecutter.project_name }}

{% if is_open_source %}
![https://pypi.python.org/pypi/{{ cookiecutter.project_slug }}]([https://img.shields.io/pypi/v/{{ cookiecutter.project_slug }}.svg)
![https://travis-ci.org/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}](https://img.shields.io/travis/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}.svg)
{%- endif %}

{{ cookiecutter.project_short_description }}

{% if is_open_source %}
- Free software: {{ cookiecutter.open_source_license }}
{% endif %}

# Features

- TODO

# Credits

- TODO
