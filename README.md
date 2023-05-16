# Portfolio
<!DOCTYPE html>
<html>
<head>
  <title>Student Portfolio</title>
  <link rel="stylesheet" type="text/css" href="poc.css">
</head>
<body>
  <header>
    <div class="container">
      <h1>Priya's Portfolio</h1>
      <img src="C:\Users\lakshmi\Downloads\stu.jpg" alt="Profile Picture">
    </div>
  </header>

  <main>
    <section id="objective">
      <h2>Career Objective</h2>
      <p>To secure a challenging position in a reputable organization and contribute my skills to achieve the company's goals.</p>
    </section>

    <section id="education">
      <h2>Education</h2>
      <div class="content-box">
        <h3>Bachelor of Science in Computer Science</h3>
        <p>Stanford University | 2021-2025</p>
      </div>
    </section>

    <section id="skills">
      <h2>Skills</h2>
      <div class="content-box">
        <ul>
          <li>HTML</li>
          <li>CSS</li>
          <li>JavaScript</li>
          <li>C,C++</li>
          <li>Java</li>
        </ul>
      </div>
    </section>

    <section id="personal">
      <h2>Personal Details</h2>
      <div class="content-box">
        <ul>
          <li><strong>Name:</strong>lakshmi priya karella</li>
          <li><strong>Email:</strong> karellah123email.com</li>
          <li><strong>Phone:</strong>9866953608</li>
          <li><strong>Address:</strong>13-81/23,Main Street,onetown,XWY</li>
        </ul>
      </div>
    </section>
  </main>
</body>
</html>
#CSS file
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f2f2f2;
}

header {
  background-color: #333;
  color: #fff;
  padding: 20px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.container {
  display: flex;
  align-items: center;
}

.container h1 {
  background-color: #555;
  padding: 10px;
  border-radius: 5px;
  margin-right: 20px;
}

img {
  width: 80px;
  height: 80px;
  border-radius: 50%;
}

main {
  padding: 20px;
}

section {
  margin-bottom: 20px;
}

section h2 {
  background-color: #555;
  color: #fff;
  padding: 10px;
  border-radius: 5px;
}

.content-box {
  background-color: #fff;
  padding: 20px;
  border-radius: 5px;
}

ul {
  list-style: none;
  padding: 0;
}

ul li {
  margin-bottom: 5px;
}
