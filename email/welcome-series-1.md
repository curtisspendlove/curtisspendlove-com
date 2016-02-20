---
layout: default
---

# Environment

In Lesson 1 we explore a typical, but bare minimum, development environment suitable for building static websites. In the future, we’ll expand this environment with additional tools to support building more complex, dynamic websites.

The absolute minimum set of tools needed are a basic text editor, a distributed version control system, and a hosting platform. (Although not **exactly** essential, a version control protocol is *highly* suggested. And since our choice—Github—just happens to also easily host static websites, it’s perfect for our objectives.)

## Version Control (Github)

Over the course of the past decade [git](https://git-scm.com) claimed the throne as the de-facto standard distributed version control system. Likewise, [Github](https://github.com) surfaced as the canonical option to host both public and private source code repositories.

Eventually we’ll explore additional options, but you really *should* have a Github presence if your ultimate goal is to get hired as a professional software developer.

Head on over to the Github web application and create an account. This process is fairly straight forward, but if you get stuck Github has excellent [support documentation](https://help.github.com/articles/signing-up-for-a-new-github-account/). (Insert link for getting started with github blog post.)

## Development (Cloud9)

In recent years the advent of “Cloud IDEs” redefined and simplified the concept of a common development environment, accessible from nearly any computing device.

Although fierce competition ensues in the Cloud IDE realm, [Cloud 9](https://c9.io)is a solid contender and tied as my favorite Cloud IDE.

Like Github, Cloud 9 offers [free accounts](https://c9.io/web/sign-up/free)for public and low-usage scenarios. Again this process is fairly straight forward, but if you get stuck Cloud 9 also has excellent [support documentation](https://docs.c9.io/docs/getting-started).

## Hosting (Github Pages)

It’s no surprise that Github is a powerful force in the software development community. They provide significant benefits to all members of their platform.

We will learn to interact with Github at a lower level in later lessons. However, for our first repository, we’ll create a traditional “Hello, World” project using the Github web interface.

An added benefit to this process is automatic integration with the [Github Pages](https://pages.github.com) hosting platform.

As Github has excellent documentation, we’ll go ahead and follow their [hello world](https://help.github.com/articles/create-a-repo/) example.

In the following steps, we dive into the technical (my mentoring philosophy is “jump into the fire”, but we’ll jump together) aspects of building a basic website. If this is the first time you’ve done this, this process might take some time, even some trial and error.

Please keep in mind, even though this may be challenging, nothing is **forever** in the software development realm. You can easily modify code, or even wipe out the repository and start over from scratch if you feel nuking and paving is necessary.

If you feel frustrated, please consult the *Resources* section at the bottom of this email. There are a few additional resources, including a screencast video, to help you out.

### Create a New Page

Now that you’re sporting a [shiny sample repository](https://github.com/knightotoldcode/hello-world), let’s soup it up a bit and make a hosted website out of it.

1. Click “New file”
2. Enter the name of the file “index.html” (above the file editor pane)
3. Add the following text:

{% highlight html %}
	<!DOCTYPE html>
	<html lang="en">
	  <head>
	    <meta charset="utf-8">
	    <title>Hello, World!</title>
	  </head>
	  <body>
	    Hello, World!
	  </body>
	</html>
{% endhighlight %}

(Feel free to customize this, for example, perhaps add your name and some personal information.)

### Commit the New Page

We entered the page and its content in the Github web interface.

(The Github web application is actually quite powerful for being able to interact with your repositories through a standard web interface. In the future, however, we’ll explore much more powerful methods to control your source code.)

In git, when we want to solidify changes to a source code file (like our new index.html file), we *commit* it. The simplest way to do this is to use the “Commit directly to the master branch” option in the “Commit new file” panel.

(If you look at my repository, I’ve used the more advanced “Create a new branch for this commit and start a pull request.” option. As a professional software developer, I try to use pull requests and other industry-standard practices as often as possible. However, this is an advanced topic we will cover in more detail later. I mention it here simply for awareness, in case your repository differs slightly from mine.)

### Trigger Github Pages

There are two ways to trigger the built-in Github Pages platform: a certain repository name, and ensuring a hostible website is in the ```gh-pages``` branch.

Since we followed the Github repository tutorial above, our repository is most likely named something like ```hello-world```. This is fine, we can turn it into a hosted page by ensuring we have the site code in the ```gh-pages``` branch.

#### Create ```gh-pages``` Branch

The Github web interface contains everything we need to create the appropriate branch.

1. Ensure you have the *index.html* file listed in your repository.
2. Click the “Branch: master” dropdown near the ‘New pull request’ button.
3. In the input box labeled “Find or create branch”, type: “gh-pages”.

This should create the new branch and copy your existing code into it.

### Preview the Hosted Site

The presence of a ```gh-pages``` branch should indicate to Github Pages that you want a website hosted from this repository. The little robots housed at the Github campus will kick in and build the website in a location available to the greater web.

We can verify this by clicking the “Settings” tab below the “Un/watch”, “Star”, and “Fork” buttons.

The Settings page should indicate “Your site is published at: http://username.github.io/repository-name” under the Github Pages panel.

Clicking this link should take you to your new page in your web browser.

## Conclusion

In Lesson 1 we created accounts on Github and Cloud 9, which will be useful for future lessons. We also created a basic “Hello, World” style example site on Github Pages (the free platform we’ll be using to host the full website created throughout this series).

The next lesson explores fleshing-out the “Hello, World” website into a more cohesive one. We will learn what the code in “index.html” actually does, and prepare for future lessons to create “About” and “Contact” pages.

## Resources

* [Getting Started with Github](https://curtisspendlove.com/article/2016/02/16/getting-started-with-github.html)
* Video: Watching Curt Do this in More Detail, as a Screencast
