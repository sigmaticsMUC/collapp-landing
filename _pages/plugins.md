---
layout: page
title: Plugins
include_in_header: false
include_in_footer: false
---
# Plugins
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

<br>

## Available
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

<div class="features">


<br>

    {% for feature in site.collappextensions %}

    {% if feature.title %}
    <div class="feature">
        <div>
            <span class="fa-stack fa-1x">
                <i class="iconBack fas fa-circle fa-stack-2x"></i>
                <i class="iconTop fas fa-bolt fa-stack-1x"></i>
            </span>
        </div>
        <div class="featureText">
            <h3>
                {{ feature.title }}
            </h3>
            <p>
                {{ feature.description }}
            </p>
        </div>
    </div>
    {% endif %}

    {% endfor %}

</div>
