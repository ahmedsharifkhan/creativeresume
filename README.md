<!DOCTYPE html>
<html lang="en">
<head>
	<title>Cvio - CV Resume & Personal Portfolio Jekyll Theme</title>
	<meta charset="utf-8" />
	<link rel="stylesheet" href="assets/style.css">
	<link rel="stylesheet" href="assets/table.css">
</head>
<body>
	<header class="dt-header dt-header_blue">
		<span class="dt-logo">Cvio v.1.0 - CV Resume & Personal Portfolio Jekyll Theme</span>
		<span class="dt-demo">
			<a href="https://cvio-jekyll.netlify.app" target="_blank">Visit Demo</a>
		</span>
	</header>	
	<div class="dt-container dt-container_flex">
		<aside class="dt-navbar">
			<nav class="dt-navbar__nav">
				<div class="dt-navbar__section">
					<ul class="dt-navbar__list">
						<li><a href="#installation" class="dt-navbar__link">Installation</a></li>
						<li><a href="#basic" class="dt-navbar__link">Basic Configurations</a></li>
						<li><a href="#home" class="dt-navbar__link">Home Configurations</a></li>
						<li><a href="#footer" class="dt-navbar__link">Footer Configurations</a></li>
						<li><a href="#navigation" class="dt-navbar__link">Navigation Configurations</a></li>
						<li><a href="#content" class="dt-navbar__link">Content Configurations</a></li>
						<li><a href="#posts" class="dt-navbar__link">Posts</a></li>
						<li><a href="#pages" class="dt-navbar__link">Pages</a></li>
						<li><a href="#projects" class="dt-navbar__link">Projects</a></li>
						<li><a href="#colors" class="dt-navbar__link">Color Schemes</a></li>
						<li><a href="#preloader" class="dt-navbar__link">Preloader</a></li>
						<li><a href="#contacts" class="dt-navbar__link">Contact Form</a></li>
						<li><a href="#disqus" class="dt-navbar__link">Disqus Comments</a></li>
						<li><a href="#styles" class="dt-navbar__link">Style Customization</a></li>
						<li><a href="#translation" class="dt-navbar__link">Translation</a></li>
						<li><a href="#netlify" class="dt-navbar__link">Netlify</a></li>
						<li><a href="#icons" class="dt-navbar__link">Icons</a></li>
						<li><a href="#credits" class="dt-navbar__link">Credits</a></li>
					</ul>
				</div>		
			</nav>
		</aside>	
		<div class="dt-content dt-content_scroll-bar-yes">
			<div class="dt-section">
				<h2 class="dt-title">Cvio - CV Resume & Personal Portfolio Jekyll Theme</h2>
				<p>Author: <a href="https://themeforest.net/user/beshleyua" target="_blank">ThemeForest Profile</a> | 
				<a href="https://cvio-jekyll.netlify.app/" target="_blank">Demo</a> | <a href="https://bslthemes.site" target="_blank">Website</a> | <a href="mailto:beshleyua@gmail.com">Contact with me</a></p>
			</div>
			<article id="installation" class="dt-section">
				<h2 class="dt-title">Installation</h2>
				<p>1. First, unzip main file, copy all files from /theme/ folder to your work dir.</p>
				<p>2. To run the theme locally, navigate to the theme directory and install all the dependencies with <a href="http://bundler.io/" target="_blank">Bundler</a>:</p>
				<div class="dt-info-block">
					<pre class="code language-html">
						<code>
bundle install
						</code>
					</pre>
				</div>
				<p>3. Then run the following command to start the Jekyll server</p>
				<div class="dt-info-block">
					<pre class="code language-html">
						<code>
bundle exec jekyll serve
						</code>
					</pre>
				</div>
				<p>4. Browse to <a href="http://localhost:4000" target="_blank">http://localhost:4000</a></p>
				<p>You can find more on <a href="https://jekyllrb.com/docs/deployment-methods/" target="_blank">Deployment Methods</a> page on Jekyll Website.</p>
			</article>
			
			<article id="basic" class="dt-section">
				<h2 class="dt-title">Basic Configurations</h2>
				<p>
					Basic site options you can edit in <code>_config.yml</code> file:
				</p>
				<div class="dt-info-block">
					<pre class="code language-yaml">
						<code>
# basic settings
title: "Cvio - Resume / CV Jekyll Theme"
email: "your-email@example.com"
description: "Jekyll Resume / CV / vCard / Portfolio template"
author: "Admin"
baseurl: "" # the subpath of your site, e.g. /blog
url: "" # the base hostname & protocol for your site, e.g. http://example.com
date_format: "%d %B %Y"

# paginations & permalinks
paginate: 9
paginate_path: "/blog/page:num/"
permalink: pretty
						</code>
					</pre>
				</div>						
			</article>
			<article id="home" class="dt-section">
				<h2 class="dt-title">Home Configurations</h2>
				<p>
					To configure home page go to <code>_data/home.yml</code> file:
				</p>
				<div class="dt-info-block">
					<pre class="code language-yaml">
						<code>
started:
  title: "I'm John Doe"
  typed:
    - "UX/UI Designer and Front-end Director."
    - "Based in Kiev."
						</code>
					</pre>
				</div>
				<ul class="dt-list dt-list_nested">
					<li><strong>"title"</strong> - Title</li>
					<li><strong>"typed"</strong> - Typed text under Name</li>
				</ul>
			</article>
			<article id="footer" class="dt-section">
				<h2 class="dt-title">Footer Configurations</h2>
				<p>
					To configure footer go to <code>_data/footer.yml</code> file:
				</p>
				<div class="dt-info-block">
					<pre class="code language-yaml">
						<code>
main:
  social:
    - title: "Dribbble"
      icon: "social-dribbble"
      url: "https://dribbble.com/"
    - title: "Twitter"
      icon: "social-twitter"
      url: "https://twitter.com/"
    - title: "GitHub"
      icon: "social-github"
      url: "https://github.com/"
    - title: "Instagram"
      icon: "social-instagram-outline"
      url: "https://instagram.com/"
  copy: "© 2020 Cvio. All rights reserved."
						</code>
					</pre>
				</div>
				<ul class="dt-list dt-list_nested">
					<li><strong>"social"</strong> - Social Links (Title, URL, Icon Class), icon class name you can find <a href="https://ionicons.com/v2/" target="_blank">here</a></li>
					<li><strong>"copy"</strong> - Copyright Text</li>
				</ul>
			</article>
			<article id="navigation" class="dt-section">
				<h2 class="dt-title">Navigation Configurations</h2>
				<p>
					To configure site navigation left panel go to <code>_data/navigation.yml</code> file:
				</p>
				<div class="dt-info-block">
					<pre class="code language-yaml">
						<code>
...

main:
  # Home
  - title: "Home"
    url: "/"
    button: 0
    
  # Resume
  - title: "Resume"
    url: "resume/"
    button: 0

...
						</code>
					</pre>
				</div>
				<p>Each menu item are linked with header menu. To add new menu item use this code:</p>
				<div class="dt-info-block">
					<pre class="code language-yaml">
						<code>
  - title: "Resume"
    url: "resume/"
    button: 0
						</code>
					</pre>
				</div>
				<ul class="dt-list dt-list_nested">
					<li><strong>"title"</strong> - Menu item name</li>
					<li><strong>"url"</strong> - Menu item url</li>
					<li><strong>"button"</strong> - Menu item style. if "1" button style was activated for menu item.</li>
				</ul>				
			</article>
			<article id="content" class="dt-section">
				<h2 class="dt-title">Content Configurations</h2>
				<p>
					All content of all pre-built sections you can edit in <code>_data/content.yml</code> file.
				</p>
				<p>All pre-built sections name:</p>
				<div class="dt-info-block">
					<pre class="code language-yaml">
						<code>
- about
- resume
- skills
- services
- clients
- contacts-info
- contacts-form
						</code>
					</pre>
				</div>
			</article>
			<article id="posts" class="dt-section">
				<h2 class="dt-title">Posts</h2>
				<p>
					To create a new post, you can create a new markdown file inside the <code>/_posts/</code> directory by following the recommended file naming format:
				</p>
				<div class="dt-info-block">
					<pre class="code language-yaml">
						<code>
YEAR-MONTH-DAY-title.MARKUP
						</code>
					</pre>
				</div>
				<p>
					Where <code>YEAR</code> is a four-digit number, <code>MONTH</code> and <code>DAY</code> are both two-digit numbers, and <code>MARKUP</code> is the file extension representing the format used in the file. For example, the following are examples of valid post filenames:
				</p>
				<div class="dt-info-block">
					<pre class="code language-yaml">
						<code>
2011-12-31-new-years-eve-is-awesome.md
2012-09-12-how-to-write-a-blog.md
						</code>
					</pre>
				</div>
				<p>
					All blog post files must begin with front matter which is typically used to set a layout or other meta data betwenn "---" and "---"". After will be rendered with Markdown and show up as “Content”.
				</p>
				<p>
					For example standart post file structure:
				</p>
				<div class="dt-info-block">
					<pre class="code language-yaml">
						<code>
---
layout: post
title:  "By spite about what to do"
date:   2020-06-15
category: Design
image: assets/img/blog/blog1.jpg
author: Ryan Adlard
tags: jekyll
---

So striking at of to welcomed resolved. Northward by described up household therefore attention. Excellence decisively nay man yet impression for contrasted remarkably.
						</code>
					</pre>
				</div>
				<p>To create a draft post, create the post file under the <code>/_drafts/</code> directory, and you can find more information at <a href="http://jekyllrb.com/docs/drafts/" target="_blank">Working with Drafts</a>.</p>
			</article>
			<article id="pages" class="dt-section">
				<h2 class="dt-title">Pages</h2>
				<p>
					To create a new pages, you need create a new markdown file inside the your work directory.
				</p>
				<p>
					All pages files must begin with front matter which is typically used to set a layout or other meta data betwenn "---" and "---"". Text after will be rendered with Markdown and show up as “Content”.
				</p>
				<p>
					For example standart page file structure:
				</p>
				<div class="dt-info-block">
					<pre class="code language-yaml">
						<code>
---
layout: page
title: About
---

So striking at of to welcomed resolved. Northward by described up household therefore attention. Excellence decisively nay man yet impression for contrasted remarkably.
						</code>
					</pre>
				</div>
			</article>
			<article id="projects" class="dt-section">
				<h2 class="dt-title">Projects</h2>
				<p>
					To create a new project, you need create a new markdown file inside the <code>/_works/</code>.
				</p>
				<p>
					All projects files must begin with front matter which is typically used to set a layout or other meta data betwenn "---" and "---"". Text after will be rendered with Markdown and show up as “Content”.
				</p>
				<p>
					For example standart project (photo type) file structure:
				</p>
				<div class="dt-info-block">
					<pre class="code language-yaml">
						<code>
---
title: Gereal Travels
category: Photo
category_slug: f-photo
type: image
image: assets/img/works/work5.jpg
---
						</code>
					</pre>
				</div>
				<ul class="dt-list dt-list_nested">
					<li><strong>"title"</strong> - Project Name</li>
					<li><strong>"category"</strong> - Project Category Name</li>
					<li><strong>"category_slug"</strong> - Project Category Slug (must be same as in filters and use only latin characters)</li>
					<li><strong>"type"</strong> - Project Popup Type: image, gallery, video, music, content, link</li>
					<li><strong>"image"</strong> - Project Preview Image</li>
				</ul>
				<p>
					For example standart project (video type) file structure:
				</p>
				<div class="dt-info-block">
					<pre class="code language-yaml">
						<code>
---
title: Architecture
category: Video
category_slug: f-video
type: video
image: assets/img/works/work6.jpg
video: https://vimeo.com/97102654
---
						</code>
					</pre>
				</div>
				<ul class="dt-list dt-list_nested">
					<li><strong>"title"</strong> - Project Name</li>
					<li><strong>"category"</strong> - Project Category Name</li>
					<li><strong>"category_slug"</strong> - Project Category Slug (must be same as in filters and use only latin characters)</li>
					<li><strong>"type"</strong> - Project Popup Type: image, gallery, video, music, content, link</li>
					<li><strong>"image"</strong> - Project Preview Image</li>
					<li><strong>"video"</strong> - Project Video URL, Youtube or Vimeo</li>
				</ul>
				<p>
					For example standart project (music type) file structure:
				</p>
				<div class="dt-info-block">
					<pre class="code language-yaml">
						<code>
---
title: Daylight Entrance
category: Music
category_slug: f-music
type: music
image: assets/img/works/work8.jpg
music: https://w.soundcloud.com/player/?visual=true&url=http%3A%2F%2Fapi.soundcloud.com%2Ftracks%2F221650664&show_artwork=true
---
						</code>
					</pre>
				</div>
				<ul class="dt-list dt-list_nested">
					<li><strong>"title"</strong> - Project Name</li>
					<li><strong>"category"</strong> - Project Category Name</li>
					<li><strong>"category_slug"</strong> - Project Category Slug (must be same as in filters and use only latin characters)</li>
					<li><strong>"type"</strong> - Project Popup Type: image, gallery, video, music, content, link</li>
					<li><strong>"image"</strong> - Project Preview Image</li>
					<li><strong>"music"</strong> - Project Soundcloud Link</li>
				</ul>
				<p>
					For example standart project (content type) file structure:
				</p>
				<div class="dt-info-block">
					<pre class="code language-yaml">
						<code>
---
title: Mobile Application
category: Content
category_slug: f-content
type: content
image: assets/img/works/work4.jpg
button_url: https://bslthemes.com/
---

So striking at of to welcomed resolved. Northward by described up household therefore attention. Excellence decisively nay man yet impression for contrasted remarkably.
						</code>
					</pre>
				</div>
				<ul class="dt-list dt-list_nested">
					<li><strong>"title"</strong> - Project Name</li>
					<li><strong>"category"</strong> - Project Category Name</li>
					<li><strong>"category_slug"</strong> - Project Category Slug (must be same as in filters and use only latin characters)</li>
					<li><strong>"type"</strong> - Project Popup Type: image, gallery, video, music, content, link</li>
					<li><strong>"image"</strong> - Project Preview Image</li>
					<li><strong>"button_url"</strong> - Project Button URL</li>
				</ul>
			</article>
			<article id="colors" class="dt-section">
				<h2 class="dt-title">Colors Schemes</h2>
				<p>Just add "green" (or "blue", "orange", "red", "pink", "purple") for <code>quick_colors</code> option in the <code>/_data/settings.yml</code> file:</p>
				<div class="dt-info-block">
					<pre class="code language-yaml">
						<code>
settings:
  quick_colors: "blue" # select quick color schemes: "blue", "green", "orange", "pink", "purple", "red". If empty colors taken from _sass/cvio/settings.scss
  dark_ui: 0 # activated dark ui styles
  rtl: 0 # activated rtl styles
  sidebar: 1 # for disable sidebar and sidebar button change to 0
  preloader: "loading..." # preloader loading text
						</code>
					</pre>
				</div>
			</article>
			<article id="preloader" class="dt-section">
				<h2 class="dt-title">Preloader</h2>
				<p>If you want change preloader text, go to <code>preloader</code> option in the <code>/_data/settings.yml</code> file:</p>
                <div class="dt-info-block">
	                <pre class="code language-yaml">
						<code>
settings:
  quick_colors: "" # select quick color schemes: "blue", "green", "orange", "pink", "purple", "red". If empty colors taken from _sass/cvio/settings.scss
  dark_ui: 0 # activated dark ui styles
  rtl: 0 # activated rtl styles
  sidebar: 1 # for disable sidebar and sidebar button change to 0
  preloader: "your text here..." # preloader loading text
						</code>
					</pre>
				</div>
			</article>
			<article id="contacts" class="dt-section">
				<h2 class="dt-title">Contact Form</h2>
				<p>To configure form submission you need confirm you email ( where you want get submissions ) on site <a href="https://formsubmit.io/dashboard/" target="_blank">formsubmit.io</a>. After, change option <code>formsubmit_email</code> in <code>/_config.yml</code> file:</p>				
				<div class="dt-info-block">
					<pre class="code language-yaml">
						<code>
# formsubmit.io
formsubmit_email: "beshleyweb@gmail.com" # sign up on https://formsubmit.io/ and confirm your email
						</code>
					</pre>
				</div>
			</article>
			<article id="disqus" class="dt-section">
				<h2 class="dt-title">Disqus Comments</h2>
				<p>You can configure Disqus Comments options in <code>/_config.yml</code> file:</p>
				<div class="dt-info-block">
					<pre class="code language-yaml">
						<code>
# disqus comments
disqus_comments: "yes" # yes - show disqus comments, no - hide disqus comments
disqus_shortname: "glitche-jekyll-theme" # read more here https://help.disqus.com/customer/portal/articles/466208-what-s-a-shortname-
						</code>
					</pre>
				</div>
				<p>You can find out more about Disqus’ shortnames <a href="https://help.disqus.com/customer/portal/articles/466208-what-s-a-shortname-" target="_blank">here</a>.</p>
			</article>
			<article id="styles" class="dt-section">
				<h2 class="dt-title">Styles Customizations</h2>
				<p>To change styles default variables go to <code>/_sass/cvio/settings.scss</code>:</p>
				<div class="dt-info-block">
					<pre class="code language-css">
						<code>
/* Colors */
$bg: #fff;
$default-color: #363636;
$extra-color: #999;
$dark-color: #141414;
$light-color: #DDD;
$white-color: #FFF;
$active-color: #f26b38;
$extra-active-color: #ede574;
$error-color: red;

/* Fonts */
$default-font: 'Roboto Mono';
$icons-font: 'Ionicons';

/* Fonts Size */
$large-size: 15px;
$default-size: 13px;
$small-size: 12px;
$extra-small-size: 11px;
$title-size: 68px;
$subtitle-size: 15px;
$h1-size: 26px;
$h2-size: 23px;
$h3-size: 20px;
$h4-size: 18px;
$h5-size: 16px;
$h6-size: 14px;

/* Letter-Spacing */
$default-letter-spacing: 0;
$extra-letter-spacing: 0.04em;

/* Line Height */
$line-height: 23px;

/* Forms */
$form-border: 1px solid $light-color;
$form-border-hover: 1px solid $active-color;
						</code>
					</pre>
				</div>				
			</article>
			<article id="translation" class="dt-section">
				<h2 class="dt-title">Translation</h2>
				<p>To translate all default strings go to <code>/_data/ui-text.yml</code> file</p>
				<pre class="code language-yaml">
					<code>
ui_text:
  home:           "Home"
  blog:           "Blog"
  archive:        "Archive"
  blog_post:      "Blog Post"
  by:             "by"
  share:          "Share"
  share_on:       "Share on"
  tags:           "Tags"
  prev:           "Prev"
  next:           "Next"
  comments:       "Comments"
  full_name:      "Full Name"
  email_address:  "Email Address"
  your_message:   "Your Message"
  send_message:   "Send Message"
  view_project:   "View Project"
  new:            "new"
  search:         "Search ..."
  recent_posts:   "Recent Posts"
  latest_posts:   "Latest Posts"
  categories:     "Categories"
					</code>
				</pre>				
			</article>
			<article id="netlify" class="dt-section">
				<h2 class="dt-title">Netlify</h2>
				<p>Use this <a href="https://www.netlify.com/blog/2015/10/28/a-step-by-step-guide-jekyll-3.0-on-netlify/" target="_blank">Guide</a>: A Step-by-Step Guide: Jekyll 3.0 on Netlify</p>
			</article>
			<article id="icons" class="dt-section">
				<h2 class="dt-title">Icons</h2>
				<p>
					In this template are defined some of classes for icons, your can see all icons here - <a href="https://fontawesome.com/" target="_blank">Fontawesome</a>.
				</p>
			</article>
			<article id="credits" class="dt-section">
				<h2 class="dt-title">Sourse & Credits</h2>
				<h3>Scripts</h3>
				<ul class="dt-list dt-list_nested dt-info-block">
					<li>
						<span class="dt-label dt-label_bold">Jekyll</span> <a target="_blank" href="https://jekyllrb.com/">https://jekyllrb.com/</a>
					</li>
					<li>
						<span class="dt-label dt-label_bold">Animate.css</span> <a target="_blank" href="https://daneden.github.io/animate.css/">https://daneden.github.io/animate.css/</a>
					</li>
					<li>
						<span class="dt-label dt-label_bold">jQuery</span> <a target="_blank" href="https://jquery.com/">https://jquery.com/</a>
					</li>
					<li>
						<span class="dt-label dt-label_bold">Isotope</span> <a target="_blank" href="https://isotope.metafizzy.co/">https://isotope.metafizzy.co/</a>
					</li>
					<li>
						<span class="dt-label dt-label_bold">imagesLoaded</span> <a target="_blank" href="http://imagesloaded.desandro.com/">http://imagesloaded.desandro.com/</a>
					</li>
					<li>
						<span class="dt-label dt-label_bold">jQuery Validation Plugin</span> <a target="_blank" href="http://jqueryvalidation.org/">http://jqueryvalidation.org/</a>
					</li>
					<li>
						<span class="dt-label dt-label_bold">Magnific Popup</span> <a target="_blank" href="http://dimsemenov.com/plugins/magnific-popup/">http://dimsemenov.com/plugins/magnific-popup/</a>
					</li>
					<li>
						<span class="dt-label dt-label_bold">Swiper</span> <a target="_blank" href="https://github.com/nolimits4web/swiper">https://github.com/nolimits4web/swiper</a>
					</li>
					<li>
						<span class="dt-label dt-label_bold">Typed.js</span> <a target="_blank" href="https://github.com/mattboldt/typed.js/">https://github.com/mattboldt/typed.js/</a>
					</li>
				</ul>
				<h3>Fonts</h3>
				<ul class="dt-list dt-list_nested dt-info-block">
					<li>
						<span class="dt-label dt-label_bold">Roboto</span> <a target="_blank" href="https://fonts.google.com/specimen/Roboto">https://fonts.google.com/specimen/Roboto</a>
					</li>
					<li>
						<span class="dt-label dt-label_bold">Fontawesome</span> <a target="_blank" href="https://ionicons.com/v4/">https://fontawesome.com/</a>
					</li>
				</ul>
				<h3>Images</h3>
				<p>Any Images or logos used in previews are not included in this item or final purchase.</p>
				<ul class="dt-list dt-list_nested dt-info-block">
					<li>
						<span class="dt-label dt-label_bold">Unsplash</span> <a target="_blank" href="https://unsplash.com/">https://unsplash.com/</a>
					</li>
					<li>
						<span class="dt-label dt-label_bold">Graphicburger</span> <a target="_blank" href="http://graphicburger.com/">http://graphicburger.com/</a>
					</li>
				</ul>
			</article>		
		</div>
	</div>
<script src="assets/rainbow-custom.min.js"></script> 
</body>
</html>
