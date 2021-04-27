## Welcome to GitHub Pages


....HERE IS MY OWN CONTENT SOME MORE SOME MORE

I AM GOINT TO PUT SOME MORE LINKS TO sTRIPE PAYMENTS HERE

<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />

    <title>Stripe Checkout Sample</title>

    <link rel="icon" href="favicon.ico" type="image/x-icon" />
    <link rel="stylesheet" href="css/normalize.css" />
    <link rel="stylesheet" href="css/global.css" />
    <script src="https://js.stripe.com/v3/"></script>
    <script src="./index.js" defer></script>
  </head>

  <body>
    <div class="sr-root">
      <div class="sr-main">
        <header class="sr-header">
          <div class="sr-header__logo"></div>
        </header>

        <section class="container">
          <div>
            <h1>Single photo</h1>
            <h4>Purchase a Pasha original photo</h4>

            <div class="pasha-image">
              <img
                src="https://picsum.photos/280/320?random=4"
                width="140"
                height="160"
              />
            </div>
          </div>

          <div class="quantity-setter">
            <button class="increment-btn" id="subtract" disabled>-</button>
            <input type="number" id="quantity-input" min="1" value="1" />
            <button class="increment-btn" id="add">+</button>
          </div>

          <p class="sr-legal-text">Number of copies (max 10)</p>

          <button id="submit">Buy</button>
        </section>

        <div id="error-message"></div>
      </div>
    </div>
  </body>
</html>

<html>
  <head>
    <title>Buy cool new product</title>
    <script src="https://js.stripe.com/v3/"></script>
  
// Set your publishable key: remember to change this to your live publishable key in production
// See your keys here: https://dashboard.stripe.com/apikeys

var stripe = Stripe(

'pk_test_51IikpYCAB1IEzkyGzXFNpjtWEw1Zet4dbptTDZfO9Sk6XgU8pMVU3TAbUjsYMIiNG9iuL2DkUNUn94sgfYK41bY900kOxyju8i'

);

var elements = stripe.elements();
  
  
  
  
  
  
  
  
  
  </head>
  <body>
    <button id="checkout-button">Checkout</button>
  </body>
</html>


You can use the [editor on GitHub](https://github.com/matauranz/matauranz.github.io-/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/matauranz/matauranz.github.io-/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
