---
title: Nick Gabler's Blog
---
<html lang="en">

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="description" content="Nick Gabler, Nicholas Gabler, Links, Resume, Instagram, Twitter, Email, Github, Systems Engineer, Systems Administrator, Linux Administrator, How to hire a systems engineer, How to hire a systems administrator, Website designer, AWS cloud practitioner, AWS certified cloud practitioner, Las Vegas, Vegas, Remote">
  <link rel="icon" type="image/x-icon" href="/images/favicon.ico">
  <link rel="preload" href="/fonts/jetbrains-mono.woff2" crossorigin="anonymous" as="font" type="font/woff2">
  <link rel="stylesheet" href="/css/main.css">
  <title>{{ title }}</title>
</head>

<body>
<h1>{{ title }}</h1><br>
{% for post in collections.post reversed %}
- [{{ post.data.title }}]({{ post.url }})
{% endfor %}
</body>

</html>
