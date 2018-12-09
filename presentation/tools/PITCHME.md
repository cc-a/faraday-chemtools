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

@snap[west span-33]
@box[bg-green text-white rounded](Version Control)
@snapend

@snap[south span-33]
@Interactive Development Environments
@snapend

@snap[midpoint span-33]
Documentation
@snapend

@snap[south-west span-33]
Maintenance
@snapend

@snap[south-east]
Design
@snapend

@snap[east span-33]
Testing
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

@snap[west span-30]
Website hosting
@snapend

@snap[south span-40]
Presentations (including this one)
@snapend

@snap[east span-30]
Project Management Tools
@snapend

@snap[south-west span-30]
Testing
@snapend

@snap[south-east span-30]
Documentation
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

@snap[west two-cols]
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

@snap[east two-cols]
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

@title[IDEs]

@snap[north span-90]
@size[1.75em](Integrated Development Environments)
@snapend

* Prevent mistakes
* Integration with Version Control and Testing

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
