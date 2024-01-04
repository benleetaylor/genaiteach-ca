---
layout: page
title: Assessment Repository
share-title: AI Assessment Repository | Open Educational Resources (OER) 
share-description: Sample assessments collected from instructors that incorporate or respond to generative AI (e.g., ChatGPT).  
---

The following assessments have been submitted by study participants. Participants have given the researchers permission to share these assessments under a [Creative Commons Public Domain License (CC0 1.0)](https://creativecommons.org/publicdomain/zero/1.0/){:target="_blank"}.
<p>Click on an assessment's title to view its contents in full, or click "Download" to view and download the originally submitted document.</p>

<div class="resource-list">
        <div class="list-header">
				<div class="title">Title</div>
				<div class="author">Author</div>
				<div class="download">Download</div>
			</div>
		<ul>
        {% assign assessments = site.assessments | sort: "author-surname" %}
        {% for assessment in assessments %}
            <li>
                <div class="title"><a href="{{ assessment.url }}">{{ assessment.short-title }}</a></div>
                <div class="author">{{ assessment.author }}</div>
                <div class="download"><a href="/downloads/{{ assessment.download }}">Download</a></div>
            </li>
        {% endfor %}
        </ul>
    </div>
