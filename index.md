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


**WRITE ON! workshop on August 8** [Learn More](
    https://kindfools.org/writeon/){: .btn .btn--info}<br>
Community Swing 6pm to 9pm every Wednesday [Details](
    /communityswing){: .btn .btn--info}<br>
Calendar of [**All Events**](
    /events/){: .btn .btn--info}<br>
{: .notice--info .maxwidthbox .align-center}

{% comment %}
**Write-up of May 20th WNY Trash Mob Cleanup** [Photos](https://www.instagram.com/p/CsjYMIIO8PR/){: .btn .btn--info}<br>
**Remembering Claire** [Video](https://kindfools.org/videos/let-them-be/){: .btn .btn--info}<br>
**Collaborative Community Art** [SIGN UP July 2023](/events/communityartsummer2023/){: .btn .btn--success .btn--large}<br>
{: .notice--success .maxwidthbox .align-center}
{% endcomment %}

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

