## Hi there 👋


<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Tech Stack Banner</title>
  <style>
    :root {
      --bg: #0b0f13;
      --card: #0f1720;
      --accent: linear-gradient(90deg, #6ee7b7, #60a5fa);
    }

    html, body {
      height: 100%;
      margin: 0;
      font-family: Inter, ui-sans-serif, system-ui, Segoe UI, Roboto, 'Helvetica Neue', Arial;
      background: var(--bg);
      color: #e6eef6;
    }

    .banner {
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      background: radial-gradient(1200px 400px at 10% 10%, rgba(96,165,250,0.06), transparent), var(--bg);
      padding: 28px;
    }

    .card {
      max-width: 1100px;
      width: 100%;
      background: linear-gradient(180deg, rgba(255,255,255,0.03), rgba(255,255,255,0.02));
      border: 1px solid rgba(255,255,255,0.04);
      backdrop-filter: blur(8px);
      padding: 26px;
      border-radius: 18px;
      box-shadow: 0 8px 40px rgba(2,6,23,0.6);
    }

    .icons {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 18px;
    }

    .icons img,
    .icons svg {
      width: 50px;
      height: 50px;
      object-fit: contain;
      border-radius: 10px;
      padding: 8px;
      background: rgba(255,255,255,0.02);
      border: 1px solid rgba(255,255,255,0.04);
      transition: transform 0.25s ease, box-shadow 0.25s ease, background 0.25s ease;
    }

    .icons img:hover,
    .icons svg:hover {
      transform: translateY(-6px) scale(1.08);
      box-shadow: 0 12px 25px rgba(0,0,0,0.4);
      background: rgba(255,255,255,0.06);
    }

    @media (max-width: 600px) {
      .icons img,
      .icons svg {
        width: 40px;
        height: 40px;
        padding: 6px;
      }
    }
  </style>
</head>
<body>
  <div class="banner">
    <div class="card" role="region" aria-label="Tech Stack Icons">
      <div class="icons">
        <!-- Languages -->
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" alt="C">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg" alt="PHP">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Python">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bash/bash-original.svg" alt="Bash">

        <!-- DevOps -->
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" alt="Docker">
        <svg role="img" aria-label="AWS" viewBox="0 0 48 48" xmlns="http://www.w3.org/2000/svg">
          <rect width="48" height="48" rx="8" fill="transparent"/>
          <text x="50%" y="54%" font-family="Inter, Arial, sans-serif" font-size="13" font-weight="700" fill="#FF9900" text-anchor="middle">AWS</text>
          <path d="M8 34c8-6 32-6 36 0" stroke="#FF9900" stroke-width="3" stroke-linecap="round" fill="none"/>
        </svg>
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kubernetes/kubernetes-plain.svg" alt="Kubernetes">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" alt="Git">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" alt="GitHub">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/ansible/ansible-original.svg" alt="Ansible">
        <img src="https://avatars.githubusercontent.com/u/45487711?s=200&v=4" alt="n8n">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jenkins/jenkins-original.svg" alt="Jenkins">

        <!-- Front-End -->
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" alt="HTML5">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" alt="CSS3">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt="JavaScript">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jquery/jquery-original.svg" alt="jQuery">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bootstrap/bootstrap-original.svg" alt="Bootstrap">

        <!-- Back-End -->
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" alt="Node.js">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/express/express-original.svg" alt="Express">
        <img src="https://ejs.co/favicon.ico" alt="EJS">
        <img src="https://cdn-icons-png.flaticon.com/512/5548/5548859.png" alt="RESTful APIs">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" alt="PostgreSQL">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" alt="MySQL">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" alt="MongoDB">
        <img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" alt="Postman">

        <!-- Security / Pentest -->
        <img src="https://cdn-icons-png.flaticon.com/512/1048/1048953.png" alt="CTF">
        <svg role="img" viewBox="0 0 48 48" xmlns="http://www.w3.org/2000/svg">
          <rect width="48" height="48" rx="8" fill="#2b2f36"/>
          <text x="50%" y="60%" font-family="Inter, Arial, sans-serif" font-size="14" fill="#ffffff" text-anchor="middle">gdb</text>
        </svg>
        <img src="https://cdn-icons-png.flaticon.com/512/1006/1006363.png" alt="SIEM">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" alt="Linux">
        <img src="https://cdn.simpleicons.org/burpsuite/FF6633" alt="Burp Suite">
        <img src="https://cdn.simpleicons.org/kalilinux/2684FF" alt="Kali Linux">
        <img src="https://cdn.simpleicons.org/parrotsecurity/00E676" alt="Parrot OS">
        <img src="https://cdn.simpleicons.org/metasploit/5A5A5A" alt="Metasploit">
        <svg role="img" viewBox="0 0 48 48" xmlns="http://www.w3.org/2000/svg">
          <rect width="48" height="48" rx="8" fill="#f43f5e"/>
          <text x="50%" y="60%" font-family="Inter, Arial, sans-serif" font-size="12" fill="#ffffff" text-anchor="middle">nmap</text>
        </svg>
        <img src="https://cdn.simpleicons.org/wireshark/1679A7" alt="Wireshark">
      </div>
    </div>
  </div>
</body>
</html>
