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

**Grant Street Clean Up May 20 10:00am** [Info](/events/cleanup20230520/){: .btn .btn--success}<br>
**WRITE ON! workshop May 11th 4:30pm and May 18th 1:00pm** [Learn More](https://kindfools.org/writeon/){: .btn .btn--info}<br>
**WNY Trash Mob's Massachusetts Ave Park Clean Up May 6** [Info](/events/cleanup20230506/){: .btn .btn--info}<br>
**Video from [Kind Fools May 3rd pitch night with Buffalo SOUP](https://kindfools.org/videos/buffalo-soup/)**<br>
See All **Past and Future** Events [All Events](/events/){: .btn .btn--info}<br>
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

