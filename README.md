

## Hello, I am Santy!

I began my career in India and my work allowed me to experience living in New Zealand, Australia and now the USA.  

I am an interested in software architecture, programming and hacking - hardware, electronics and espresso machines. I am an avid HAM Radio operator (KF5KGI). 

My current interests include machine learning, blockchain and security.

I am a minimalist and spend quite a lot of energy balancing simplicity and functionality. 

## Contact 

<div class="col-xs-4">
            <div class="team-member wow zoomIn">
                <img src="{{ site.author.avatar | prepend: site.baseurl }}" height="110" width="110" class="img-responsive img-circle" alt="">
                <h4><span class="navy">{{ site.author.first_name }}</span> {{ site.author.last_name }}</h4>
                <ul class="list-inline social-icon">
                    {% if site.author.github_username %}
                    <li><a href="https://github.com/{{ site.author.github_username }}" target="blank"><i class="fa fa-github"></i></a></li>
                    {% endif %}
                    {% if site.author.linkedin_id %}
                    <li><a href="https://www.linkedin.com/in/{{ site.author.linkedin_id }}" target="blank"><i class="fa fa-linkedin"></i></a></li>
                    {% endif %}
                    {% if site.author.facebook_username %}
                    <li><a href="https://www.facebook.com/{{ site.author.facebook_username }}" target="blank"><i class="fa fa-facebook"></i></a></li>
                    {% endif %}
                    {% if site.author.twitter_username %}
                    <li><a href="https://twitter.com/{{ site.author.twitter_username }}" target="blank"><i class="fa fa-twitter"></i></a></li>
                    {% endif %}
                    {% if site.author.email %}
                    <li><a href="mailto:{{ site.author.email }}"><i class="fa fa-envelope-o"></i></a></li>
                    {% endif %}
                    <li><a href="{{ site.baseurl }}/feed.xml" target="blank"><i class="fa fa-rss"></i></a></li>
                    {% if site.author.cv %}
                    <li><a href="{{ site.author.cv }}" target="blank"><i class="fa fa-file-pdf-o"></i></a></li>
                    {% endif %}
                </ul>
            </div>
        </div>
### About this Site

This site is built in GitHub Pages and Jekyll. I used the Cayman theme from Jekyll.
{% include skills.html %}
