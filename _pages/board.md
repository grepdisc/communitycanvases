---
permalink: /board/
title: "Community Canvases Board Members"
author_profile: false

---

<div class="grid">
    {% for member in site.data.board %}
        <div class="grid-item">
            <div class="panel-heading">
                 <b>{{ member.name }}</b> - {{member.role}}
                <br><br>
                {{member.bio}}<br><br>
            </div>
        </div>
    {% endfor %}
</div>

## Community Canvases Staff

**Katherine Pessecow** - Executive Director

Katherine teaches Social Studies in the Buffalo Public Schools.
With 13 years of volunteer coordination and event planning experience,
she chairs the Community Engagement Committee on the Board of the
Buffalo Maritime Center.<br><br><br>

**Hy Carrel** - Director of Operations

Hy is a social worker who has brought Faithful Fools training to Buffalo. Previously, he built
community through developing REI circles and housing unhoused neighbors at BestSelf Behavioral Health.


