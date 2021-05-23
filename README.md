# index.html
<!DOCTYPE html>
<ang="en">

  <head>
    <!-- Set viewport with -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- Link to CSS -->
    <link rel="stylesheet" href="styles.css" />
    <title>Search</title>
  </head>

  <body>
    <!-- HEADER START -->
    <div class="header">
      <div class="header-links"> <a href="images.html">Google Images</a> <a href="advanced.html">Google Advanced Search</a>        </div>
    </div>
    <!-- HEADER END -->
    <!-- SEARCH CONTAINER START -->
    <div class="search-container">
      <img src="https://www.google.com/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png"
      alt="Google logo" />
      <form action="https://www.google.com/search" method="get">
        <div class="search-field">
          <svg height="21" viewBox="0 0 21 21" width="21" xmlns="http://www.w3.org/2000/svg">
            <g fill="none" fill-rule="evenodd" stroke="#808080" stroke-linecap="round" stroke-linejoin="round">
              <circle cx="8.5" cy="8.5" r="5" />
              <path d="m17.571 17.5-5.571-5.5" />
            </g>
          </svg>
          <input type="text" name="q"> </div>
        <input type="submit" value="Google Search">
        <!-- Adding a name to the feeling lucky button includes the parameter in the URL -->
        <input type="submit" name="btnI" value="I'm feeling lucky"> </form>
    </div>
    <!-- SEARCH CONTAINER END -->
  </body>

</html>
