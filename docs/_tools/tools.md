---
layout: default
title: Tools for Cooking Prime Rib
---

<div class="row mt-5">
    <div class="frosted-glass">
        <h2 class="mb-3">{{ page.title }}</h2>
        <div class="row">
            {% for tool in page.tools %}
            <div class="col-md-4 mb-3">
                <div class="card">
                    <img src="{{ tool.image }}" class="card-img-top" alt="{{ tool.alt }}">
                    <div class="card-body">
                        <h5 class="card-title">
                            <a target="_blank" href="{{ tool.link }}">{{ tool.title }}</a>
                        </h5>
                        <p class="card-text">{{ tool.description }}</p>
                    </div>
                </div>
            </div>
            {% endfor %}
        </div>
    </div>
</div>

