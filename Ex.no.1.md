# Ex01 Portfolio
## Date:04.03.2025

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
## HOME
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>profile</title>
</head>
<style>
    .container{
            margin: 20px;
            padding: 60px;
            border: 10px;
            display: flex;
            justify-content: center;
            flex-direction: row;
            flex-wrap: wrap;}
</style>
<body style="background-image: url(portme.jpeg); background-size: 100%">
<marquee style="color: aliceblue;">WELCOME TO MY PROFILE</marquee>
<header>
    <nav  style=" text-align:start;">
        <a href="http://127.0.0.1:5501/exp.html" style="text-decoration: none; color: whitesmoke; text-align: right; padding: 20px;">EXPERIENCE</a>
        <a href="http://127.0.0.1:5501/cont.html" style="text-decoration: none; color: whitesmoke; text-align: right; padding: 08px;">CONTACTS</a>
    </nav>
</header>
<div class="container">
    <div class="box" style="border: 07px solid whitesmoke; padding: 05px;"><img src="me.jpg" alt="" height="300px" width="300px"></div>    
</div>
<h2 style="text-align: center; color: goldenrod;">SANTHA RAMANATH M</h2>
<p style= "font-style: oblique; text-align: center; padding: 20px; font-size:large ; color: whitesmoke;">I’m a second-year student at Saveetha Engineering College. 
    I’m passionate about Full Stack Development and I'm focused on expanding my knowledge and skills. 
    I enjoy being involved in clubs, extracurriculars, or hobbies and strive to balance academics with personal growth. 
    I’m excited for the opportunities ahead and look forward to further developing both academically and professionally.
</p>
</body>
</html>
```
## EXPERIENCE
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EXPERIENCE</title>
</head>
<style>
    .box{
            margin: 0px;
            padding: 0px;
            border: 0px;
            display: flex;
            justify-content: center;}
</style>
<body style="background-color: rgb(224, 217, 218);">
    <div>
        <h3 style="text-align: center; padding: 50px; padding: 30px; font-weight: 1000;">** INTERNSHIP EXPERIENCE **</h3>
        <div class="box"><img src="intern2.png" height="300px" width="300px" style="padding: 10px;;"></div>
    <h1 style="text-align: justify; padding: 10px; font-size: larger; font-style: oblique; margin: 10px;">During my internship at Retech Solution, I had the opportunity to work on full-stack development, gaining hands-on experience with both front-end and back-end technologies. I was involved in the design, development, and deployment of web applications, collaborating with a talented team of developers to build user-friendly interfaces and scalable server-side logic. I worked with technologies such as HTML, CSS, JavaScript, React for the front end, and Node.js, Express, and MongoDB for the back end. Throughout the internship, I learned how to integrate various components of an application, troubleshoot issues, and follow best practices in coding and development processes. This experience greatly enhanced my technical skills, and I gained valuable insights into the software development lifecycle.</h1> 
</body>
</html>

```
## CONTACT
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CONTACTS</title>
    <style>
        .contact-info {
    text-align: center;
    font-size: 1.2rem;
}
        .contact-info a {
    color: #1abc9c;
    text-decoration: none;
}

.contact-info a:hover {
    text-decoration: underline;
}

.contact-info p {
    margin-bottom: 1rem;
}

footer {
    background: #2c3e50;
    color: white;
    text-align: center;
    padding: 2rem;
    width: 100%;
}

footer p {
    font-size: 1.1rem;
}
    </style>
</head>

<body style="background-color:skyblue;">
    <section id="contact" class="contact">
        <h2 style="text-align: center;">** GET IN TOUCH **</h2>
        <div class="contact-info">
            <p>Email: <a href="#">santharamanath@gmail.com</a></p>
            <p>Phone: <a href="#"></a>+91-938527410</p>
            <p>LinkedIn: <a href="#"></a>Santha ramanath M</p>
        </div>
    </section>
</div>

<footer>
    <p>© 2025 Santharamanath M.Crafted with dedication and innovation.</p>
</footer>
</html>

```


## OUTPUT
![Screenshot 2025-04-29 155649](https://github.com/user-attachments/assets/91e566ac-9a03-4996-bd3f-48d4860e942f)

![Screenshot 2025-04-29 155625](https://github.com/user-attachments/assets/f04a8773-285e-4511-8dae-e9cdea3248ea)

![Screenshot 2025-04-29 155637](https://github.com/user-attachments/assets/1a511198-9c8c-4bf0-a5d4-72741181ce77)


## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
