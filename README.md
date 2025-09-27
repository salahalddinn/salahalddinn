<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <!-- <link rel="stylesheet" href="v.css"> -->
</head>
<style>

    /* استدعاء خط */
body {
  margin: 0;
  font-family: 'Cairo', sans-serif;
  line-height: 1.6;
  background: #0f172a;
  color: #f1f5f9;
}

/* الهيدر */
header {
  height: 100vh;
  background: url('https://images.unsplash.com/photo-1503264116251-35a269479413?ixlib=rb-4.0.3&auto=format&fit=crop&w=1950&q=80') no-repeat center/cover;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  position: relative;
}

header .overlay {
  background: rgba(15, 23, 42, 0.75);
  padding: 2rem;
  border-radius: 20px;
}

header h1 {
  font-size: 3rem;
  color: #38bdf8;
  margin-bottom: 10px;
}

header p {
  font-size: 1.2rem;
  margin-bottom: 20px;
}

.btn {
  display: inline-block;
  padding: 10px 25px;
  background: linear-gradient(90deg, #06b6d4, #7c3aed);
  color: white;
  text-decoration: none;
  border-radius: 30px;
  font-weight: bold;
  transition: 0.3s;
}

.btn:hover {
  transform: scale(1.1);
  box-shadow: 0 0 15px #38bdf8;
}

/* الأقسام */
section {
  padding: 60px 20px;
  text-align: center;
}
h3{
     font-size: 1.5rem;
  margin-bottom: 20px;
  color: cadetblue;

}

h2 {
  font-size: 2rem;
  margin-bottom: 30px;
  color: #38bdf8;
}

/* المهارات */
.skills-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
  gap: 15px;
}

.skill {
  background: #1e293b;
  padding: 15px;
  border-radius: 10px;
  font-weight: bold;
  transition: 0.3s;
}

.skill:hover {
  background: linear-gradient(90deg, #06b6d4, #7c3aed);
  color: white;
  transform: scale(1.05);
}

/* المشاريع */
.projects-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
}

.project-card {
  background: #1e293b;
  padding: 20px;
  border-radius: 15px;
  text-align: center;
  transition: 0.3s;
}

.project-card:hover {
  transform: translateY(-10px);
  box-shadow: 0 5px 20px rgba(56, 189, 248, 0.3);
}

/* التواصل */
.contact-links a {
  display: inline-block;
  margin: 10px;
  padding: 10px 20px;
  border: 2px solid #38bdf8;
  border-radius: 25px;
  text-decoration: none;
  color: #38bdf8;
  transition: 0.3s;
}

.contact-links a:hover {
  background: #38bdf8;
  color: #0f172a;
  box-shadow: 0 0 15px #38bdf8;
}

/* الفوتر */
footer {
  background: #1e293b;
  padding: 15px;
  text-align: center;
  font-size: 0.9rem;
  color: #94a3b8;
}
</style>
<body>
    
    <!-- Banner متحرك -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:7c3aed,100:06b6d4&height=220&section=header&text=صلاح%20الدين%20سمير%20حنيش&fontSize=45&fontColor=ffffff&animation=fadeIn" />
</p>

<h3 align="center">🚀 مطور شغوف بالتقنية و البرمجة</h3>





 <h3 align="center">🎓 طالب ومهتم بتطوير  تطبيقات الويب والموبايل  </h3><br>
<h3 align="center"> 🌱 أتعلم حاليا Flutter, Dart, Python </h3> <br>
 <h3 align="center">🤝 أحب التعاون والعمل الجماعي  </h3><br>
<h3 align="center"> ⚡ شغفي: الإبداع وابتكار الحلول التقنية  </h3><br>



<h3 align="center">🛠️ المهارات</h3><br>
<p align="center">
  <img src="https://skillicons.dev/icons?i=html,css,js,python,java,php,mysql,git,dart,flutter&perline=5" />
</p>

<br>

<h3 align="center">📊 إحصائيات GitHub</h3><br>
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=USERNAME&show_icons=true&theme=tokyonight" height="160" />
  <br>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=USERNAME&layout=compact&theme=tokyonight" height="160" />
</p>

<br>

<h3 align="center">🌐 تواصل معي</h3><br>
<p align="center">
  <a href="https://linkedin.com/in/username" target="_blank">
    <img src="https://img.shields.io/badge/-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <br>
  <a href="mailto:youremail@gmail.com" target="_blank">
    <img src="https://img.shields.io/badge/-Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  <br>
  <a href="https://github.com/USERNAME" target="_blank">
    <img src="https://img.shields.io/badge/-GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
</p>

<br>
<!-- Footer متحرك -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:06b6d4,100:7c3aed&height=120&section=footer"/>
</p>
</body>
</html>
