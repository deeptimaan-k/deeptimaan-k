<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Deeptimaan K - Portfolio</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    
    body {
      font-family: 'Fira Code', monospace;
      background-color: #0f172a;
      color: #e2e8f0;
    }
    
    #particles-js {
      position: absolute;
      width: 100%;
      height: 100%;
      top: 0;
      left: 0;
      z-index: 1;
    }
    
    .hero-container {
      position: relative;
      height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      z-index: 2;
    }
    
    .hero-content {
      text-align: center;
      padding: 20px;
    }
    
    .typing-text {
      color: #6366F1;
      font-weight: 600;
      font-size: 28px;
      margin-bottom: 30px;
    }
    
    .hero-image {
      width: 400px;
      max-width: 90%;
      margin: 20px 0;
    }
    
    .hero-description {
      max-width: 800px;
      margin: 20px auto;
      font-weight: 500;
      line-height: 1.6;
    }
    
    .social-links {
      margin-top: 20px;
    }
    
    .social-button {
      display: inline-block;
      margin: 0 5px;
      padding: 8px 20px;
      background-color: #6366F1;
      color: white;
      text-decoration: none;
      border-radius: 5px;
      font-weight: 600;
      transition: all 0.3s ease;
    }
    
    .social-button:hover {
      transform: translateY(-3px);
      box-shadow: 0 5px 15px rgba(99, 102, 241, 0.4);
    }
  </style>
</head>
<body>
  <!-- Particles.js Container -->
  <div id="particles-js"></div>
  
  <!-- Hero Section -->
  <div class="hero-container">
    <div class="hero-content">
      <div class="typing-text" id="typing-text">Hi, I'm Deeptimaan 👋</div>
      
      <img src="https://user-images.githubusercontent.com/109351602/202650321-7f4da361-f98f-4345-8df4-adf352a11322.gif" class="hero-image" alt="Coding">
      
      <p class="hero-description">
        <b>Passionate engineering student transforming ideas into elegant solutions. Specializing in full-stack development and machine learning with a knack for collaborative problem-solving.</b>
      </p>
      
      <div class="social-links">
        <a href="https://deeptimaank.netlify.app/" class="social-button">Portfolio</a>
        <a href="mailto:deeptimaankrishnajadaun@gmail.com" class="social-button">Email</a>
        <a href="https://github.com/deeptimaan-k" class="social-button">GitHub</a>
      </div>
    </div>
  </div>

  <!-- Load particles.js library from CDN -->
  <script src="https://cdnjs.cloudflare.com/ajax/libs/particles.js/2.0.0/particles.min.js"></script>
  
  <!-- Load Typed.js for the typing effect -->
  <script src="https://cdnjs.cloudflare.com/ajax/libs/typed.js/2.0.12/typed.min.js"></script>
  
  <script>
    // Initialize particles.js
    particlesJS("particles-js", {
      particles: {
        number: {
          value: 80,
          density: {
            enable: true,
            value_area: 800
          }
        },
        color: {
          value: "#6366F1"
        },
        shape: {
          type: "circle",
          stroke: {
            width: 0,
            color: "#000000"
          }
        },
        opacity: {
          value: 0.5,
          random: false,
          anim: {
            enable: false,
            speed: 1,
            opacity_min: 0.1,
            sync: false
          }
        },
        size: {
          value: 3,
          random: true,
          anim: {
            enable: false,
            speed: 40,
            size_min: 0.1,
            sync: false
          }
        },
        line_linked: {
          enable: true,
          distance: 150,
          color: "#6366F1",
          opacity: 0.4,
          width: 1
        },
        move: {
          enable: true,
          speed: 6,
          direction: "none",
          random: false,
          straight: false,
          out_mode: "out",
          bounce: false,
          attract: {
            enable: false,
            rotateX: 600,
            rotateY: 1200
          }
        }
      },
      interactivity: {
        detect_on: "canvas",
        events: {
          onhover: {
            enable: true,
            mode: "grab"
          },
          onclick: {
            enable: true,
            mode: "push"
          },
          resize: true
        },
        modes: {
          grab: {
            distance: 140,
            line_linked: {
              opacity: 1
            }
          },
          bubble: {
            distance: 400,
            size: 40,
            duration: 2,
            opacity: 8,
            speed: 3
          },
          repulse: {
            distance: 200,
            duration: 0.4
          },
          push: {
            particles_nb: 4
          },
          remove: {
            particles_nb: 2
          }
        }
      },
      retina_detect: true
    });

    // Initialize typing effect
    document.addEventListener('DOMContentLoaded', function() {
      const options = {
        strings: ["Hi, I'm Deeptimaan 👋", "Engineering Student", "Full Stack Developer", "ML Enthusiast", "Problem Solver", "RadianT Coder"],
        typeSpeed: 50,
        backSpeed: 30,
        backDelay: 1000,
        startDelay: 500,
        loop: true
      };
      
      new Typed('#typing-text', options);
    });
  </script>
</body>
</html>

## 🚀 About Me
```javascript
const deeptimaan = {
  education: "Engineering Student",
  focus: ["Machine Learning", "Full Stack Development"],
  currentProjects: ["ML Project", "React Native App"],
  funFact: "Known as RadianT in coding communities",
  location: "India",
  passions: ["Problem Solving", "Collaborative Coding", "Learning New Tech"]
};
```

- 🔭 Currently working on **Advanced Machine Learning Projects**
- 🌱 Learning **TensorFlow and Cloud Architecture**
- 👨‍💻 Portfolio: [deeptimaank.netlify.app](https://deeptimaank.netlify.app/)
- 📫 Reach me at: **deeptimaankrishnajadaun@gmail.com**
- ⚡ Fun fact: **I transform coffee into code**

## 🛠️ Tech Stack

<div align="center">

  ### Languages
  ![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
  ![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
  ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
  ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
  ![Kotlin](https://img.shields.io/badge/Kotlin-0095D5?style=for-the-badge&logo=kotlin&logoColor=white)
  
  ### Frontend
  ![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
  ![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
  ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
  ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
  ![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
  
  ### Backend & Database
  ![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
  ![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
  ![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
  ![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)
  ![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=black)
  
  ### Tools & Platforms
  ![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
  ![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
  ![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
  ![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
  
  ### ML/AI
  ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
  ![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
  ![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
  
</div>

## 🏆 Achievements
- 🥇 Completed 200+ LeetCode challenges
- 🏆 Top performer in campus hackathons
- 📚 Published research paper on ML applications
- 🌟 Open-source contributor

## 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=deeptimaan-k&show_icons=true&locale=en&layout=compact&theme=tokyonight&bg_color=1e293b&border_color=475569&text_color=e2e8f0&title_color=a78bfa" alt="Top Languages" />
  
  <img src="https://github-readme-stats.vercel.app/api?username=deeptimaan-k&show_icons=true&locale=en&theme=tokyonight&bg_color=1e293b&border_color=475569&text_color=e2e8f0&title_color=a78bfa&icon_color=6366f1" alt="GitHub Stats" />
  
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=deeptimaan-k&theme=tokyonight&background=1e293b&border=475569&stroke=475569&ring=a78bfa&fire=6366f1&currStreakNum=e2e8f0&sideNums=e2e8f0&currStreakLabel=a78bfa&sideLabels=a78bfa&dates=94a3b8" alt="GitHub Streak" />
</div>

## 📌 Featured Projects

<div align="center">
  <a href="https://github.com/deeptimaan-k/RadianT-Movies">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=deeptimaan-k&repo=RadianT-Movies&theme=tokyonight&bg_color=1e293b&border_color=475569&text_color=e2e8f0&title_color=a78bfa&icon_color=6366f1" alt="Featured Project" />
  </a>
  <a href="https://github.com/deeptimaan-k/Movies_react">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=deeptimaan-k&repo=Movies_react&theme=tokyonight&bg_color=1e293b&border_color=475569&text_color=e2e8f0&title_color=a78bfa&icon_color=6366f1" alt="Featured Project" />
  </a>
</div>


## 🌐 Connect With Me

<div align="center">
  
  [![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/deeptimaan_k)
  [![Facebook](https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white)](https://fb.com/deeptimaankrishnajadaun)
  [![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/deeptimaan_k)
  [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/deeptimaan-k)
  [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/deeptimaan-k)
  
</div>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=deeptimaan-k&label=Profile%20views&color=6366f1&style=for-the-badge" alt="Profile views" />
</div>

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=200&size=12&pause=1000&color=6366F1&center=true&vCenter=true&width=435&lines=Building+tomorrow's+solutions+today" alt="Typing SVG" />
</div>
