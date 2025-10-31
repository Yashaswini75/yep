# yep
yep
-------------python------------------
FROM python:3.9-slim
WORKDIR /app
COPY . /app
CMD ["python", "app.py"]
PS D:\sample> python app.py
Hello, World!
This is a sample Python application.
PS D:\sample> docker build -t p1 .
PS D:\sample> docker run --name myapp p1
Hello, World!
This is a sample Python application.
PS D:\sample> docker tag sha256:6f4dcf32c22aedd722d730314abcfeb9c098ea78bffb9629b581e6dcd5374100 yashaswini75
PS D:\sample> docker push docker.io/yashaswini75
---------------------------------------------------------------
PS D:\sample> docker tag p1 yashaswini75/p1:latest      
PS D:\sample> docker push yashaswini75/p1:latest

-----------------------------------------------------------------------------------

PS C:\\Users\\VVCE\\Desktop\\docker image&gt; javac sample.java----THIS WILL SAMPLE.CLASS BY DEFAULT 
PS C: \\Users\\VVCE\\Desktop\\docker image&gt; java sample
Test
PS C:\\Users\\VVCE\\Desktop\\docker image&gt; docker build -t javasample
FROM openjdk
WORKDIR /app
COPY. /app
RUN javac sample.java
CMD ["java", "sample"]
----------------------------------------------------------------------------------

FROM gcc:latest
WORKDIR /app
COPY . /app
RUN gcc sample.c -o sample
CMD ["./sample"\]
gcc sample.c -o sample
./sample
------------------------------------------
<!doctype html>

<html lang="en">

<head>

  <meta charset="utf-8">

  <meta name="viewport" content="width=device-width,initial-scale=1">

  <title>Small Profile</title>

  <style>

    body{font-family:Arial,Helvetica,sans-serif;background:#f6f8fb;color:#0b1220;display:flex;align-items:center;justify-content:center;height:100vh;margin:0}

    .card{background:white;padding:18px;border-radius:10px;box-shadow:0 6px 18px rgba(11,18,32,0.08);width:320px;text-align:center}

    .avatar{width:84px;height:84px;border-radius:50%;background:#7c3aed;color:white;display:inline-flex;align-items:center;justify-content:center;font-weight:700;font-size:28px;margin-bottom:12px}

    h1{font-size:18px;margin:6px 0}

    p.role{margin:0;color:#6b7280;font-size:13px}

    p.bio{font-size:14px;color:#374151;margin:12px 0}

    .contact{font-size:13px;color:#111827}

    .btn{display:inline-block;margin-top:10px;padding:8px 12px;border-radius:8px;background:#06b6d4;color:white;text-decoration:none}

  </style>

</head>

<body>

  <div class="card">

    <div class="avatar">PR</div>

    <h1>Priyanka R.</h1>

    <p class="role">Software Engineer</p>

    <p class="bio">I build web services and containerized applications. I enjoy automating workflows and learning new tools.</p>

    <div class="contact">shivani@example.com • +917686987907</div>

    <a class="btn" href="#">Connect</a>

  </div>

</body>

</html>
--------------------------------------------------------------------------
1) Create two file index.html,Dockerfile
2) In index.html ,sample code,In Dockerfile,FROM httpd:latestCOPY index.html /usr/local/apache2/htdocs/
3) docker login -u vvce23cse0002@vvce.ac.in
4) docker build -t image_name .( docker build -t a3 .)
5) docker run -d --name cointainer_name -p port_number image_name (docker run -d --name aa3 -p 8081:81 a3 ) B2.
6) bocker tag image_id user_name/image_name(bocker tag sha256:166c4f613107b5beb6c3d8ddeab4c17f1a2a9efb24ad2db4a9bb9412f06c7e3b ashmitaumesh/a3)
7) docker push docke.io/ user_name/image_name (docker push docke.io/ashmitaumesh/a3 )
--------------------------------------------------------------------------------------------
FROM php:8.2-apache
WORKDIR /var/www/html
COPY . /var/www/html/
EXPOSE 80

http://localhost:8080
-----------------------------------------------------------------------------------------------------

git init
git config --global user.name '"
git status
git add .
git commit -m ''
git mv hello.txt hey.txt
mkdir src
git mv hello.txt src/
git log
git log --oneline
git rest --soft head~1
mixed hard
git stash
git stash list
git stash pop

reviewer ses collabotors add people 
protection ses branches add classic protection rule 

.





