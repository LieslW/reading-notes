# HTML5 Layout  

**HTML5** is the newest version of HTML
- New elements that indicate purpose of different parts of the page which also help describe structure  
  - *e.g. `<header>`, `<body>`, etc*  
- These elements make the code more clear in divisions of the page
  - Before, multiple `<div>` elements labeled with IDs or class attributes to indiciate various page sections 
    - e.g. `<div id="page">`, `<div class="article">`, etc  

**New Elements**  
- ***`<header>`***: appears at top of page, contains site name and main navigation  
  - Individual headers can be used throughout the page for `<article>` and `<section>`  
- ***`<footer>`***: appears at bottom of the page, contains copyright info, terms and conditions, privacy policy, etc  
  - Individual footers can be used throughout the page for `<article>` and `<section>` 
- ***`<nav>`***: contains major navigational blocks 
  - *e.g. Home, About Us, Store, etc* 
- ***`<article>`***: any section of the page that can stand alone  
  - *e.g. blog entries*  
- ***`<aside>`***: contains related but non-essential info  
  - can be within `<article>` element or on the page itself  
- ***`<section>`***: groups related content with its own header  
- ***`<hgroup>`***: individual headers for sections  
  - *e.g. different sizes, `<h1>, <h2>, <h3>,` etc*  
- ***`<figure>`, `<figcaption>`***: referenced content from article  
  - *e.g. images, diagrams, videos, etc*  
  - `<figcaption>` are the captions below said content   
- ***`<div>`***: used same way as previous HTML version if no designated element for the class
  - *e.g. `<div class="wrapper">`*  

Older browsers that do not recognize new HTML5 code need to be told block-level elements and may require extra JS, available free from Google. (e.g. Internet Explorer 8).
