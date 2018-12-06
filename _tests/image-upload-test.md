---
title: "Image Upload Test \U0001F440"
layout: test
front_matter_test_image: /uploads/colossus-2.jpg
front_matter_test_text:
---
Front matter words: {{page.front_matter_test_text}}

Data words: {{site.data.image_upload_test.test_text}}

This image is loaded from front matter:
![]({{page.front_matter_test_image}})


This image is loaded from a data file:
![]({{site.data.image_upload_test.upload_image}})

this png tested in the Content Editor:

![](/uploads/icy-speedway.png)

v this jpg tested in the Content Editor:

![](/uploads/icy-speedway.jpg)

this png tested in the Visual Editor:

![](/uploads/fracture-hills.png)

this jpg tested in the Visual Editor:

![](/images/Canyon Speedway/Canyon Speedway.jpg)

 

this jpg tested in the Visual Editor, chosen from previously uploaded images:

 

![](/images/Colossus/Colossus sky.png)

![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVQYV2NYtWrVfwAG/gL+NbCogwAAAABJRU5ErkJggg==){: .cms-image-placeholder}