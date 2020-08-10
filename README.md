# SerenitySkins

_**Serenity Sking Spa ** Serenity Skin Spa's websites allows customers to signup with a profile and manage their services and make appointments._


<br>

## MVP


_The **Serenity Skins Spa** This website allows users to sign up and manage appointments. Once they signup with their email they can add services this company provides. They will be able to create appoinments on whatever date they want. They will be able to delete, update and review the service they selected.._

<br>

### Goals

- Allow customers to create a profile_
- Customers will be able to view provided services._
- Customers will be able to select services and view them individually alog with prices._
- Customers will be able to remove and services update the services selected._


<br>

### Libraries and Dependencies


|     Library      | Description                                |
| :--------------: | :----------------------------------------- |
|      React       | _Build encapsulated components that manage their own state._ |
|   React Router   | _Collection of navigational components that compose declaratively with your application._ |
| CSS | _Cascading Style Sheets is a style sheet language used for describing the presentation of a document._ |
|     Ruby on Rails      | _Ruby on Rails, is a server-side web application framework._ |


<br>

### Client (Front End)

#### Wireframes

> Use the Wireframes section to display desktop, tablet and mobile views. No hand-drawn wireframes. Use a tool like wireframe.cc, Whimsical or AdobeXD

https://wireframe.cc/PUwm75

- Desktop Landing

https://wireframe.cc/6OmKy2

- Desktop Hero

https://wireframe.cc/lBTUEh

- Resource Index

https://wireframe.cc/OqJUXd

- Resource Show

https://wireframe.cc/uEBxCX

- Tablet Resource Index

https://wireframe.cc/qF656C

- Mobile Resource Index

#### Component Tree

https://drive.google.com/file/d/1JqhojbjRlBkTxTHOlwnHUytFNUxsjRZl/view

#### Component Hierarchy

> Use this section to define your React components and the data architecture of your app. This should be a reflection of how you expect your directory/file tree to look like. 

``` structure

src
|__ assets/
      |__ fonts
      |__ graphics
      |__ images
      |__ mockups
|__ components/
      |__ Header.jsx
|__ services/

```

#### Component Breakdown

> Use this section to go into further depth regarding your components, including breaking down the components as stateless or stateful, and considering the passing of data between those components.

|  Component   |    Type    | state | props | Description                                                      |
| :----------: | :--------: | :---: | :---: | :--------------------------------------------------------------- |
|    Header    | functional |   n   |   n   | _The header will contain the navigation and logo._               |
|  Navigation  | functional |   n   |   n   | _The navigation will provide a link to each of the pages._       |
|   Gallery    |   class    |   y   |   n   | _The gallery will render the posts using cards in flexbox._      |
| Gallery Card | functional |   n   |   y   | _The cards will render the post info via props._                 |
|    Footer    | functional |   n   |   n   | _The footer will show info about me and a link to my portfolio._ |

#### Time Estimates

> Use this section to estimate the time necessary to build out each of the components you've described above.

| Task                | Priority | Estimated Time | Time Invested | Actual Time |
| ------------------- | :------: | :------------: | :-----------: | :---------: |
| Add Contact Form    |    L     |     3 hrs      |     2 hrs     |    3 hrs    |
| Create CRUD Actions |    H     |     3 hrs      |     1 hrs     |     TBD     |
| TOTAL               |          |     6 hrs      |     3 hrs     |     TBD     |

> _Why is this necessary? Time frames are key to the development cycle. You have limited time to code your app, and your estimates can then be used to evaluate possibilities of your MVP and post-MVP based on time needed. It's best you assume an additional hour for each component, as well as a few hours added to the total time, to play it safe._

<br>

### Server (Back End)

#### ERD Model

https://drive.google.com/file/d/1t1wmLFiidZLxloW2hx20aUWmXOqyuUwU/view

<br>

***

## Post-MVP

> Use this section to document ideas you've had that would be fun (or necessary) for your Post-MVP. This will be helpful when you return to your project after graduation!

***

## Code Showcase

> Use this section to include a brief code snippet of functionality that you are proud of and a brief description.

## Code Issues & Resolutions

> Use this section to list of all major issues encountered and their resolution.
