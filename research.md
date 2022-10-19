---
title: Research
permalink: /research/
---

<br>

### **Research**
We seek to do cutting-edge, high-quality, and impactful research combining theory and practice. As such, we are closely collaborating with our industrial partners including Huawei, Alibaba Group, and Ant Group to solve real-world challenging problems in an effective and scalable way.


<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=, initial-scale=1.0">
    <title>Research</title>
</head>
<style>
    * {
        padding: 0;
        margin: 0;
    }
    .shell{
        width: 100%;
        height: 80vh;
        overflow-x: hidden;
        perspective: 3px;
    }
    .shell div{
        position: relative;
        display: flex;
        justify-content: center;
        align-items: center;
        font-style: 30px;
        letter-spacing: 2px;
    }
    .image{
        transform: translateZ(-1px) scale(1.0);
        background-size: cover;
        background-repeat: no-repeat;
        position: center;
        height: 100%;
        width: 100%;
        z-index: -1;
    }
    .text{
        height: 50vh;
        background-color: #fff;
    }
    .text h1{
        color: #000;
    }
    .heading{
        z-index: -1;
        transform: translateY(-30vh) translateZ(1px);
        color: #fff;
        font-size: 30px;
    }
</style>

<body>
    <div class="shell">
        <div class="image" style="background-size: 100%; background-image: url('{{site.baseurl}}/images/research/1.png');"></div>
        <div class="heading">
            <h2>DL Copyright Protection</h2>
        </div>

        <div class="image" style="background-size: 100%; background-image: url('{{site.baseurl}}/images/research/2.png');"></div>
        <div class="heading">
            <h2>NN Repair</h2>
        </div>

        <div class="image" style="background-size: 100%; background-image: url('{{site.baseurl}}/images/research/3.png');"></div>
        <div class="heading">
            <h2>DL Robustness Testing</h2>
        </div>

        <div class="image" style="background-size: 100%; background-image: url('{{site.baseurl}}/images/research/4.png');"></div>
        <div class="heading">
            <h2>Certifiable Machine Unlearning</h2>
        </div>

        <div class="image" style="background-size: 100%; background-image: url('{{site.baseurl}}/images/research/5.png');"></div>
        <div class="heading">
            <h2>DL FairRec Testing</h2>
        </div>

        <div class="image" style="background-size: 100%; background-image: url('{{site.baseurl}}/images/research/6.png');"></div>
        <div class="heading">
            <h2>OD System testing</h2>
        </div>
    </div>
</body>

</html>


<!-- ### **AI System Analysis**

<div class="content list">
  {% for post in site.posts %}
    {% if post.categories contains 'AI_System_Analysis' %}
    <div class="list-item">
      <p class="list-post-title">
        <a href="{{ post.url | prepend: site.baseurl }}">
            <div class="row">
                <div class="col-sm-4">
                    <img src="/{% if post.header-img %}{{ post.header-img }}{% else %}{{ site.header-img }}{% endif %}">
                </div>
                <div class="col-sm-8">
                    <h3 class="post-title">
                        {{ post.title }}
                    </h3>
                    <p class="list-post-title">
                        {{ post.description}}
                    </p>
                    <p class="list-detail" >
                      {{ post.content | strip_html | truncatewords:30 }}
                    </p>
                </div>
            </div>
            <hr/>
        </a>
      </p>
    </div>
    {% endif %}
  {% endfor %}
</div>

### **Lightweight Formal Methods & Program Analysis**

<div class="content list">
  {% for post in site.posts %}
    {% if post.categories contains 'Program_Analysis' %}
    <div class="list-item">
      <p class="list-post-title">
        <a href="{{ post.url | prepend: site.baseurl }}">
            <div class="row">
                <div class="col-sm-4">
                    <img src="/{% if post.header-img %}{{ post.header-img }}{% else %}{{ site.header-img }}{% endif %}">
                </div>
                <div class="col-sm-8">
                    <h3 class="post-title">
                        {{ post.title }}
                    </h3>
                    <p class="list-post-title">
                        {{ post.description}}
                    </p>
                    <p class="list-detail" >
                      {{ post.content | strip_html | truncatewords:30 }}
                    </p>
                </div>
            </div>
            <hr/>
        </a>
      </p>
    </div>
    {% endif %}
  {% endfor %}
</div> -->