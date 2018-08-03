# A11Y Nutrition Cards

A11Y Nutrition Cards is an attempt to digest and simplify the accessibility expectations when it comes to component authoring. Based on the <a href="https://w3c.github.io/aria-practices/">WAI ARIA Authoring Practices Guide</a>.

## Roadmap

- [ ] Add more components
- [ ] Simplify language
- [ ] Add framework-less CodePen demos for each component
- [ ] Use `<details>` to hide/disclose optional or advanced techniques.
 
## Contributing

Thank you very much for your interest in this project. While I won't be prompt, there's like a 90% chance I'd merge anything you commit.

## Building Locally

The site is built with [Jekyll](https://jekyllrb.com/) (you'll need Ruby to run Jekyll) and deployed via Github Pages. Not sure if it's the best path but leveraging Jekyll's Collections feature to organize components. If you'd like to help contribute locally...

```
git clone git@github.com:davatron5000/a11y-nutrition-cards.git
gem install jekyll
jekyll serve --livereload
```

To add a new component, create a new file in the `_components/` folder.
