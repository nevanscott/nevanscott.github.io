---
layout: long
title: Jekyll for Designers
lede: Tom Preston-Werner started work on Jekyll with a simple idea - "What would happen if I approached blogging from a software development perspective? What would that look like?" Turns out the solution he came up with is also a great tool for web _designers_. Here's why and how to make use of this great tool.
published: false
---

I've been kicking Jekyll's tires for a little over a month now, trying to establish its viability as a tool for web designers, and I've been pretty happy with how easy and powerful it has been.

h3. You might want to try Jekyll if...

* You like to design in the browser, from the content out
* You want to keep your design code under version control
* The data you're designing with is a bit more complicated than blog posts with titles
* You want to use different designs for different posts, but keep the same header and footer around (a la "Jason Santa Maria":http://jasonsantamaria.com/)

h3. Installation

Jekyll's "installation page":http://wiki.github.com/mojombo/jekyll/install covers this pretty well. If you have Ruby installed on your system, you should be able to run @sudo gem install jekyll@ on the command line. That should be all it takes. If you need to install Ruby first, just visit the Ruby "downloads page":http://www.ruby-lang.org/en/downloads/ and follow the instructions there.[1]

fn1(sidenote). If you're running Mac OS X Leopard or later, you're in luck! A recent version of Ruby should already be installed. To confirm, just run @ruby --version@.

h3. Setup

Let's get started with just the very basics. Create an empty directory for your project. For demonstration purposes let's call it @mysite@. Run the following commands:

pre. $ mkdir mysite
$ cd mysite
$ touch index.html

Now open your newly-created @index.html@ file in your favorite text editor and put the following code in:

pre. ---
title: My Site
---
<html>
	<head>
		<title>{{ page.title }}</title>
	</head>
	<body>
		<h1>Welcome to My Site</h1>
	</body>
</html>

With that done, hop back over to the command line and run:

pre. $ jekyll --server

The @jekyll@ command tells Jekyll to look through the files in the current directory and parse them according to Jekyll's rules, generating a static site in the specified directory. In this case, we haven't specified a directory, so Jekyll will use its default @_site@.

The @--server@ flag tells jekyll to also start a light-weight local server after it generates the site, which by default should run on port 4000. Once it is done generating the site, you should see output somthing like this:

pre. Building site: . -> ./_site
Successfully generated site: . -> ./_site
[2009-12-28 17:51:03] INFO  WEBrick 1.3.1
[2009-12-28 17:51:03] INFO  ruby 1.8.7 (2008-08-11) [universal-darwin10.0]
[2009-12-28 17:51:03] INFO  WEBrick::HTTPServer#start: pid=11151 port=4000

Then in your favorite browser, visit @http://localhost:4000/@ to see the results. You should see the @index.html@ file you wrote, without any of the YAML frontmatter that came between the dashes. The file has been run through a liquid filter so that the @{{ page.title }}@ in your code will be replaced with "My Site" - the title you provided in the frontmatter.

----

Alright, all that feels too technical to me for some reason. What's a better way to approach introducing someone to Jekyll? Is there a good way? Or do you really first need to know git, and development in general? This kind of introduction is just going to drive people away...

What is really motivating here? Why use Jekyll in the first place? Yes, it is a specific tool that meets my own specific needs. It's better for focusing on content than almost any other system I have worked with. It would probably be even better if it worked with Django's templating system instead of Liquid. But there are enough similarities that it isn't a big deal. Maybe what I need are some larger examples, hosted on github, that I can refer to.