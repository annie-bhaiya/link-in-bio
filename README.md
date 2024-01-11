# linkinbio

Link In Bio Page for Instagram, Twitter, Tumblr etc

## Introduction

As many of you will know, you can only have one link on your Instagram and Twitter Bios. To overcome this, many users use third party link in bio apps to show multiple links. However, the downside of this is your are distracting people from your brand by linking to another site rather than your own.

Some of these third party options allow for you to use a custom domain but that is usually a premium option you need to pay for.

Given that many of these third party link in bio pages are just a list of links I decided to roll my own.

You can see an example of what this looks like here: [https://alexhyett.com/links](https://alexhyett.com/links).

You can read more about it on my blog [How to Create a Link in Bio Page for Instagram](https://www.alexhyett.com/create-link-in-bio-page/).

## How to use

You first need to update the profile section by changing the `h1` tag to your own name as well as changing the location and bio information. You will also want to add in your own profile photo. Your profile photo should be square.

Next you need to add in links to all your profiles.

You can do this by copy and pasting one of the link blocks and updating the text and links.

```
<a href="https://instagram.com/alexhyettdev" class="block link">
    <div class="image-float instagram">
        <div class="beacon instagram"></div>
        <div class="image">
            <img src="images/instagram.svg" />
        </div>
    </div>
    <div>
        <h2>Instagram</h2>
        <div>@alexhyettdev</div>
    </div>
    <div class="arrow">
        <i class="fas fa-arrow-right"></i>
    </div>
</a>
```

### Social Media Colors

The following CSS classes have been added which can be used to show the correct colors for the beacon and image shadow.

- `amazon`
- `dev`
- `facebook`
- `github`
- `google`
- `instagram`
- `linkedin`
- `medium`
- `paypal`
- `twitter`
- `youtube`

### Beacon

If you want one or more of the links to stand out you can apply the beacon div to just above the `image` div so that it will pulsate.

```
<div class="beacon instagram"></div>
```

### Images

I have included logos for all the sites mentioned above in the social media colors section.
