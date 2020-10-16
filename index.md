# James Tubiano's docs configuration

  This site contains my minimal configuration, with some of the technologies used in my development phase.

## Creating CDN script using jsdelivr with github repository

  in my development phase i am wondering, how did these people created CDN scripts?
  but in my discovery i will show you how i did it by the use of JSDelivr
  
  1. Login to github.com
  2. create repository in github make sure to make it public to make it accessable anywhere
  3. used this template using jsdelivr
  
  https://cdn.jsdelivr.net/gh/user/repo@version/file
  
  just replace the following
  user: your github username
  repo: your github repository name
  version: would be the branch of your repository
  file: this would changed depends on your file structure on your repo.
  
  that's it! hope it helps

  you can visit there site, just click [here](https://www.jsdelivr.com/?docs=gh)


## ASP.NET Core MVC Tag helpers

  this configuration to make the ```<environment></environment>``` tags and other ASP.NET Core MVC features
  all you need to do is to import this piece of code to your current ```.cshtml``` file
  ```@addTagHelper "*, Microsoft.AspNetCore.Mvc.TagHelpers"```. then viola! you can now used those 
  MVC built in tags

  ### Note:
  this configuration must apply if you are using ASP.NET Core AREAS to get all the MVC tags.


## Gulp 4 configuration

  this configuration are my suited in production environment,
  since i will be only defining all the paths of the source and destination
  of my working environment

  You can visit [here](https://github.com/waput90/Gulp4Watch) 

## Webpack configuration

  this webpack configuration is created due to my curiousity. :) 
  feel free to make your own, this is just a starting point,
  since there are lot of configuration out there.

  You can visit [here](https://github.com/waput90/Gulp4Watch) 

## Support or Contact

  Do you have any questions? you can reach me at: [tubianojames@gmail.com](mailto:tubianojames@gmail.com)
