
# Modern CSS3 Animated Hamburger Menu

This is an  easy-to-implement, editable HTML/CSS-only hamburger menu that you can easily integrate into your website.

The menu by default occupies half the page when it is open, but this can be easily changed. All navigation items are editable

Important: This is not WordPress Plugin.

## Features
- Fully Responsive
- Works on all browsers (like Chrome, Bing, Firefox etc. )
- Minimalist, modern look
- Smooth purely CSS animations
- Easily edit the theme colour of the Navigation bar
- Easily edit the size of the Navigation bar
- Easily edit the icon size
- Can be easily integrated to any existing website


## Documentation

### Changing the Colour

To change the theme colour of the website:

- Open the "style.css" file in a text editor
- Go to the `:root` selector
- Go to the variables under the comment "`/* Edit Theme Color */`"
- Enter the desired [hex code](https://htmlcolorcodes.com/) in the space after the colon, where the current [hex codes](https://htmlcolorcodes.com/) are (it may be `#333` or `#fff`)
- You may click [here](https://htmlcolorcodes.com/) to pick a hex code for the colour you want.
- Alternatively, you can type in colours in full words such as "white" or "black". as long as the colour is present in this table [here](https://www.tutorialrepublic.com/css-reference/css-color-names.php)

### Changing the Menu size

If you want the menu to span the full page, only half the page or any percentage of the page,:

- Open the "style.css" file in a text editor
- Go to the `:root` selector
- Go to the variable under the comment "`/* Adjust Menu Size */`"
- Enter the desired percentage of the screen you want the menu to take after the colon (for example, if you want the navigation to be full screen, you can put 100% like this `--navigation-width: 100%;`)

### Changing the Font/Icon/Animation
(Go to steps on "changing the colour" or "changing the menu size")All other variables apart from the variable labeled `--hamburger-height`,  can be edited to adjust your specific website. Though, if you want an external font from places like [Google fonts](https://fonts.google.com/), you may copy the HTML link from the cite and paste under the section that says `<!-- Add Font Links Under this Comment -->`

### Changing the menu items

- Open the "index.html" file in a text editor
- Go to the comment that says `<!-- Add Menu Items under this comment -->`
- To add more menu items, copy and paste the `span` tags (A whole span tag may look like this `<span class="item"><a href="">Home</a></span>`)
- To edit the contents of the menu item, go to the word right after the full "a" tag (for example the word in capital letter here, was edited `<span class="item"><a href="">CONTACTS</a></span>`)
- To make the item link somewhere insert the link in between the quotation marks right after the word `href` (for example, the link is shown in capital letters here `<span class="item"><a href="LINK">Home</a></span>`)
## Authors

- [@king525dev](https://www.github.com/king525dev)


## Acknowledgements

 - [WebDevSimplified](https://www.youtube.com/@WebDevSimplified)

