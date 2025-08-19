---
layout: default
title: About
permalink: /about/
---

<div class="about-page">
    <h1>About Me</h1>
    
    <div class="about-content">
        <p>Hello! I'm {{ site.author }}, passionate about technology, design, and innovation.</p>
        
        <p>This blog is where I share my thoughts, projects, and discoveries. I believe in the power of clean design and thoughtful technology.</p>
        
        <h2>What I Write About</h2>
        <p>You'll find posts about:</p>
        <ul>
            <li>Web development and design</li>
            <li>Technology trends</li>
            <li>Personal projects</li>
            <li>Random thoughts and ideas</li>
        </ul>
        
        <h2>Get In Touch</h2>
        <p>Feel free to reach out:</p>
        <ul>
            <li>Email: {{ site.email }}</li>
            {% if site.github_username %}<li>GitHub: <a href="https://github.com/{{ site.github_username }}">@{{ site.github_username }}</a></li>{% endif %}
            {% if site.twitter_username %}<li>Twitter: <a href="https://twitter.com/{{ site.twitter_username }}">@{{ site.twitter_username }}</a></li>{% endif %}
        </ul>
    </div>
</div>
