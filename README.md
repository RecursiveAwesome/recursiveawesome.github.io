# Cookie - a fast and easy to deploy landing website for your next project.
Cookie is a Jekyll and Tailwind CSS based static website that makes the whole process of creating and launching landing websites extremely easy. With its responsive and mobile friendly pages, integrated blog, additional pages and [Soopr](https://www.soopr.co) integration, you can focus on building your product than landing website.

## Features
* Well-designed landing page
* Responsive and mobile friendly
* Additional pages like about us, terms of service & privacy policy
* Integrated blog, write content in markdown format
* Easy to customize using Tailwind CSS
* Fast and performant website
* SEO optimized (uses [Jekyll SEO Tag](https://github.com/jekyll/jekyll-seo-tag))
* RSS feed (uses [Jekyll Feed](https://github.com/jekyll/jekyll-feed))
* Easy to deploy, one-click deploy on [Netlify](https://www.netlify.com) possible
* [Soopr](https://wwww.soopr.co) integrated - easy to customize share & like buttons, URL shortning and website analytics


## Demo
[![Netlify Status](https://api.netlify.com/api/v1/badges/58bd7992-1cc1-4fb9-b684-6be577a06324/deploy-status)](https://app.netlify.com/sites/cookie-demo/deploys)
<br />
You can see demo app deployed [here](https://cookie-demo.netlify.app/)

## Why Jekyll?
Jekyll is a static website generator - what it means is that in production, your site will be faster because it has been converted into HTML pages while deployment. Another reason is that by separating your landing website from your app website, your app servers get comparatively free and can boost performance for your regular customers. 

Cookie uses Tailwind 2.0 which is a good improvement over Tailwind 1.0.

## Installation
1. Fork this repository.
2. `cd cookie`
3. `bin/bootstrap`

## Starting Server
`bin/start` - development server will start at http://127.0.0.1:4061

## Customizing
1. You can customize landing page by modifying index.html in root directory.
2. You can customize other website pages by modifying files present in `_pages` directory. You can add more pages too - you will be able to directly link to them using filename. Don't forget to change Terms & Privacy Policy.
3. You can write blog posts in `_posts` directory. It's a regular Jekyll blog, and Tailwind Typography for better blog formating and code syntax highlighting is already included.
4. You should also checkout `_config.yml` in root directory, and add relevant details. Many of them are used for SEO purposes.
5. You should also add favicons in `custom-head.html` present in `_includes` directory. You can use [RealFaviconGenerator](https://realfavicongenerator.net/).
6. You can customize image assets in `assets/img` directory.
7. You will have to hook the 'Work with Us' form present on main page with a real backend.
8. [Font Awesome](https://fontawesome.com/) is also integrated, to add any icon in your HTML files, you can refer to the website

## Deploy Instructions
Website can be easily deployed on all the cloud providers (AWS etc.), and on static website hosting services like Netlify & Vercel. You can also use this button to do one click deploy
<br />
<br />
[![Deploy with Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/abhinavs/cookie)


## Contributing
Bug reports and pull requests are welcome on GitHub at https://github.com/abhinavs/cookie.

## Acknowledgement
Cookie uses landing page provided by [Tailwind Starter Kit](https://www.creative-tim.com/learning-lab/tailwind-starter-kit/presentation) - thanks for providing an amazing landing page under MIT License. Initial code was also inspired by [Jekyll TailwindUI](https://github.com/chunlea/jekyll-tailwindui)

## License
This project is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

## Blog Sample

---
layout: post
---
You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: http://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/

## Blog Sample 2

---
layout: post
---

[Soopr][soopr-website] is the easiest way for you to add share reaction buttons to your blog and website, integrate an URL shortener and simple to understand analytics service. Soopr lets you manage all of these using a powerful dashboard.

Cookie uses Soopr for share and like buttons and is already integrated. By default, Cookie shows `circular` Twitter, Facebook and Copy buttons in `base` size. To add `like` button, please signup for free on [Soopr][soopr-website]

Once you have signed up on Soopr, get a publish token for your website and edit `_config.yml` file and add it under `soopr` key and restart the server.
```yml
soopr:
  publish-token: "ADD_YOUR_PUBLISH_TOKEN_HERE" 
```

Check out the [Soopr Website][soopr-website] for more info on how to get the most out of Soopr. 

[soopr-website]: https://www.soopr.co



