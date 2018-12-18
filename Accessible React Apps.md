allycast (irrelevant)

* Updating page title in react app

  * adds context
  * SEO
  * How:
    * use document.title() function
      1. `​componentDidMount { document.title = ${thing.name}}`

* informing user that page new page has loaded
  * kind of like reporting a full page refresh
    * use refs
    * `​this.varName = React.createRef()`
    * ​`​this.container.current.focus()`