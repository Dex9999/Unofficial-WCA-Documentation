---
description: The thing that is the worst
---

# 📝 Regions



{% hint style="warning" %}
**In the API, instead of regions, you pass in a country\_iso2 code**\


**eg.**

**For competitions in Canada your query would be:**\
`?country_iso2=CA`
{% endhint %}

{% hint style="danger" %}
Remember that only the first parameter has the ?, the rest of them have & symbols between them\
\
For example:\
www.example.com/api/v0?first\_param=3\&second=true\&third=yeah
{% endhint %}

## Country Codes

A list of all the countrys and their iso2 codes

| Role          | Capabilities                            |
| ------------- | --------------------------------------- |
| Administrator | Has all admin privileges                |
| Editor        | Can edit posts                          |
| Viewer        | Can only view posts                     |
| Guest         | Can only view posts they are inivted to |
