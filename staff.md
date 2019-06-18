---
layout: default
title: "관리자 목록"
---

<section class="banner">
    <div class="container">
        <div class="content">
            <h1 class="title">{{ page.title }}</h1>
        </div>
    </div>
</section>
<section class="content">
    <div class="container">
        <div class="row">
            <div class="col-md-12">
                <h2>Administrators <small>{{ site.data.staff.administrators | size }}</small></h2>
                <hr>
            </div>
        </div>
        <div class="row">
            {% for staff in site.data.staff.administrators %}
            <div class="col-sm-6 col-md-3">
                <div class="staff-entry">
                    <img width="90" height="90" class="avatar"
                        src="https://api.ashcon.app/mojang/v2/avatar/{{ staff.name }}">
                    <h3>{{ staff.name }}</h3>
                    <p>{{ staff.role }}</p>
                </div>
            </div>
            {% endfor %}
        </div>
        <div class="row">
            <div class="col-md-12">
                <h2>Advisors <small>{{ site.data.staff.advisors | size }}</small></h2>
                <hr>
            </div>
        </div>
        <div class="row">
            {% for staff in site.data.staff.advisors %}
            <div class="col-sm-6 col-md-3">
                <div class="staff-entry">
                    <img width="90" height="90" class="avatar"
                        src="https://api.ashcon.app/mojang/v2/avatar/{{ staff.name }}">
                    <h3>{{ staff.name }}</h3>
                    <p>{{ staff.role }}</p>
                </div>
            </div>
            {% endfor %}
        </div>
    </div>
</section>