---
description: An endpoint for data on WCA competitors
---

# 👥 Persons Endpoint

{% swagger method="get" path="/persons" baseUrl="https://www.worldcubeassociation.org/api/v0" summary="Returns a list of people in the database" expanded="false" %}
{% swagger-description %}
To access the next page of the API results, utilize the page parameter: "?page=2"
{% endswagger-description %}

{% swagger-parameter in="query" name="q" type="" %}
A query parameter used to search for people by name or WCA ID. If provided, only people matching the query will be returned.

\




\


eg. 

[?q=sus](https://www.worldcubeassociation.org/api/v0/persons?q=sus)


{% endswagger-parameter %}

{% swagger-parameter in="query" name="wca_ids" type="" %}
A comma-separated list of WCA IDs. If provided, only people with these WCA IDs will be returned.



[If you only want one person's stats use the next path.](persons-endpoint.md#undefined)



eg. [?wca\_ids=2022OLEA01,2022OLEA02,2022OLEA03,2022OLEA04](https://www.worldcubeassociation.org/api/v0/persons?wca\_ids=2022OLEA01,2022OLEA03,2022OLEA02,2022OLEA01)
{% endswagger-parameter %}
{% endswagger %}

{% swagger method="get" path="/persons/{id}" baseUrl="https://www.worldcubeassociation.org/api/v0" summary="Returns detailed information about a specific person identified by their WCA ID." expanded="false" %}
{% swagger-description %}
{id} is the person's WCA id, has no parameters
{% endswagger-description %}

{% swagger-parameter in="path" name="n" type="/" %}
a
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="" %}

{% endswagger-response %}
{% endswagger %}

{% swagger method="get" path="/persons/{id}/results" baseUrl="https://www.worldcubeassociation.org/api/v0" summary="Returns a list of a person's competition results." expanded="false" %}
{% swagger-description %}
{id} is the person's WCA id
{% endswagger-description %}

{% swagger-parameter in="query" name="competition_id" %}
Filter results by competition ID
{% endswagger-parameter %}

{% swagger-parameter in="query" name="event_id" %}
Filter results by event
{% endswagger-parameter %}

{% swagger-parameter in="query" name="round_type" %}
Filter results by round type (e.g., "first round", "semifinals", "finals" etc.).
{% endswagger-parameter %}
{% endswagger %}
