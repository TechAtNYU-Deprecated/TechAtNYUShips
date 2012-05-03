Tech@NYU Ships
==============
What the heck is this?
----------------------
It's a gallery of awesome stuff Tech@NYU members have done. Tech@NYU is the
"entrepreneurship club at NYU that ships" so let's show it off. It's sort of like
a one-topic site (a la [http://istheltrainfucked.com/](http://istheltrainfucked.com/)).

It is live at [http://techatnyuships.heroku.com/](http://techatnyuships.heroku.com)

![http://imgur.com/zpbwN.gif](http://imgur.com/zpbwN.gif)

How can I contribute?
--------------------- 
This repo is intended to be as simple as possible to make it easy to contribute.
No templating or markup language, no confusing servers, just a static page
of HTML and CSS that's easy to change.

To get started:

```
git clone
cd techatnyuships
gem install rack
rackup
```

Maneuver your browser-of-choice to [http://localhost:9292/](http://localhost:9292/)
(Rack's default setup) and you'll see the site!

If you've never used git before, you'll need to learn, so here's a guide:
[Simple Guide to Git](http://rogerdudler.github.com/git-guide/)

Style guide
------------
An example project is below. Your project should generally conform to this one,
use the same styles, etc.

```html
<hr class="divider">
<div class="project">
	<div class="description">
		<h2>Project Name</h2>
		<h3>Techa@NYU member's names<i class="alumni"></i></h3>
		<p>
			One sentence description. Followed by a longer, in depth description that
			is 300 characters or less.
		</p>
		<p>
			<a class="live_link" href="linktoyourproject.com">http://linktoyourproject.com</a>
		</p>
	</div>
	<div class="image">
		<img src="/img/imageyouadded.jpg" />
	</div>
</div>
```

* Project description should be 300 chars or less
* You MUST have a project image (but it can be anything) and it should be 380 by 260 px.
* Save the earth and keep load times down by keeping your image to 30kb or less.

What goes on the list?
----------------------
(These rules are open to debate and change, but for now they are:)
* One project per Tech@NYU member (i.e., post your best one, not all of them)
* "Shipped" means available for public consumption. If it's a library, that means posting to GitHub, if it's a product, that means having the product in a live public beta, etc. No private stuff/launchrock pages count as "shipped".
* There is no project too small or too large, as long as it's shipped.
* Alumni projects are OK, but should follow all the other rules as well. Put an alumni tag next to alumni names.