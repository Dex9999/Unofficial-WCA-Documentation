---
description: An endpoint for data on WCA competitors
---

# 👥 Persons Endpoint

{% swagger method="get" path="/" baseUrl="https://www.worldcubeassociation.org/api/v0/persons" summary="Returns a list of people in the database" %}
{% swagger-description %}
To access the next page of the API results, utilize the page parameter: "?page=2"
{% endswagger-description %}

{% swagger-parameter in="query" name="q" %}
A query parameter used to search for people by name or WCA ID. If provided, only people matching the query will be returned.
{% endswagger-parameter %}

{% swagger-parameter in="query" name="wca_ids" type="" %}
A comma-separated list of WCA IDs. If provided, only people with these WCA IDs will be returned.
{% endswagger-parameter %}
{% endswagger %}
