---
layout: page
title: Assessment Repository
---

The following assessments have been submitted by study participants. Participants have given the researchers permission to share these assessments under a [Creative Commons Public Domain License (CC0 1.0)](https://creativecommons.org/publicdomain/zero/1.0/){:target="_blank"}.
<p>Click on an assessment's title to view its contents in full, or click "Download" to view and download the originally submitted document.</p>

<div class="resource-list">
        <ul>
        {% for assessment in site.assessments %}
            <li>
                <div class="title"><a href="{{ assessment.url }}">{{ assessment.title }}</a></div>
                <div class="author">{{ assessment.author}}</div>
                <div class="download"><a href="/downloads/{{ assessment.download }}">Download</a></div>
            </li>
        {% endfor %}
            <!-- Repeat the above <li> block for each resource -->
        </ul>
    </div>
