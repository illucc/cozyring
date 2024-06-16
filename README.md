---
permalink: /about
---

# Cozyring!

Cozyring is a webring for cozy and cute websites :3

## Joining

To join the webring, you'll have to make a pull request and create a file in the `_ring` folder named `YOUR_NAME.html` -- this name won't be used anywhere except for in the URL of the navbar widget.
Its content should be like this:

```md
---
href: "<url>"
name: "<name>"
blurb: |
  <description>
---
```

where:

- `<url>` is the URL of their website, that links in the webring for your website will point to.
- `<name>` is the name shown in the navbar widget, and on the index page.
- `<description>` is a brief description, used in the listing on the index page.

You can also have a look at existing entries to see examples

OR if you dont know how to make a pr please mail me at me@illuc.xyz ill add you to the webring :3

## How to embed the navbar

Once you're part of this webring, you'll need to add the navbar widget to your website.
To do so, include the following html snippet, replacing `YOUR_NAME` with the username you registered with.

```html
<iframe style="width: 100%; border: none;" src="https://cozyring.illuc.xyz/embed/YOUR_NAME"></iframe>
```

<!-- {{ "--" }}{{ ">" }}

Here's an example of what it looks like (with an added border so you can see the size):

<iframe style="width: 100%; border: none;" src="{{ site.ring[0].url | absolute_url }}"></iframe>

{{ "<!" }}{{ "--" }} -->

Feel free to tweak the style attribute -- these are just defaults that work for most people.

You can specify `<extra html>` to inject extra CSS to your widget to make it fit in better with your website.
