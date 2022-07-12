# Tech stack used
<ul>
  <li>Python</li>
  <li>Django Framework</li>
  <li>CSS , HTML</li>
  <li>BootStrap</li>  
</ul>

<p> Project Deployed to pythoneverywhere

## Steps Followed

1. Created a django project mov and inside that porjected created an application by the name 'core'
2. Create a user defined Registration model in models.py file (I did't use inbuilt forms here)
3. Create a movie model in models.py , here i used builtin forms by creating forms.py file
3. Registered my model on admin.py
4. created urls.py file and templates folder inside my application
5. linked app urls with project urls 
6. migrated all models to database
6. Build my first function in views.py , configured its url in urls.py, returned a response in the form of html page 
7. Created login and signup pages and integrated them with my project 
8. Applied for a key on omdb application
9. processed omdb api and got the movie info , passed in that info from my view funcrtion to html response page
10. To get the details of a particular movie , i passed in an imdbID attribute through url into the view , got all info and passed it into movie detials page
11. created two html pages "allmovies" and "mymovies" to display all movies and my private movies respectively 
12. fetched private movies by using status field of Movie model and fetched all movies by getting entire records of Movie model
