   * `git add .`
   * `git commit -m "<COMMENT>"`
   * `git push origin master`
   * `git add .`
   * `git commit -m "<COMMENT>"`
   * `git push origin master`
Responsiveness

Using Bootstrap, recreate your portfolio site with the following items:

   * A navbar

   * A responsive layout (remember the grid, rows and columns are your friends)

     * eg. On `xs` and `sm` screens, each section should take up the entire grid. On `md` and larger screens, each section should take up 2/3 of the grid and the sidebar should take up 1/3 of the grid
Instructions - (No Bootstrap)

Use three `@media screen` tags, each with one of these `max-width`s: `980px`, `768px` and `640px`.

   * You use `980px` because you never want any of the content to be cut off. Since the desktop layout is about 960px wide, you want the media queries to kick in before your content gets cut off.

   * `768px` is about the width of a tablet and `640px` is about the width of a phone in landscape.

Be sure to include the `viewport` tag in all your HTML files, otherwise your media-queries won't function as expected on mobile devices. _(Hint: You won't need to use exact pixels for anything other than the container)_