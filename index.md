## James Tubiano's docs configuration

this site contains my minimal configuration, with some of the technologies used in my development phase.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### ASP.NET Core MVC Tag helpers

this configuration to make the ```<environment></environment>``` tags and other ASP.NET Core MVC features
all you need to do is to import this piece of code to your current ```.cshtml``` file
```@addTagHelper "*, Microsoft.AspNetCore.Mvc.TagHelpers"```. then viola! you can now used those 
MVC built in tags

### Note:
this configuration must apply if you are using ASP.NET Core AREAS to get all the MVC tags.

### Gulp 4 configuration

this configuration are my suited in production environment,
since i will be only defining all the paths of the source and destination
of my working environment

You can visit [here](https://github.com/waput90/Gulp4Watch) 

### Webpack configuration

this webpack configuration is created due to my curiousity. :) 
feel free to make your own, this is just a starting point,
since there are lot of configuration out there.

You can visit [here](https://github.com/waput90/Gulp4Watch) 

### Support or Contact

Do you have any questions? you can reach me at: [tubianojames@gmail.com](mailto:tubianojames@gmail.com)
