---
---

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>{{ page.title | default: site.title }}</title>
</head>

<body>

{% include header.html %}

{{ content }}

<!-- You can also include a footer here if you want, similar to the header. -->

</body>
</html>
