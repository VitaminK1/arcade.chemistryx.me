---
layout: default
title: 가이드
---

<section class="banner">
    <div class="container">
        <div class="content">
            <h1 class="title">{{ page.title }}</h1>
        </div>
    </div>
</section>
<!-- <section class="info">
    <div class="alert alert-warning">
        <div class="container">
            <p><span class="badge badge-default">참고</span> 아직 문서가 완성되지 않았습니다.</p>
        </div>
    </div>
</section> -->
<section class="content">
    <div class="container">
        <h2>일반 가이드</h2>
        <div class="row">
            {% for general in site.data.general %}
            <div class="col-sm-6 col-lg-3">
                <div id="{{ general.slug }}" class="thumbnail thumbnail-guide">
                    <div class="guide-image guide-image-default">
                        <div class="guide-banner">
                            <a href="general/{{ general.slug }}" class="guide-name"><strong>{{ general.name }}</strong></a>
                            <span class="guide-desc">{{ general.desc }}</span>
                        </div>
                    </div>
                </div>
            </div>
            {% endfor %}
        </div>
        <h2>게임모드 가이드</h2>
        <div class="row">
            {% for game in site.data.games %}
            <div class="col-sm-6 col-lg-3">
                <div id="{{ game.slug }}" class="thumbnail thumbnail-guide">
                    <div class="guide-image" style="background-image:url('../resources/images/games/{{ game.slug }}.png');">
                        <div class="guide-banner">
                            <a href="games/{{ game.slug }}" class="guide-name"><strong>{{ game.name }}</strong></a>
                            <span class="guide-desc">{{ game.desc }}</span>
                        </div>
                    </div>
                </div>
            </div>
            {% endfor %}
        </div>
    </div>
</section>