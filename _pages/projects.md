---
permalink: /projects/
title: "Projects"
excerpt_separator: "projects"
tags:
  - Projects
  - Django
  - AWS
  - Virtual
  - Network
  - Alura
  - Oracle
toc: true
toc_label: "My Table of Contents"
toc_icon: "cog"
---


Here are some of the projects I have worked on and completed:

{% assign sorted_posts = site.posts | sort: 'date' | reverse %}
<ul>
  {% for post in sorted_posts %}
    <li>
      <a href="{{ post.url }}" class="post-link">{{ post.title }}</a>
      <p>Published on: {{ post.date | date: "%B %d, %Y" }}</p>
    </li>
  {% endfor %}
</ul>

## [Web Application for Graph Visualization and Shortest Path Finding using Dijkstra's Algorithm](https://bash20cu.github.io/Universidad/Proyecto_Matatica_Discreta/AlgoritmoDijkstra/){:target="_blank"}
As part of my Discrete Mathematics course, I created a web project that implemented Dijkstra's algorithm. Using jQuery, I created an interactive map where the user can click to add nodes, assign weights, and create edges between them, creating a graph. The algorithm then calculates the shortest path between two selected nodes and highlights it on the map.

This project allowed me to apply my knowledge of discrete mathematics, data structures, and algorithms in a practical way. It also helped me develop my skills in web development, particularly with jQuery and JSON. Additionally, I made the project available online for other students to use, which helped me develop my skills in project management and collaboration.

## [Java Game Development](https://github.com/bash20cu/Universidad/tree/main/Estructuras_de_Datos_Algoritmos/Donkey_Kong){:target="_blank"}
As part of my coursework in data structures, I developed a video game using Java programming language. The game is a graphical adventure that incorporates elements of strategy and puzzles, and was created using the JavaFX graphics library.

During the game development process, I was able to apply my skills in object-oriented programming, software pattern design, and resource management. I also gained experience in using tools such as Eclipse and NetBeans, and in creating user interfaces by building windows and dialogs using JavaFX.

If you're interested in learning more about my Java game project, please feel free to contact me for further details.



## [Real Time Analyst and Junior Software Developer at Movate (CSSCORP)](https://github.com/miguelfernandez2022){:target="_blank"}

I have been working at CSSCORP since November 2020, where I have had the opportunity to work as a Real Time Analyst and Junior Software Developer. In my role as Real Time Analyst, I have been responsible for the development of reports in excel with macros, as well as automation with Microsoft Automate of the PTO report and approvals. I have also been in charge of the real-time analysis of the workload, as well as the behavior of the teams and call loads, managing rest times for several teams with over 150 agents. My role as Junior Software Developer has involved learning the codebase connectivity tool project using jQuery, creating web applications for Commscope/ARRIS using HTML5, CSS3 and VanillaJS, and auditing, designing, and implementing Commscope/ARRIS G34 web simulator using HTML5, CSS3, VanillaJS, and PHP. I have also collaborated on the debugging and analysis of the source code and attended design meetings with the client every week, participating in all the updates. 

## [Oracle Next Education with Alura LATAM](https://bash20cu.github.io/ONE-Alura/){:target="_blank"}

I have completed the ALURA LATAM course, which covered a wide range of frontend techniques and tools. Through this course, I gained valuable experience in HTML, CSS, JavaScript, and other popular technologies used in frontend development. I learned how to create responsive web pages, build interactive user interfaces, and optimize website performance.

This course has enabled me to take on various frontend projects and deliver high-quality work that meets the needs of clients. I am excited to apply my knowledge and skills to new projects and continue learning and growing as a frontend developer.

## Collaboration with ColmenaTech on Odoo
![image-left]({{"/assets/images/ColmenaTech.jpg"|absolute_url}}){: .align-left}
I collaborated with ColmenaTech in the implementation of AWS virtual machines with Ubuntu and the Odoo CRM for electronic invoicing in Costa Rica. This collaboration gave me a lot of knowledge of installing Linux systems and deploying and exploiting the CRM, as well as skills in reading system registers, solving connection errors, and creating virtual connections (VLAN). I also managed to deploy the container system with the collaboration of joker charlie/odoo-dkr-cr: 12.0 and learned to handle container technology and apply its principle - Same development environment - Same deployment environment.

## [Inventario PyDev win32](https://github.com/bash20cu/inventario_py_dev_0.5){:target="_blank"}

I created the Inventario PyDev app to handle the invoice system of a little store or business using Python 2.7 language and Django framework. The app is free to use and has already been deployed using Py-To-Exe. You can find more information about Inventario PyDev on 

These projects have allowed me to learn and improve my skills in different areas, from real-time analysis and customer service to web development and container technology. 
