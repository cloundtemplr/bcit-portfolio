<!DOCTYPE >
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport">
    <title>KMS's Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Noto+Sans&family=Young+Serif&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="mypage.css">
  </head>
  <body>
    <main>
      <!-- ***************  ABOUT / PROFILE  **************** -->
      <header>
        <div class="content-wrap">
          <h1>Min Seuk Kim</h1>
          <h2>CIT International Student</h2>
          <img src="my_photo.jpg" alt="my_photo">
          <p> As a CIT student, I'm trying to be a database system specialist of Computer Information Technology.<br>
              
        </div>
      </header>


      <!-- ****************  WORK EXPERIENCE  ******************** -->
      <section class="work-experience">
        <div class="content-wrap">
          <h2>Work Experience</h2>
        

          <!-- Job 1 -->
          <section class="job-item">
            <div class="job-details">
              <h3>Forestry Technologist</h3>
              <p>Taewang Forestry, South Korea</p>
              <p>January 2018 - November 2018</p>
            </div>
            <div class="job-summary">
              <p><strong>Duty</strong></p>
              <ul>
                <li>Measuring trees</li>
                <li>Planning forest management</li>
                <li>Managing facilities in forest</li>
              </ul>
            </div>
          </section>

          <!-- Job 2 -->
          <section class="job-item">
            <div class="job-details">
              <h3>Carpenter</h3>
              <p>Noh Design & Construction, Canada</p>
              <p>July 2020 - June 2022</p>
            </div>
            <div class="job-summary">
              <p><strong>Duty</strong></p>
              <ul>
                <li>Renovation for resturants and houses</li>
                <li>Demolition</li>
                <li>Tiling</li>
                <li>Wood work for framing</li>
                <li>Drywall work</li>
                <li>Electircity work</li>
              </ul>
            </div>
          </section>

          <!-- Job 3 -->
          <section class="job-item">
            <div class="job-details">
              <h3>Cook & Sub-Manager</h3>
              <p>Chung Chun Rice Hotdog</p>
              <p>October 2021 - December 2022</p>
            </div>
            <div class="job-summary">
              <p><strong>Duty</strong></p>
              <ul>
              <li>Managing employees</li>
              <li>Managing ingredients</li>
              <li>Frying Hotdogs</li>
              </ul>
            </div>
          </section>
        </div>
      </section>

      <!-- *************  EDUCATION & CERTIFICATIONS *********** -->
      <section class="education">
        <div class="content-wrap">
          <h2>Education</h2>

          <section>
            <h3>Kangwon National University, South Korea</h3>
            <p>Bachelor of Forest Management, 2010 - 2017</p>
          </section>

          <section>
            <h3>British Columbia Institute of Technology, BC, Canada</h3>
            <p>Diploma of Computer Information Technology, Fall 2023 ~ </p><br>
            <h3>Current courses</h3>
            
            <h3>Fundamental Web Technology(ACIT1620):</h3>
              <li>Building the structure of webpages with HTML</li>
              <li>Styling text and content with CSS</li>
              <li>Dynamically updating the content and style of pages with client-side scripting techniques</li></li></ul>
              
            <h3>Database system(ACIT1630):</h3>
              <li>Covering relational and NoSQL database technologies</li>
              <li>Basic concepts, relational algebra, enhanced entity-relationship and NoSQL data modeling, functional dependencies and normalization, design methodology, SQL query language (DDL and DML), views, security and transaction management</li>

            <h3>Scripting for IT(ACIT1515):</h3>
              <li>Introducing the fundamental concepts of programming for IT professionals</li>
              <li>Focusing on scripting languages that are commonly found in the workplace</li>
              <li>Design, implement, test, and debug programs that incorporate</li>
                
            
            
          </section>
        </div>
      </section>

      <!-- CONTACT -->
      <footer>
        <div class="content-wrap">
          <h2>Contacts</h2>
          <ul class="contact-list">
            <li><a href="mailto:mkim311@my.bcit.ca">mkim311@my.bcit.ca</a></li>
            <li><a href="mailto:Phone:778-888-8888">Phone: 778-888-8888</a></li>
          </ul>
        </div>
      </footer>
    </main>
  </body>
</html>

html {
    box-sizing: border-box;
  }
  *, *:before, *:after {
    box-sizing: inherit;
  }
  
  body {
    color: #343434;
    margin: 0;
    padding: 0;
    font-family: 'Noto Sans', sans-serif;
    font-size: 15px;
    line-height: 1.5;
  }
  img {
    width: 300px;
  }
  a {
    color: #FFE66D;
  }
  a:hover {
    text-decoration: none;
  }
  h1 {
    font-size: 100px;
    line-height: 1;
  }
  h2 {
    font-size: 45px;
  }
  h1, h2 {
    font-family: 'Noto Sans', sans-serif;
    font-weight: 400;
    margin: 0;
  }
  .content-wrap {
    width: 800px;
    margin: 0 auto;
    padding: 60px 0;
  }
  
  
  
  /* Profile
  ------------------------------------*/
  header {
    background: lightskyblue;
    color: black;
    text-align: center;
  }
  
  img{
    width: 200px;
    height: auto;
  }
  
  
  /* Work Experience
  ------------------------------------*/
  .work-experience {
    background: white;
  }
  .job-item {
    display: grid;
    grid-template-columns: 1fr 2fr;
    column-gap: 20px;
  }
  
  
  /* Education
  ------------------------------------*/
  .education {
    background: gray;
  }
  .job-item {
    display: grid;
    grid-template-columns: 1fr 2fr;
    column-gap: 20px;
  }
  
  
  /* Contact Info
  ------------------------------------*/
  footer {
    background: black;
    color: white;
    text-align: center;
  }
  .contact-list {
    list-style-type: none;
    padding: 0;
    display: flex;
    justify-content: center;
  }
  .contact-list a {
    padding: 15px;
    display: inline-block;
  }

  @media (max-width: 768px) {
    .content-wrap img {
      max-width: 70%;
    }
    .content-wrap {
      width: auto;
      margin: 0 auto;
      padding: 60px 0;
    }
   
    .content-wrap h1 {
      font-size: 250%;
  }
    .content-wrap h2 {
      font-size: 130%;
  }
  
    .content-wrap p {
      font-size: 100%;
  }
   }

   @media (max-width: 480px) {
    .content-wrap img {
      max-width: 50%;
    }
    .content-wrap {
      width: auto;
      margin: 0 auto;
      padding: 60px 0;
    }
    
    .content-wrap h1 {
      font-size: 200%;
  }
    .content-wrap h2 {
        font-size: 110%;
    }
    
    .content-wrap p {
        font-size: 100%;
    }
  }
