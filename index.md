---
layout: splash
permalink: /
header:
  #overlay_color: "#5e616c"
  overlay_image: /assets/images/CommunityCanvasesHeader.jpg
  #caption: Community Canvases project with artists Chuck Tingley and Edreys Wajed
excerpt: "facilitating community engagement and expression through the arts"

---

# Upcoming Events
{: .text-center}

**WNY Trash Mob's Earth Day Clean Up Challenge 2024** [All the Details](
    /earthday2024/){: .btn .btn--large .btn--success}<br>
All Groups, **please complete WNY Trash Mob** [Data Form](https://forms.gle/i1CR68pJMt4kfzue9
   ){: .btn .btn--success}<br>
Community Swing 6pm to 9pm every Wednesday [Details](
    https://www.facebook.com/communityswing){: .btn .btn--info}<br>
Signal Box Art Project [Info/Application](
    /signalboxes/northbuffalo/){: .btn .btn--info}<br>
**"Heavy" Reflections** part of the Civil Writes Project
   [Info](https://kindfools.org/heavyreflections/){: .btn .btn--info}<br>
WNY Trash Mob's **Advisory Board Interest Form** [Details](
    https://docs.google.com/forms/d/e/1FAIpQLSdEl97wl8-2h3utgQFutv624b2_dMh0bYoFICap5twcbq7ZXw/viewform?usp=sf_link   
){: .btn .btn--info}<br>

Calendar of [**All Events**](
    /events/){: .btn .btn--info}<br>

{% comment %}
WRITE ON! 6pm April 9th on Zoom [Info/Sign-up](
    https://kindfools.org/writeon/){: .btn .btn--info}<br>
**Community Swing** at 6pm on Jan 31st (live band) [Details](
    https://www.facebook.com/communityswing
    ){: .btn .btn--info}<br>
Thank you for attending our Art Show at Hostel Buffalo [Details](
    /events/artshow20231111/){: .btn .btn--info}<br>
[Art Survey](
https://docs.google.com/forms/d/e/1FAIpQLSfaCyszcBCM1RKUOpB4O_wfKkR5dA8_oXpwG9IQlASn7kwXgQ/viewform
){: .btn .btn--success} [Data Collection](
https://docs.google.com/forms/d/e/1FAIpQLSe_z314Lh2i1LRe87zYxUFVd2iWS8pYDOx-iyihX5yIL8qbcw/viewform
){: .btn .btn--warning}
{% endcomment %}

{% comment %}
{: .notice--info .maxwidthbox .align-center}
**TONIGHT: Pumpkin Carving and Film Party/Fundraiser Oct 13th** [Tickets](
    https://www.chateaubuffalo.com/suite-16-cinema-series
    ){: .btn .btn--success}<br>
Can't attend but still want to support Community Canvases? [Donate](/donate/
    ){: .btn .btn--success}<br>
{: .notice--success .maxwidthbox .align-center}

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

Contact us: [team@communitycanvases.org](mailto:team@communitycanvases.org)

