1. Functional Expectations
score: 2.5 
  --> application recreates site, "home" button doesn't work. Adds HTML5 email client function for contact

  4: Application recreates the original site and adds three Interactive Elements
  3: Application recreates the original site and adds one Interactive Element
  2: Application has some small missing functionality
  1: Application is not a usable replacement of the original site

2. Test-Driven Development
score: 2
  --> application does not demonstrate effective TDD. Feature test coverage is limited, no isolation or integration tests are used.

  4: Application is broken into components which are well tested in both isolation and integration using appropriate data
  3: Application is well tested but does not balance isolation and integration/feature tests
  2: Application makes some use of tests, but the coverage is insufficient
  1: Application does not demonstrate strong use of TDD

3. Encapsulation / Breaking Logic into Components
score: 3
  --> app.rb holds more than routes, some of this could be broken into better logic, but good over all. You could also create an instance for each DB so as to avoid singleton methodology.

  4: Application is expertly divided into logical components each with a clear, single responsibility
  3: Application effectively breaks logical components apart but breaks the principle of SRP
  2: Application shows some effort to break logic into components, but the divisions are inconsistent or unclear
  1: Application logic shows poor decomposition with too much logic mashed together

4. Fundamental Ruby & Style
score: 3

  4: Application demonstrates excellent knowledge of Ruby syntax, style, and refactoring
  3: Application shows strong effort towards organization, content, and refactoring
  2: Application runs but the code has long methods, unnecessary or poorly named variables, and needs significant refactoring
  1: Application generates syntax error or crashes during execution

5. Sinatra / Web and Business Logic
score: 2

  4: Application takes advantage of all the features Sinatra has to offer and effectively separates the web application from the business logic.
  3: Application makes good use of Sinatra but has some mixing of the web and business logic.
  2: Application has web and business logic totally mixed together
  1: Application demonstrates a weak understanding of Sinatra and how applications should be built.

6. View Layer
score: 2~3
  --> tooooooooo much inline CSS, I really like the use of HAML, it makes the code clean, but styling should be specific to CSS file

  4: Application expertly breaks components out to view partials and makes use of both built-in and custom-written view helpers.
  3: Application breaks components out to view partials but has some logic or complexity leaking into the view
  2: Application has messy views that mix logic and presentation
  1: Application shows a lack of understanding around view templates and how they should be used/constructed.