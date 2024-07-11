## Flask Application Design

**HTML Files**

**1. base.html**
- This file will serve as the base template for all other HTML files used in the application.
- It will include the necessary HTML structure, such as header, footer, and navigation bar.
- The CSS styling for the application will also be linked from this file.

**2. index.html**
- This file will be the main landing page for the application.
- It will include the main content of the page, such as:
    - Captivating text to introduce the Dune: Imperium board game
    - High-quality images and animations showcasing the game's features
    - A call-to-action button for users to learn more or purchase the game

**Routes**

**1. @app.route('/')**
- This route will handle the initial request to the application.
- It will render the index.html file, which is the main landing page.

**Note:**
- The HTML files specified above are the minimum required for this application. Additional HTML files can be created to accommodate more content or functionality if needed.