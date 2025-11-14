 ATIK HASAN
 <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>GitHub Menu Generator</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #f6f8fa;
      margin: 0;
      padding: 20px;
    }

    .menu {
      width: 250px;
      background-color: #fff;
      border: 1px solid #e1e4e8;
      border-radius: 6px;
      box-shadow: 0 1px 3px rgba(27,31,35,0.12);
      padding: 10px 0;
    }

    .menu-item {
      padding: 10px 20px;
      cursor: pointer;
      color: #24292f;
      display: flex;
      justify-content: space-between;
      align-items: center;
      transition: background 0.2s;
    }

    .menu-item:hover {
      background-color: #f6f8fa;
    }

    .submenu {
      display: none;
      flex-direction: column;
      padding-left: 20px;
    }

    .submenu-item {
      padding: 8px 20px;
      cursor: pointer;
      color: #57606a;
      transition: background 0.2s;
    }

    .submenu-item:hover {
      background-color: #f6f8fa;
    }

    .menu-item.open + .submenu {
      display: flex;
    }

    .arrow {
      font-size: 12px;
      transition: transform 0.2s;
    }

    .menu-item.open .arrow {
      transform: rotate(90deg);
    }
  </style>
</head>
<body>
  <div class="menu">
    <div class="menu-item" onclick="toggleMenu(this)">
      Home <span class="arrow">▶</span>
    </div>
    <div class="submenu">
      <div class="submenu-item">Dashboard</div>
      <div class="submenu-item">Activity</div>
    </div>

    <div class="menu-item" onclick="toggleMenu(this)">
      Projects <span class="arrow">▶</span>
    </div>
    <div class="submenu">
      <div class="submenu-item">Repository 1</div>
      <div class="submenu-item">Repository 2</div>
    </div>

    <div class="menu-item" onclick="toggleMenu(this)">
      Settings <span class="arrow">▶</span>
    </div>
    <div class="submenu">
      <div class="submenu-item">Profile</div>
      <div class="submenu-item">Account</div>
    </div>
  </div>

  <script>
    function toggleMenu(element) {
      element.classList.toggle('open');
    }
  </script>
</body>
</html>



 
![](https://media.licdn.com/dms/image/v2/D4E03AQFZvCtc-5Aerw/profile-displayphoto-shrink_800_800/B4EZPVf.mmHEAc-/0/1734453751869?e=1764201600&v=beta&t=0EeBMiwkKh8yLZbkB_GpOhdYo_8J8RP_kgV3oqQn6BA)
UNDERGRADUATE STUDENT



## 📘 About Me
-am an undergraduate student in Economics at the University of Rajshahi, and I am building my academic foundation to pursue future research opportunities in applied economics. My research interests lie at the intersection of development economics, health economics, agricultural economics, and environmental economics. I am particularly interested in how households and communities in low- and middle-income countries make decisions under various economic and environmental constraints.

I aim to focus on empirical research methods, including econometric analysis, causal inference, and the use of machine learning tools with survey and administrative data. I am motivated to understand real-world challenges related to agriculture, public health, and sustainable development



## 🧩on going  Projects
- research paper : Iportance of information and communication technology on disaster management, astudy on southeastern region in Bangladesh



## 🌐 Contact
- 📧 Email: s2210842131@ru.ac.bd
- 🔗 GitHub: [github.com/atik-hasan](https://github.com/atik-hasan)
