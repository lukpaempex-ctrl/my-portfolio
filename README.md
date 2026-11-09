
<!DOCTYPE html>
<html lang="th">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Portfolio | ธรณิศ เกษมสุข</title>

<style>
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: #f0f4fa;
  color: #26364a;
}

header {
  background: linear-gradient(135deg, #102b4e, #28649a);
  color: white;
  text-align: center;
  padding: 60px 20px;
}

.profile-img {
  width: 190px;
  height: 190px;
  object-fit: cover;
  border-radius: 50%;
  border: 5px solid white;
  margin-bottom: 15px;
}

header h1 {
  font-size: 30px;
  margin: 10px;
}

header p {
  font-size: 17px;
  margin: 8px;
}

nav {
  background: #102b4e;
  text-align: center;
  padding: 16px;
}

nav a {
  color: white;
  text-decoration: none;
  margin: 10px;
  font-size: 15px;
}

section {
  max-width: 850px;
  margin: 30px auto;
  padding: 30px;
  background: white;
  border-radius: 15px;
  box-shadow: 0 4px 12px #00000010;
}

h2 {
  color: #174b80;
  border-bottom: 2px solid #d7e5f5;
  padding-bottom: 10px;
}

section p {
  line-height: 1.9;
  font-size: 16px;
}

footer {
  background: #102b4e;
  color: white;
  text-align: center;
  padding: 25px;
}

@media(max-width:600px) {
  header h1 {
    font-size: 25px;
  }

  nav a {
    display: inline-block;
    margin: 6px;
  }

  section {
    margin: 18px 12px;
    padding: 22px;
  }
}
</style>
</head>

<body>

<header>

  <img src="profile.jpeg"
       class="profile-img"
       alt="รูปโปรไฟล์">

  <h1>นาย ธรณิศ เกษมสุข</h1>

  <p>MY PORTFOLIO</p>

  <p>แฟ้มสะสมผลงาน</p>

  <p>สาขาวิศวกรรมโยธา</p>

  <p>นักเรียนชั้นมัธยมศึกษาปีที่ 6</p>

</header>

<nav>
  <a href="#about">ประวัติส่วนตัว</a>
  <a href="#education">การศึกษา</a>
  <a href="#goal">เป้าหมาย</a>
</nav>

<section id="about">
  <h2>ABOUT ME | ประวัติส่วนตัว</h2>

  <p>
    สวัสดีครับ ผมชื่อ นาย ธรณิศ เกษมสุข
    ปัจจุบันกำลังศึกษาอยู่ระดับชั้นมัธยมศึกษาปีที่ 6
  </p>

  <p>
    ผมเป็นคนที่มีความสนใจด้านวิทยาศาสตร์
    คณิตศาสตร์ และเทคโนโลยี
    ชอบเรียนรู้สิ่งใหม่ ๆ และพัฒนาความสามารถของตนเอง
  </p>
</section>

<section id="education">
  <h2>EDUCATION | ประวัติการศึกษา</h2>

  <p>
    ระดับมัธยมศึกษาตอนปลาย
  </p>

  <p>
    โรงเรียน : ................................
  </p>

  <p>
    แผนการเรียน : ................................
  </p>
</section>

<section id="goal">
  <h2>MY GOAL | เป้าหมายในอนาคต</h2>

  <p>
    ผมมีความตั้งใจที่จะศึกษาต่อในสาขาวิศวกรรมโยธา
    เพราะมีความสนใจเกี่ยวกับการออกแบบ
    การก่อสร้างอาคารและโครงสร้างพื้นฐาน
  </p>

  <p>
    ผมหวังว่าจะนำความรู้และประสบการณ์
    ไปพัฒนาตนเองให้เป็นวิศวกรโยธาที่มีคุณภาพ
    และสามารถสร้างประโยชน์ให้กับสังคมได้
  </p>
</section>

<footer>
  <h3>THANK YOU</h3>
  <p>ขอบคุณที่เข้าชม Portfolio ของผม</p>
  <p>THORANIT KASEMSUK</p>
</footer>

</body>
</html>
