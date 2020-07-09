---
layout: default
title: Projects
---
<div class="container mt-5">
    {% for project in site.data.projects %}
        <div class="card text-white bg-primary mr-4 mb-4" style="max-width: 20rem; display:inline-block;">
            <div class="card-body">
                <h4 class="card-title">{{ project.title }}</h4>
                <p class="card-text">{{ project.description }}</p>
                <hr class="my-4" style="border-color:white;">
                <div class="project-link text-right">
                    <i class="fa fa-github" aria-hidden="true"></i>
                    <a href="{{ project.link }}" target="_blank" class="text-white">View</a>
                </div>
            </div>
        </div>
    {% endfor %}
</div>
