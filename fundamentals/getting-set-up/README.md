---
description: >-
  This API had 0 comprehensive documentation :) So after struggling for many
  projects with it, I decided to make one for myself and others.
---

# 🛠 WCA API V0

{% hint style="warning" %}
_**All the endpoints are paginated.**_

\
Each page displays 25 results.\
To access the next page of the API results, utilize the page parameter: "?page=2"
{% endhint %}

## Rest API Basics

In a REST API, a _<mark style="color:purple;">**path**</mark>_ is a part of the URL that follows the domain name and typically identifies a specific resource or endpoint.&#x20;

In the URL "[https://www.worldcubeassociation.org/api/v0/persons](https://www.worldcubeassociation.org/api/v0/persons)", the path is "/api/v0/persons". The "api" segment indicates that the URL is accessing an API endpoint, and the "v0/persons" segments specify the resource or endpoint that the client is requesting.

Each segment of the path can contain _<mark style="color:purple;">**query**</mark>_ parameters that are used to specify additional information about the resource.

For example, if the API supported filtering by country, a parameter such as "?country=USA" could be appended to the end of the path to filter the results to only show persons from the United States. [(The actual usage here is different)](setting-permissions.md)

When a client makes a request to a REST API using a URL such as "[https://www.worldcubeassociation.org/api/v0/persons?id=2022OLEA03](https://www.worldcubeassociation.org/api/v0/persons)", the server processes the request based on the path and any parameters included in the URL. The server then returns a response containing the requested data or indicating an error if the request was invalid.

<details>

<summary>Step1: Creating your organization</summary>



</details>
