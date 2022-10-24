# CARTE Education Pathways

Team Members: Mymy Tran, Grace Jiang, Yixin Tian.

This repo is a clone of https://github.com/nelaturuk/education_pathways.

Screenshot of Repo in your GitHub account:
As a user, <>
![image](images/userstory1.png)
2. As a user, I want to browse courses given key terms and different restrictions.
3. As a user, I want an option to learn more about the website.
![image](images/userstory3.png)
![image](userstory-2-3-commented.png)

## Activity 6: FE Protypings
### Prototype 1: Homepage Search Form
![image](https://user-images.githubusercontent.com/56566212/197421326-a6bd93ed-9e31-46f1-9ef1-265eca275ac9.png)

### Prototype 2: Course Page Grid
![image](https://user-images.githubusercontent.com/56566212/197421444-13b871a4-4c6f-4a45-b106-9462dfb370fb.png)

### Prototype 3: About Page Link
![image](https://user-images.githubusercontent.com/56566212/197421559-969a4093-3285-4916-857e-2bb4b160bfbb.png)

## Description
Welcome to CARTE's in-development tool for course selection at UofT. Education Pathways allows for more intelligent course searching, by matching not just the terms you search, but ones relevant to them. The more terms you search for, the more relevant your results will be! Even try searching across disciplines for the courses that best cover each.

Whatever year you are looking for, Education Pathways will also suggest courses in earlier years that will best help you to prepare. To get the most out of this, try searching for courses in a later year and see what is suggested for your current one.

We are looking for feedback to improve Education Pathways and make it more useful for students. If you have ideas or suggestions, please email us!

Screenshot's Lab 5:


## Repository files:

`./Procfile ./wsgi.py` *tells gunicorn how to run the program*

`./environment.yml  ./requirements.txt` *specifies python requirements for anaconda and pip respectively*

`./__init__.py` *main flask code*

`./readme.md` *this file*

`./resources:` *contains datasets used in the program*

`course_vectorizer.pickle df_processed.pickle`

`course_vectors.npz       graph.pickle`

`./static:` *contains any static elements of the webpage, in this case just the CARTE logo*
`CARTE_logo.jpg`

`./templates:` *contains flask templates for rendering HTML*

`_formhelpers.html course.html       index.html        results.html`
