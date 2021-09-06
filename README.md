<h1 text-align="center">Acoustra Manager</h1>

<span id="acoustra"></span>

![Portfolio website](static/images/logo.png)

Welcome to Acoustra Manager where you get the opportunity to create your own profile directly on the band's website. You will have the means to create your own blogs and tasks and can edit, delete and update them. You will have access to available information the band have. You can select a date you may be interested in coming to see the band play or simply send in a request to see if they are available to come play in your neck of the woods.

Acoustra Manager is designed to be user friendly and easy access and navigate around the pages. It is customisable to suit the user's needs enabling them to have full control over any input they have. The Admin's page can be viewed but cannot be edited and that also applies to each individual user, they can create their own page but cannot alter another members page or input.

This project is the third out of four Milestone Projects in the Full Stack Web Development Program I am attending at The Code Institute.

**[View the Acoustra Manager project here.](https://acoustra-manager.herokuapp.com/)**

---

## Index 

- <a href="#ux">1. User experience (UX)</a>
  - <a href="#ux-goals">1.1. Project goals</a>
  - <a href="#ux-stories">1.2 User stories</a>
  - <a href="#ux-design">1.3 Design</a>
  - <a href="#ux-architecture">1.4 Information architecture</a>
  - <a href="#ux-mockup">1.5 Mockup designs</a>
- <a href="#features">2. Features</a>
  - <a href="#features-existing">2.1 Existing features</a>
  - <a href="#features-future">2.2 Features left to implement in the future</a>
- <a href="#technologies">3. Technologies used</a>
- <a href="#testing">4a. Testing</a>
- <a href="#bugs">4b. Bugs</a>
- <a href="#deployment">5. Deployment</a>
- <a href="#credits">6. Credits</a>
- <a href="#Acknowledge">7. Acknowledgements</a>
- <a href="#Acknowledge">8. Disclaimer</a>

---

<span id="ux"></span>

<h1>1. User experience (UX)</h1>

<span id="ux-goals"></span>

### 1.1 Project goals 

- Making a full-stack site that allows users to manage a common dataset about a particular domain. 
- Making a full-stack site that uses HTML, CSS, JavaScript, Python+Flask and MongoDB.
- Creating a website that serves as a platform where people can access band information and get involved in a more personal manner. 
- The user can create stories of their own experience with the band and check for live performances.
- The user can also request a booking for the band.
- Creating a website that is simple to understand and easy to navigate.
- The users of the website can make use of CRUD (create, read, update and delete) for the information they wish to include. 

<span id="ux-stories"></span>

### 1.2 User stories  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <a href="#bugs">(return to 4b).</a>

**First-time visitor goals:**
1. As a first time visitor, I want to be able to visit the website on every device, so that I can look at the website on desktop, mobile and tablet. 
2. As a first time visitor, I want to be able to navigate easily through the website, so I can find everything with minimul effort. 
3. As a first time visitor, I want to see an overview of all users, so I can get inspired by other people's stories or queries.
4. As a first time visitor, I want to be able to search for site content, so I can easily find what I'm looking for. 
5. As a first time visitor, I want to be able to search the site based on key words, so I can find information easily.
6. As a first time visitor, I want to register an account on the website, so I can share my experiences with other users. 

**Site member goals:** 

All the goals of first-time visitors also apply for site members. There are additional user stories to the site members because they have more access to the website. See the additional user stories below.
<br> 
1. As a site member, I want to add my blogs/tasks, so I can share my stories. 
2. As a site member, I want to edit my blogs/tasks, so I can update information in them.
3. As a site member, I want to delete my blogs/tasks, so I can remove them if no longer relevant. 
4. As a site member, I want to login to my profile, so I have access to my information. 
5. As a site member, I want to logout of my profile, when I leave the site.
6. As a site member, I want to add a task to find where the band may be playing or request a date to book them. 


**Admin goals:**

All the goals of the first time visitors and site members also apply for the admin. The admin has additional user stories to manage the categories of the site. 
1. As an admin, I want to add new categories, so I can make the categories clear and manageable. 
2. As an admin, I want to edit categories, so I can update categories. 
3. As an admin, I want to delete categories, so I can remove categories when they are no longer relevant. 

<span id="ux-design"></span>

### 1.3 Design 

- #### Colour scheme 
The five colours that are used for the Acoustra Manager website are very similar to the original website design for the band. I have chosen these colours to remain close to the original color scheme the banfd already use. 

![Colour scheme](static/images/colorscheme.jpg)

- **The black colour** is used for the background across all pages, this is to co-ordinate with the main colour the band use.
- **The white colour** is used on all input pages for clear and easy to see input received from the user.The white has a striking  contrast to the black colour. 
- **The lime colour** is the navbar and accordion dropdown selections. This colour again makes the comntrast with the black stand out more. 
- **The second lime colour** is used for the edit and delete buttons to distinquish against the existing background colours.
- **The deep orange accent colour**  is used to show important buttons.

- #### Fonts
The **Lato font** is used throughout the whole website. Sans serif is the fallback in case the main font isn’t being imported to the site correctly. This font is used because it is easy to read. 

- #### Icons
In the project, icons are used that are provided by [Font Awesome](https://fontawesome.com/). The Icons that are used have functional purposes such as the dropdown menu and social media icons. 

- #### Images
The images I used for this project came from [Acoustra](https://www.acoustraweddingband.com/). Images are used for the logo and picture on the home page. 

- #### Defensive design 

    - The user is not able to break the site by clicking on buttons. 
    - The signup form: 
        - The username has to be between 5-20 characters. 
        - The password has to be between 5-20 characters.
    - The add and edit forms:
     - The forms can be filled out to be between 1-3000 characters to allow the user to input their blog.
     - The category has to be chosen.
     - A blog, task or category can't be deleted by just one click. If someone clicks on the delete button, there wil be a pop up with a confirmation to delete the blog, task or category or else cancel back out of it.

- #### Interactive design 

    - The website has to be easy to navigate. 
    - The user can quickly find the information they want to find.
    - The user can easily find and select social media links to the bands other platforms. 



<span id="ux-architecture"></span>

### 1.4 Information architecture
The project has three collections in the database. The database in MongoDB is as follows: 

![Information architecture](static/images/mongoimage.png)

<span id="ux-mockup"></span>

### 1.5 Wireframe designs
Wireframe designs are made with [Balsamiq Wireframes](https://balsamiq.com/wireframes/)

Click on the link below to see the wireframes in Balsamiq.
  
|[Acoustra Manager Wireframes](static/images/acoustramanagerwireframes.pdf)| 

<span id="features"></span>

<h1>2. Features</h1>

<span id="features-existing"></span>

### 2.1 Existing features 

#### 1. Design 
- An attractive and simple layout with consistency.
- Simple navigation throughout the website by using the navigation bar. 
- Showing the blogs and tasks with clarity.

#### 2. General 
- The index page shows an introduction in the shape of a logo for the band and navbar menu.
- The page shows an image of the band and a and a little subtitle.
- There are links to the social media platforms at the bottom of the website. 
 

#### 3. Blogs & Tasks
- Blogs and Tasks can be created, read, updated and deleted (CRUD) by the users. 
- Blogs and Tasks can be sorted by category.
- People can search for Blogs and Tasks with the search bar. 
- Users have access to their profile, with an overview of all their Blogs and Tasks. 
- Blogs and Tasks include information the user wishes to share or queries they want answered.

#### 4. Signup, login and logout 
- People can create a new account on the web application. 
- People can login with their existing accounts. 
- People can easily log out.
- If a person creates a new account, logs in or logs out, a flashed message will appear with the action the person has done. 

<span id="features-future"></span>

### 2.2 Features left to implement in the future 
- A proper method to respond to a member.
- Adding a favorite section. Users can favorite a Blog or Task and see them on their favorite page. 
- Users could have the ability to upload pictures to their profile   
- Add form validation on the backend.
- The user can delete their profile.
- Create a merchandising page.
- Sign up for a newsletter option.
- Adding a search by category rather than just tasks or keywords.

<span id="technologies"></span>

<h1>3. Technologies used</h1>

#### Languages used
- [HTML5](https://en.wikipedia.org/wiki/HTML5)
    - HTML5 provides the structure and the content for my project. 
- [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)
    - CSS3 provides the style of the HTML5 elements.
- [jQuery](https://jquery.com/)
    - jQuery used as the JavaScript functionality.
- [Python](https://www.python.org/)
    - Python provides the backend of the project.

#### Frameworks, libraries & Other
- [Gitpod](https://www.gitpod.io/) 
    - The GitPod is used to develop the project.
- [Git](https://git-scm.com/)
    - The Git was used for version control to commit to Git and push to GitHub.
- [GitHub](https://github.com/)
    - The GitHub is used to host the project.
- [Google Fonts](https://fonts.google.com/)
    - Google Fonts is used to provide the font lato for all the text that is used in the project. 
- [Balsamiq](https://balsamiq.com/wireframes/)
    - Balsamiq is used to create the mockup designs for the project.
- [Materialize](https://materializecss.com/)
    - Materialize is used for the design framework.
- [MobgoDB](https://www.mongodb.com/1)
    - MongoDB is the fully managed cloud database service used for the project.
- [Heroku](https://dashboard.heroku.com/)
    - Heroku is the cloud platform to deploying the app.
- [Flask](https://flask.palletsprojects.com/en/1.1.x/)
    - Flask is the web framework used to provide libraries, tools and technologies for the app.
- [Jinja](https://jinja.palletsprojects.com/en/2.11.x/)
    - Jinja is used for templating Python
- [Werkzeug](https://werkzeug.palletsprojects.com/en/1.0.x/)
    - Werkzeug is used for password hashing and authentication and autohorization.

#### Testing tools used 
- [Chrome DevTools](https://developers.google.com/web/tools/chrome-devtools/open) is used to detect problems and test responsiveness.
- [Autoprefixer](https://autoprefixer.github.io/)
    - Autoprefixer is used to parse the CSS and to add vendor prefixes to CSS rules. 
- [W3C Markup Validation Service](https://validator.w3.org/)
    - The W3C Markup Validation Service is used to check whether there were any errors in the HTML5 code. 
- [W3C CSS validator](https://jigsaw.w3.org/css-validator/)
    - The W3C CSS validator is used to check whether there were any errors in the CSS3 code.
- [Beautify Tools](https://beautifytools.com/)
    - Beautify Tools is a JavaScript validator that is used to check whether there were any errors in the JavaScript code. 
- [PEP8](http://pep8online.com/)
    - The PEP8 validator is used to check whether there were any errors in the Python code.

<span id="testing"></span>

<h1>4a. Testing</h1>

The testing process can be found [here](static/images/validatorerrors.jpg).
<br>
The results can be found [here](static/images/validatorpass.jpg).
<br>
Test matrix on all devices attached [here](static/images/screenmatrix.png).
<br>

<span id="bugs"></span>


<h1>4b. Bugs</h1>

<ul>
<li>
I used the design goals above when the application was completed to build a set of test users stories<a href="#ux-stories">(1.2)</a>to confirm that all functionality conformed to the requirements.
</li>
<li>
I found errors showing up in the html validation process associated with jinja templating within the majority of the .html pages. The code managed perfectly without fault and without breaking. I tested the HTML code by running my server locally and used view page source. This code I passed through the validator. 
</li>
<li>
I tried to include a search by just category and could not get it to implement. I made attempts on mongodb to include a new search category but it would not work properly. I will try this again in a future endevour.
</li>
<li>
The edit and delete buttons didn't line up on every page but solved by using divs
</li>
<li>
When an unregistered user not logged in browsed the main blog page they were being shown a botton that allowed them to view the users profile and blogs. This was leading to a security risk but also causing an internal server error on the profile page because it expected a user value to be present. Fixed this with an if statement.
</li>
<li>
Main banner image was not displaying correctly after push to heroku. Realised I had an absolutle reference to an image on the dev server, corrected this to fix display
</li>
</ul>
<span id="deployment"></span>


<h1>5. Deployment</h1>

#### Requirements 
- Python3 
- Github account 
- MongoDB account 
- Heroku account

#### Clone the project 
To make a local clone, follow the following steps. 
1. Log in to GitHub and go to the repository. 
2. Click on the green button with the text **“Code”.**
3. Click on **“Open with GitHub Desktop”** and follow the prompts in the GitHub Desktop Application or follow the instructions from **[this link](https://docs.github.com/en/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/cloning-a-repository#cloning-a-repository-to-github-desktop)** to see how to clone the repository in other ways. 

#### Working with the local copy
1. Install all the requirements: Go to the workspace of your local copy. In the terminal window of your IDE type: **pip3 install -r requirements.txt**.
2. Create a database in MongoDB  
    - Signup or login to your MongoDB account.
    - Create a cluster and a database.
    - Create three collections in the db: **categories, tasks, users.**
    - Add string values for the collections. See <a href="#ux-architecture">my Information architecture</a> how the database is set up for this project.
3. Create the environment variables 
    - Create a .gitignore file in the root directory of the project.
    - Add the env.py file in the .gitignore.
    - Create the file env.py. This  will contain all the envornment variables.
    ```
    Import os
    os.environ.setdefault("IP", "Added by developer")
    os.environ.setdefault("PORT", "Added by developer")
    os.environ.setdefault("SECRET_KEY", "Added by developer")
    os.environ.setdefault("MONGO_URI", "Added by developer")
    os.environ.setdefault("MONGO_DBNAME", "Added by developer")
    ```
4. Run the app: Open your terminal window in your IDE. Type python3 app.py and run the app.

#### Heroku Deployment  
1. Set up local workspace for Heroku 
    - In terminal window of your IDE type: **pip3 freeze -- local > requirements.txt.** (The file is needed for Heroku to know which filed to install.)
    - In termial window of your IDE type: **python app.py > Procfile** (The file is needed for Heroku to know which file is needed as entry point.)
2. Set up Heroku: create a Heroku account and create a new app and select your region. 
3. Deployment method 'Github'
    - Click on the **Connect to GitHub** section in the deploy tab in Heroku. 
        - Search your repository to connect with it.
        - When your repository appears click on **connect** to connect your repository with the Heroku. 
    - Go to the settings app in Heroku and go to **Config Vars**. Click on **Reveal Config Vars**.
        - Enter the variables contained in your env.py file. it is about: **IP, PORT, SECRET_KEY, MONGO_URI, MONGO_DBNAME**
4. Push the requirements.txt and Procfile to repository. 
     ```
    $ git add requirements.txt
    $ git commit -m "Add requirements.txt"

    $ git add Procfile 
    $ git commit -m "Add Procfile"
    ```
5. Automatic deployment: Go to the deploy tab in Heroku and scroll down to **Aotmatic deployments**. Click on **Enable Automatic Deploys**. By **Manual deploy** click on **Deploy Branch**.

Heroku will receive the code from Github and host the app using the required packages. 
Click on **Open app** in the right corner of your Heroku account. The app wil open and the live link is available from the address bar. 


<span id="credits"></span>

<h1>6. Credits</h1>

#### Code
- [Flask error handling - Python on the web - Learning Flask ep. 18](https://www.youtube.com/watch?v=mBKKZN1MMBM)
- [W3Schools: HTML Input Pattern Attribute](https://www.w3schools.com/tags/att_input_pattern.asp)
- [W3Schools: HTML Input Attributes](https://www.w3schools.com/html/html_form_attributes.asp)
- [MaterializeCss: CSS Input Attributes](https://materializecss.com/)
- [Tim Neilson: Mini Project Walkthrough](https://codeinstitute.net/)

<span id="Acknowledge"></span>

<h1>7. Acknowledgements</h1>

Thanks to the following people and organizations who helped or inspired me for the project:  
- The support and guidance of Kieron Alexander and Johann in Code Institute. 
- Eoin Lynch for his incredible support throughout this project. 
- Juan Stelling for README file inspiration.
- The lessons and knowledge of [Code Institute.](https://codeinstitute.net/)


<span id="Disclaimer"></span>

<h1>8. Disclaimer</h1>
This project is for educational purposes only. All rights to the content was given by [Acoustra's.](https://www.acoustraweddingband.com/) full consent for this project.

Thank You

<a href="#acoustra">Back to top!</a>
