---
title: "Taylortemplatetinker"
date: 2022-10-19T19:31:54-04:00
draft: false
---
<html>
<body>
<p>I looked in the ananke layout folder in order to see how it worked. What I found was that there are two main sections that make up the posts. There is a {{.Title}} and a {{.Content}}. .Title seems to define were the title is in the layout of the page, and .Content marks were the main body of information will always be. Every page on Hugo will share this same layout, becasue this is the template for our layout. You can add and remove these tags to change how the layout of our posts are. In the summary file, it has a template to set up how the dates of the posts appear. HAving multiple templates focusing on differnet areas of the same posts makes it easy to understand and edit, because having too much information in one place can get confusing. Since Hugo natively supports taxonomies, it makes it really easy to have categories and tags organzie your information. I believe the Menu contextual file is what aggregates all of the tags, using a table of contents feature. It looks for certain parameters in order to know if it should pull the content or not. This relates to what we learned this week because it shows how easy tags and categories can be set up usign Hugo, and shows how valuable it is to group your content by a type. Whenever the content is grouped aby a category or a tag, the easier it is to find the information you are looking for, or similar posts.
</p>
</body>
</html>
