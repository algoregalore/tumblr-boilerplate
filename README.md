Tumblr Boilerplate - 2.0.3
------

A fully functional bare-bones Tumblr theme that works out of the box. Style it to your needs. The goal of the project was to remove uncessary code easing the development process.

###Getting Started

1. Choose an [Installation](#install) method.
2. Modify `tumblr.html` with your favorite code editor.
3. Publish it by going to `http://tumblr.com/customize/{your_blog_name}`.
4. Click *Edit HTML* on the left column.
5. Copy & paste your customized code then click *Save*.

### <a name="install"></a>Installation

* [Bower](http://bower.io/): `bower install tumblr-boilerplate`
* [Github] (https://github.com): `git clone https://github.com/davesantos/tumblr-boilerplate.git`
* [Download](https://github.com/davesantos/tumblr-boilerplate/archive/master.zip).

### Features

* HTML5 tags
* [Normalize.css](http://necolas.github.com/normalize.css/) from [cdnjs](https://cdnjs.com/)
* Supports all [post](https://www.tumblr.com/docs/en/custom_themes#posts) types
* Theme options from [global appeareance](https://www.tumblr.com/docs/en/custom_themes#global_appearance)
* [Localization] (http://www.tumblr.com/docs/en/custom_themes#localization) strings

__Theme does not support__

* Comment System ([Disqus](https://disqus.com/))
* [Group Blogs](https://www.tumblr.com/docs/en/custom_themes#group-blogs)
* [Notes](https://www.tumblr.com/docs/en/custom_themes#notes)
* [Srcset Attribute](http://caniuse.com/#search=srcset)

(Intentionally not included to remain flexible in the various uses for a theme.)

###Caveats

Tumblr will auto-inject code (such as [Open Graph Protocol](http://ogp.me/), [Twitter Cards](https://dev.twitter.com/cards/overview) & javascript) into the final result for your page. This is out of the theme developers' control. Running it through a HTML Validator or Page Speed may spit out warnings & errors.

(Tumblr injects `<!DOCTYPE html>`, twice!)

###Optional Snippets

[Open Graph Protocol](http://ogp.me/). If you choose not to include this in the `<head>`, Tumblr is auto-generate it for you.

```
<head prefix="og: http://ogp.me/ns# fb: http://ogp.me/ns/fb# blog: http://ogp.me/ns/blog#">
```
And this:

```
  <meta property="og:site_name" content="{Title}">
  <meta property="og:url" content="{BlogURL}">
  <meta property="og:image" content="{PortraitURL-128}">
  <meta property="og:type" content="tumblr-feed:tumblelog">
```

###Resources
* [Custom Theme Documentation](http://www.tumblr.com/docs/en/custom_themes)
* [tumblr.com/developers](https://www.tumblr.com/developers)
* [Tumblr Developer Blog](http://developers.tumblr.com/)
* [HTML 5 Boilerplate] (http://html5boilerplate.com/)

###License

[MIT](https://github.com/davesantos/tumblr-boilerplate/blob/master/LICENSE.md)



