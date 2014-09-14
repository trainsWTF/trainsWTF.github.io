---
layout: page
---
{% include JB/setup %}
![Logo]({{ site.url }}/logo.jpg)

Southeastern: 

[Customer Comments]({{ site.url }}/setrains)

[Delay Repay]({{ site.url }}/setrains_dr)

<div class="container">

	<div class="col-md-9">
	{% for post in site.posts %}
	{% assign monkey = forloop.index | modulo:4 %}
	{% case monkey %}
	{% when 1,3 %}
    	<div class="row">
        	<div class="col-md-6">
            	
					<span><a href="{{ BASE_PATH }}{{ post.url }}"><b>{{ post.title }}</b></a></span>
					<br><b> {{ post.date | date_to_string }}</b>
					<a href="https://twitter.com/share" class="twitter-share-button" data-url="http://trains.wtf{{ BASE_PATH }}{{ post.url }}" data-via="trainsWTF">Tweet</a>
					
					<br>
						{{ post.summary }}
					<br><br>
 
        	</div>
	{% when 0,2 %}
		<div class="col-md-6">
			<span><a href="{{ BASE_PATH }}{{ post.url }}"><b>{{ post.title }}</b></a></span>
			<br><b> {{ post.date | date_to_string }}</b>
			<a href="https://twitter.com/share" class="twitter-share-button" data-url="http://http://trains.wtf{{{ BASE_PATH }}{{ post.url }}" data-via="trainsWTF">Tweet</a>
			
			<br>
			{{ post.summary }}
			<br><br>   
	
        </div>

        
        </div>
        
		{% if monkey == 5 %}
			<div class="row">
			ad, yo - full width one too!?
			</div>
		{% endif %}        
	{% endcase %}
	{% endfor %}	
	
	
	{% assign monkey = site.posts | modulo:2 %}
	{% case monkey %}
	{% when 0 %}
	
		<div class="col-md-6">
		
		</div>
		</div>
	{% when 1 %}
		
	{% endcase %}
    </div>

    <div class="col-md-3">

<a class="twitter-timeline" href="https://twitter.com/TrainsWTF" data-widget-id="501443537091575808">Tweets by @TrainsWTF</a>
<script>!function(d,s,id){var js,fjs=d.getElementsByTagName(s)[0],p=/^http:/.test(d.location)?'http':'https';if(!d.getElementById(id)){js=d.createElement(s);js.id=id;js.src=p+"://platform.twitter.com/widgets.js";fjs.parentNode.insertBefore(js,fjs);}}(document,"script","twitter-wjs");</script>





    </div>
</div>


        