---
layout: splash
permalink: /
header:
  #overlay_color: "#5e616c"
  overlay_image: /assets/images/CommunityCanvasesHeader.jpg
  #caption: Community Canvases project with artists Chuck Tingley and Edreys Wajed
excerpt: "facilitating community engagement through the arts"

---

# Upcoming Events
{: .text-center}

**WRITE ON! workshop May 2nd 6pm** [Learn More](https://kindfools.org/writeon/){: .btn .btn--info}<br>
**Kind Fools May 3rd 6pm pitch night with [Buffalo SOUP](https://www.instagram.com/buffalonysoup/)**<br>
**Massachusetts Ave Park Clean Up May 6 10:45am** [Info](/events/cleanup20230506/){: .btn .btn--success}<br>
**Grant Street Clean Up May 20 10:00am** - more details very soon<br>
**Earth Day Clean Up** [Info](/earthday2023/){: .btn .btn--success}<br>
{: .notice--info .maxwidthbox .align-center}

# Projects
{: .text-center}

<div class="grid">
    {% for project in site.data.projects %}
        <div class="grid-item">
            <a alt="{{ project.name }}" href="{{ project.link }}" title="{{ project.name }}">
                <div class="panel panel-default">
                    <div class="panel-heading">
                        {{ project.name }}
                    </div>
                    <div class="panel-body" style="background: url('{{ project.image }}') no-repeat; background-size: cover; min-height: 200px;"></div>
                </div>
            </a>
        </div>
    {% endfor %}
</div>

# We are gathering art supplies... to build this into a beautiful website. Please check back soon
{: .text-center}

Contact us: [team@communitycanvases.org](mailto:team@communitycanvases.org)

