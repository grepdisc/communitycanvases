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

[Art Show on April 8th](/events/artshow20230408/)
{: .notice--info .maxwidthbox}

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
