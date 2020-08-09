---
layout: default
title: Blog
permalink: /blog/
---


<div class="container">
	<br>
	<div class="row">
		<div class="col col-12">
			<div class="container__inner">
				<div class="contaniner__inner-box">
					<div class="row grid">
					{{site.posts.size}}
					{{paginator.posts.size}}
						{% if site.posts.size > 0 %}
						{% for post in paginator.posts %}
						{% include article-content.html %}
						{% endfor %}
						{% endif %}
					</div>
				</div>
			</div>
		</div>
	</div>
</div>

{% include pagination.html %}