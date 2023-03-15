# <!DOCTYPE html>
<html>
  <head>
    <title>My Simple Site</title>
    <style>
      /* Style the sections */
      .section {
        display: inline-block;
        width: 100%;
        padding: 20px;
        box-sizing: border-box;
        text-align: center;
      }
      
      /* Set the width of the sections for desktop view */
      @media screen and (min-width: 768px) {
        .section {
          width: 33.33%;
        }
      }
    </style>
  </head>
  <body>
    <h1>My Simple Site</h1>
    <div class="section">
      <h2>Section 1</h2>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
    </div>
    <div class="section">
      <h2>Section 2</h2>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
    </div>
    <div class="section">
      <h2>Section 3</h2>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
    </div>
  </body>
</html>
