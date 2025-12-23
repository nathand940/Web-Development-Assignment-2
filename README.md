Web Development Assignment 2:

Project Name: SkySense

Description:

For this assignment I was tasked with creating a weather app that displays weather and forecast for 7 days for multiple countries across the world.
By using Eleventy and Bulma I was able to create a dynamic, mobile-friendly weather dashboard that allows you to navigate to pages displaying the weather forecast for specific countries.

Website Features:

- Weekly forecast cards for the countries: AUstralia, Ireland, Japan, Russia, Spain, the UK and the USA.
- The weather conditions (temp, wind speed, weather type) for each country are displayed under each country.
- Emojis, gathered from Unicode.org, are used to represent the weather type for each country and day.
- Clickable cards which navigate users to that specific country or preference page.
- A preference page where users can choose the countries they wish to be displayed, how they would like the weather to be measured (celsius/fahrenheit), dark mode to be toggled on or off, etc.
- A responsive design by using Bulma CSS
- Lastly, custom backgrounds to match the different weather conditions for each spcific country.

Technologies Used:

- Eleventy was used to help generate a static site and to create a means to navigate between pages.
- Bulma was used to create a responsive design to allow users to navigate to and from pages.
- HTML and Nunjucks templates were used for reusable components
- Javascript was used to create the Navbar that was interactive, created a NavbarBurger that was displayed when the page was zoomed in on (this was also interactive).
- Javascript was also used to create an interactive preference page allowing users to clickbox certain settings and countries to be displayed.
- A custom weather.css block of code was created for backgrounds to represent the weather for those countries.

 The structure of the files is as follows:
 
- _includes - Nunjucks components
- _site - Generated Files
- css - Stylesheets
- image - Icons, favicon, logos
- pages - Index.njk, preferences.njk, country html pages
- .eleventy.js - Eleventy config
- package.json - Project dependencies

How to run program:
- Ensure node is installed by opening command promt and typing: node -v
- Next type: cd path/to/project
- Then type: elvenety --serve

Deployment:

- The website was manually deployed via Netlify by dropping and dragginh the _sitre folder and having netlify build it from there.
- Build command: npm run build
- Publish directory: _site.

Known Issues:

- I attempted to push deploy the website from git by adding in the package.json, package-lock.json and the node_modules but Netlify identified issues in the code.
- I attempted to correct the code based on the instructions given but this led to more issues unfortunately.
- I ended up manually deploying in the end.

Attributions:
- Emojis used throughout assignment were gathered on unicode: https://unicode.org/emoji/charts/full-emoji-list.html
- Image used to represent Australia acquired from unsplash: https://images.unsplash.com/photo-1729404646839-7b27451f0148?q=80&w=870&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D
- Image used to represent Ireland acquired from unsplash: https://images.unsplash.com/photo-1515963931004-51a07139e710?q=80&w=870&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D
- Image used to represent Japan acquired from unsplash: https://images.unsplash.com/photo-1718936333474-d56608984837?q=80&w=870&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D
- Image used to represent Russia acquired from unsplash: https://images.unsplash.com/photo-1606840958465-dacedcc72239?q=80&w=870&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D
- Image used to represent Spain acquired from unsplash: https://images.unsplash.com/photo-1716924229394-2ef50eb6e9d1?q=80&w=870&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D
- Image used to represent UK acquired from unsplash: https://images.unsplash.com/photo-1505761671935-60b3a7427bad?auto=format&fit=crop&w=1600&q=80
- Image used to represent USA acquired from unsplash: https://images.unsplash.com/photo-1628034456699-c4e34656fdd2?q=80&w=871&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D
- Image used for browser Icon: https://cdn-icons-png.flaticon.com/128/3222/3222791.png
- Image used for Logo in header: https://skysense.ag/assets/img/logo.jpg 
- Image used for Logo in footer: https://skysense.ag/assets/img/logo_footer.png
- Split used in HTML ages was learned from Shopigy.github: https://shopify.github.io/liquid/filters/split/
- How to install and use eleventy navigation plugin: https://www.11ty.dev/docs/plugins/navigation/
- Hardcoded checkboxes used for preferences page to allow users to customise settings. Information gathered from W3Schools: https://www.w3schools.com/tags/att_input_type_checkbox.asp
- Hardcoded radio buttons used for preferences page to allow users to customise settings. information gathered from W3Schools: https://www.w3schools.com/tags/att_input_type_radio.asp
- Navburger information used from class notes on dotify: https://tutors.dev/lab/setu-cert-comp-sci-2025-web-dev-1/unit-01/topic-08-bulma-recap/unit-0/book-bulma/05
