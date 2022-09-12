# 0x0F. Build a web app in JavaScript
## Details
 By: Nicolas Philippot, UI/UX designer and Guillaume Salva, CTO at Holberton School Weight: 5Project will startSep 10, 2022 12:00 AM, must end bySep 13, 2022 12:00 AMManual QA review must be done(request it when you are done with the project)In this project, you will finalize the previous project  [0x0B. Implement a design with bootstrap](https://intranet.hbtn.io/rltoken/oiPG7fxT8IPuYTMm8gbVBw) 
  and make some parts dynamic with Javascript (JQuery exactly).
You will reuse final files of  [0x0B. Implement a design with bootstrap](https://intranet.hbtn.io/rltoken/oiPG7fxT8IPuYTMm8gbVBw) 
  and update them.
You will use all HTML/CSS/Accessibility/Responsive design/Bootstrap/Javascript knowledges that you learned previously. 
You won’t have a lot of instruction, you are free to implement it the way that you want - the objective is simple: Have fully functional web pages that look the same as the designer file.
Here the final result:
 ![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/3c71cc99d2fc1c12a3d3.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220912%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220912T151810Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=7d316c4607965f6255bfa851a78788770a19c71332eaeb138bfda0b4bd6966a7) 

This webpage has been designed by Nicolas Philippot, UI/UX designer. You can find final screens  [here](https://intranet-projects-files.s3.amazonaws.com/holbertonschool-webstack/623/Archive.zip) 

### Requirements
* You have to use Bootstrap
* Your  ` styles.css `  must be as small as you can - you must use as much as you can Bootstrap classes
* You have to use JQuery
* Your  ` scripts.js `  must contain all your Javascript part
* Your Javascript must be executed only when the document is loaded
### Imports
For this project, you will need: fonts from Google, JQuery, Bootstrap CSS/JS
```bash
<link href="https://fonts.googleapis.com/css?family=Source+Sans+Pro&display=swap" rel="stylesheet">
<link href="https://fonts.googleapis.com/css?family=Coiny&display=swap" rel="stylesheet">

<script src="https://code.jquery.com/jquery-3.4.1.min.js" integrity="sha256-CSXorXvZcTkaix6Yvo6HppcZGetbYMGWSFlBw8HfCJo=" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script>

<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">

<link rel="stylesheet" href="styles.css">
<script src="scripts.js"></script>

```
## Tasks
### 0. Reuse and polish your Bootstrap integration
          mandatory         Progress vs Score  Task Body Copy files from  [0x0B. Implement a design with bootstrap](https://intranet.hbtn.io/rltoken/oiPG7fxT8IPuYTMm8gbVBw) 
 :
*  ` homepage.html `  ->  ` 0-homepage.html ` 
*  ` pricing.html `  ->  ` 0-pricing.html ` 
*  ` courses.html `  ->  ` 0-courses.html ` 
*  ` styles.css `  and any files/folders needed (images, fonts…) 
And finalize the design if it’s not done yet - the final result should be the same as these screens:
* [Homepage](https://intranet.hbtn.io/rltoken/X5mp-bZwa8Jzi3HI4xqSLA) 
 - [fig file](https://intranet.hbtn.io/rltoken/zsIWYdFMnWtImWisjLgfTw) 

* [Pricing](https://intranet.hbtn.io/rltoken/Bbop8wwZOLJsavfT6szqdQ) 
 - [fig file](https://intranet.hbtn.io/rltoken/5yAyDbQvLAVmm3IC_NRV3g) 

* [Courses](https://intranet.hbtn.io/rltoken/PSFYeol4NYMEmSBsxUyuoQ) 
 - [fig file](https://intranet.hbtn.io/rltoken/Jzp3WS1dZwYd8Q_wTIYp9Q) 

Important notes with Figma:
* if your computer doesn’t have missing fonts, you can find them here: [source-sans-pro](https://intranet.hbtn.io/rltoken/Ei8qgkDzThkeVZMZYZydHg) 
 and [Spin-Cycle-OT](https://intranet.hbtn.io/rltoken/SZKEX6sWitAn-vK8bZLvhA) 

* some values are in float - feel free to round them
* “Be pixel perfect” - yes! but mainly make sure colors, size and position are correct. #C271FF is not purple.
For this task, please write an amazing   ` README.md ` 
Interactions note:
* Web pages must switch to the tablet version when the screen width is 768px
* Web pages must switch to the mobile version when the screen width is 576px
* button hover/active:  ` opacity: 0.9 ` 
 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-smiling-school-javascript ` 
* File:  ` 0-homepage.html, 0-pricing.html, 0-courses.html, styles.css, README.md ` 
 Self-paced manual review  Panel footer - Controls 
### 1. Homepage - quotes
          mandatory         Progress vs Score  Task Body From   ` 0-homepage.html `  , create   ` 1-homepage.html `  .
Replace static quotes by dynamic loading:
* URL:  ` https://smileschool-api.hbtn.info/quotes ` 
* No static quotes should be present in the quotes section
* During the Ajax request, a loader should be present
* Carousel should work like before
Example of my loader:
```bash
HTML:
<div class="loader"></div>

CSS:
.loader {
    border: 10px solid #f3f3f3;
    border-top: 10px solid #C271FF;
    border-radius: 50%;
    width: 80px;
    height: 80px;
    animation: spin 2s linear infinite;
    margin: auto;
}

@keyframes spin {
    0% { transform: rotate(0deg); }
    100% { transform: rotate(360deg); }
}

```
Final result:
 ![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/4/044058b378bfef994b7c9dd672de1dca33d5f576.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220912%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220912T151810Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=3465aacef87810275148e959dfda3cf878fb202e5748a2f3ea9d1eb903f300fc) 

 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-smiling-school-javascript ` 
* File:  ` 1-homepage.html ` 
 Self-paced manual review  Panel footer - Controls 
### 2. Homepage - popular tutorials
          mandatory         Progress vs Score  Task Body From   ` 1-homepage.html `  , create   ` 2-homepage.html `  .
Replace static video cards by dynamic loading:
* URL:  ` https://smileschool-api.hbtn.info/popular-tutorials ` 
* No static video cards should be present in the section
* During the Ajax request, a loader should be present
* Carousel should work by sliding card by card (like GIF below) - this kind of carousel is not unique, make it generic to reuse it easily!
* Don’t forget the responsive part!
Final result:
 ![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/4/0efb5ff68c622f830a70e7aaf16bac87822462af.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220912%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220912T151810Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=0bf3208d501c0e967a2c8b8f3b8f2ab4767254c181486c5fe20f578eeef4eecc) 

 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-smiling-school-javascript ` 
* File:  ` 2-homepage.html ` 
 Self-paced manual review  Panel footer - Controls 
### 3. Homepage - latest videos
          mandatory         Progress vs Score  Task Body From   ` 2-homepage.html `  , create   ` homepage.html `  .
Replace static video card by dynamic loading:
* URL:  ` https://smileschool-api.hbtn.info/latest-videos ` 
* No static video cards should be present in the section
* During the Ajax request, a loader should be present
* Carousel should work by sliding card by card (like GIF below) - this kind of carousel is not unique, make it generic to reuse it easily!
* Don’t forget the responsive part!
Final result:
 ![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/4/c9a421edef604cee434f02f26328f6a549abd81a.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220912%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220912T151810Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=af53343baf2fcacddeb6f1ba18bffeacefecf072a6b55f4e8601bda062fcbf59) 

 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-smiling-school-javascript ` 
* File:  ` homepage.html ` 
 Self-paced manual review  Panel footer - Controls 
### 4. Pricing - quotes
          mandatory         Progress vs Score  Task Body From   ` 0-pricing.html `  , create   ` pricing.html `  .
Replace static quotes by dynamic loading:
* URL:  ` https://smileschool-api.hbtn.info/quotes ` 
* No static quotes should be present in the quotes section
* During the Ajax request, a loader should be present
* Carousel should work like before
Same as the   ` homepage.html ` 
 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-smiling-school-javascript ` 
* File:  ` pricing.html ` 
 Self-paced manual review  Panel footer - Controls 
### 5. Courses
          mandatory         Progress vs Score  Task Body From   ` 0-courses.html `  , create   ` courses.html `  .
Replace static video card by dynamic loading:
* URL:  ` https://smileschool-api.hbtn.info/courses ` *  ` GET `  parameters:*  ` q ` : search value (in our case, the value of the field KEYWORDS)
*  ` topic ` : topic filter value (in our case, the value of the field TOPICS)
*  ` sort ` : order of all courses (in our case, the value of the field SORT BY)


* No static video cards should be present in the section
* During the Ajax request, a loader should be present
* Dropdowns are dynamic (coming from the API):* Topic: list of  ` topics ` 
* Sort by: list of  ` sorts ` 

* Search value should be initialized by the value  ` q `  in the API response
* The list of video cards is coming from  ` courses `  in the API response
* API request must be done when:* Search value is changing
* A new Topic is selected
* A new Sort by is selected

 ![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/4/b081f3358ab5e79f44afc847d882bcf6fd5ef517.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220912%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220912T151810Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=a05f5648bee7bcd984d7e30eec538db674cddaaa72ae2ae141521813731f316c) 

 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-smiling-school-javascript ` 
* File:  ` courses.html ` 
 Self-paced manual review  Panel footer - Controls 
[Done with the mandatory tasks? Unlock 1 advanced task now!](https://intranet.hbtn.io/projects/628/unlock_optionals) 

Ready for a  manual review