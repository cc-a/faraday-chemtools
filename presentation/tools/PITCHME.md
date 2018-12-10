@title[Tools you need to be using]

@snap[north span-80]
Aspects of Software Engineering
@snapend

<!-- @snap[midpoint under-title] -->
<!-- @ol[](false) -->
<!-- - Version Control -->
<!-- - Testing -->
<!-- - Interactive Development Environments -->
<!-- @olend -->
<!-- @snapend -->

@snap[west box-style]
@box[bg-blue text-white rounded](<br>Version Control<br><br>)
@snapend

@snap[south-west box-style]
@box[bg-orange text-white rounded](<br>Maintenance<br><br>)
@snapend

@snap[midpoint box-style]
@box[bg-orange text-white rounded](<br>Documentation<br><br>)
@snapend

@snap[south box-style]
@box[bg-green text-white rounded](Interactive Development Environments)
@snapend

@snap[south-east box-style]
@box[bg-blue text-white rounded](<br>Design<br><br>)
@snapend

@snap[east box-style]
@box[bg-green text-white rounded](<br>Testing<br><br>)
@snapend

---

@title[Version Control]

@snap[north headline span-80]
Version Control
@snapend

@snap[south-west split-screen-img]
![PhD Comics](http://phdcomics.com/comics/archive/phd101212s.gif)
<!-- <img src="http://phdcomics.com/comics/archive/phd101212s.gif" width="400px"> -->
@snapend

@snap[south-east split-screen-text]
@ul[](false)
- Reproducibility
  - Track what changes you make to your work and when
  - Easily move back to previous versions
- Share and collaborate
  - Work on separate 'branches' then automatically combine the different versions
@ulend
@snapend

---

@snap[north headline span-80]
Working Online
@snapend

@snap[midpoint span-30]
 ![Github](https://studyguide.itu.dk/~/media/studyguide/student-life/facilities-at-itu/it-facilities/github/github_logo.png?h=248&w=573&la=en)  
 ![Bitbucket](https://d301sr5gafysq2.cloudfront.net/6beed0228b70/img/logos/bitbucket/bitbucket-attribution-blue.svg)  
 ![Gitlab](https://cdn-images-1.medium.com/max/2000/1*A4gQU4Mtnz0YVNrl8pCwXg.png)
@snapend

@snap[west span-25]
@box[bg-green text-white](Website hosting<br><br>)
@snapend

@snap[south span-35]
@box[bg-blue text-white](Presentations (including this one))
@snapend

@snap[east span-25]
@box[bg-blue text-white](Project Management Tools)
@snapend

@snap[south-west span-30]
@box[bg-orange text-white](Testing)
@snapend

@snap[south-east span-30]
@box[bg-green text-white](Documentation)
@snapend

---

@title[Testing]

@snap[north headline span-60]
Testing
@snapend

* The goal of data analysis/modelling is to get to the *right* answer
* Testing is well established as fastest way to do this
* Fundamental pillar of modern software engineering
* Initial investment of time allows you to make changes more flexibly
* Actual technical details vary between projects and languages

---

@snap[north span-80]
(Some of the) Types of Testing
@snapend

@snap[south-west two-cols]
Runtime tests  
@ul[](false)
- Performed as the code is executed
- "Sanity checks" - make sure things are internally consistent
- Check inputs as well as code
@ulend

@ul[code-region](false)
* function calculate_mass(weight):
  * mass = weight / 9.81
  * if mass < 0:
    * Error - cannot have negative mass
  * return mass
@ulend
@snapend

@snap[south-east two-cols]
Unit tests  
@ul[](false)
- Separate from main code
- Consider functional units of code in isolation
@ulend
@ul[code-region](false)
* function test_calculate_mass():
  * test_inputs = 0, 9.81, 19.62
  * test_outputs = 0, 1, 2
  * for input, output in test_inputs, test_outputs:
    * assert output == calculate_mass(input)
@ulend
@snapend

---

---?image=https://www.pptgrounds.com/wp-content/uploads/2012/12/Blue-Tech-Circles-Powerpoint-Technology-Backgrounds-1024x768.jpg

@title[IDEs]

@snap[midpoint span-90]
@size[1.75em](Integrated Development Environments)
<br><br>
@size[1.25em](Software that helps you write software)
@snapend

@snap[south-west span-33]
Boost Productivity
@snapend

@snap[south span-33]
Avoid Mistakes
@snapend

@snap[south-east span-33]
Integration with<br>
other tools
@snapend

---

@snap[north span-100]
@size[1.2em](Boost productivity and Avoid Mistakes)
@snapend

@snap[south under-title]
Code Completion<br>
![Autocomplete](https://code.visualstudio.com/assets/docs/languages/javascript/javascript_intellisense.gif)
@snapend

---

@snap[north span-100]
@size[1.2em](Boost productivity and Avoid Mistakes)
@snapend

@snap[south under-title]
Code Linting<br>
![Linting](https://code.visualstudio.com/assets/docs/languages/javascript/eslint_warning.png)
@snapend

---

@snap[north span-100]
@size[1.2em](Boost productivity and Avoid Mistakes)
@snapend

@snap[south under-title]
Integrated Testing<br>
![Linting](https://www.jetbrains.com/ruby/features/screenshots/testing/testing_ui@2x.png)
@snapend

---

@snap[north span-80]
Many options
@snapend

@snap[west span-35]
![Visual](https://upload.wikimedia.org/wikipedia/commons/thumb/1/19/Visual_Studio_2012_logo_and_wordmark.svg/2000px-Visual_Studio_2012_logo_and_wordmark.svg.png)
![PyCharm](https://upload.wikimedia.org/wikipedia/commons/thumb/a/a1/PyCharm_Logo.svg/1200px-PyCharm_Logo.svg.png)
@snapend

@snap[midpoint span-30]
![IntelliJ](https://upload.wikimedia.org/wikipedia/commons/thumb/d/d5/IntelliJ_IDEA_Logo.svg/1024px-IntelliJ_IDEA_Logo.svg.png)
@snapend

@snap[east span-35]
![Emacs](https://upload.wikimedia.org/wikipedia/commons/thumb/5/5f/Emacs-logo.svg/2000px-Emacs-logo.svg.png)
![Eclipse](https://upload.wikimedia.org/wikipedia/commons/thumb/d/d0/Eclipse-Luna-Logo.svg/274px-Eclipse-Luna-Logo.svg.png)
@snapend
