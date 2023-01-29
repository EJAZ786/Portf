<!DOCTYPE html>
<html>
  <head>
    <title>My Portfolio</title>
    <style>
      /* Add your CSS styles here */
      .header {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 1rem;
      }
      .header h1 {
        font-size: 2rem;
        margin: 0;
      }
      .header nav {
        display: flex;
        list-style: none;
        margin: 0;
        padding: 0;
      }
      .header nav a {
        font-size: 1.2rem;
        margin-left: 1rem;
        text-decoration: none;
        color: black;
      }
      .header nav a:hover {
        color: gray;
      }
      .intro {
        padding: 2rem;
        text-align: center;
      }
      .intro h2 {
        font-size: 1.5rem;
        margin-bottom: 1rem;
      }
      .intro p {
        font-size: 1.2rem;
        margin: 0;
      }
      .projects {
        display: flex;
        flex-wrap: wrap;
        justify-content: space-between;
      }
      .project {
        width: calc(33.33% - 1rem);
        background-color: lightgray;
        padding: 1rem;
        text-align: center;
      }
      .project h3 {
        font-size: 1.2rem;
        margin-bottom: 1rem;
      }
      .project p {
        font-size: 1rem;
        margin: 0;
      }
      .footer {
        padding: 1rem;
        text-align: center;
      }
      .footer p {
        font-size: 1rem;
        margin: 0;
      }
    </style>
  </head>
  <body>
    <header class="header">
      <h1>My Portfolio</h1>
      <nav>
        <a href="#intro">Intro</a>
        <a href="#projects">Projects</a>
      </nav>
    </header>
    <section class="intro" id="intro">
      <h2>Hi, I'm Abdul ejaz</h2>
      <p>Web Developer</p>
    </section>
    <section class="projects" id="projects">
      <div class="project">
        <h3>Project 1</h3>
        <p>L.</p>
      </div>
      <div class="project">
        <h3>Project 2</h3>
        <p>I am Android Developer .</p>
      </div>
  
