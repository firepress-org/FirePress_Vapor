## Checklist for dev

Here are the impacts of our custom elements:

#### 1) files

/partials/custom_footer.hbs
/partials/custom_header.hbs
/package.json

#### 2) directory

/assets/css_firepress/

#### 3) edit default.hbs

In default.hbs, we do reference this:

- {{>custom_header}}
- {{>custom_footer}}
- custom <footer class="site-foot">
