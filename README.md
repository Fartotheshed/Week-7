# Project 7-Wordpress Pentesting

Time spent: 6 hours total

> Objective: Find, analyze, recreate, and document **five vulnerabilities** affecting an old version of WordPress

## Pentesting Report

1.Authenticated Stored Cross Site Scripting
Summary:
  Vulnerability: Cross Site Scripting
  Fixed in version: 4.2
  Tested in version: 4.2.3
  Walkthrough:
    ![xss1](https://user-images.githubusercontent.com/23129522/47958720-63b2e100-dfa7-11e8-8e74-df6262d55dae.gif)
   Steps: make a new post, write the javascript,publish,then view the post.

2.Authenticated Stored Cross Site Scripting via Image frame
Summary:
  Vulnerability: Cross Site Scripting
  Fixed in version: 4.2
  Tested in version: 4.2.1
  Walkthrough:
    
![xss2](https://user-images.githubusercontent.com/23129522/47958738-952bac80-dfa7-11e8-897f-ffdc1058ff95.gif)
  Steps: Add a new image in media. Go to library, then click on image. Then in the title section add the javascript right next to the image name.
  
3. User Authentication
Summary:
  Vulnerability: User Authentication
  Fixed in version: 4.2
  Tested in version: N/A
  Walkthrough:
  
![user enum](https://user-images.githubusercontent.com/23129522/47958741-cdcb8600-dfa7-11e8-8ef6-3d3566ca0322.gif)
  Steps: Type in username as admin but enter a wrong password. Type in random name and random password.
  
  ##Notes
  Some downloads took a while and kept crashing.
  
  ## Assets

List any additional assets, such as scripts or files

## Resources

- [WordPress Source Browser](https://core.trac.wordpress.org/browser/)
- [WordPress Developer Reference](https://developer.wordpress.org/reference/)

GIFs created with [LiceCap](http://www.cockos.com/licecap/).

  ## License

    Copyright [2018] [Farshed Adib]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
