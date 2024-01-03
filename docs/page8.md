## JavaScript File Instructions

## Sidebar Toggle Variables

- `menuToggler`: Represents the HTML element for toggling the sidebar.
- `sideBar`: Represents the HTML element for the sidebar.

## Page Navigation Variables

- `navItemLinks`: Represents all navigation links in the sidebar.
- `pages`: Represents various sections or pages of the website.

## Filtering Variables

- `filterBtn`: Represents all filter buttons on the webpage.
- `itemCategory`: Represents categories associated with portfolio items or elements.

## Toggling Sidebar in Mobile

- `menuToggler` click event listener toggles the visibility of the sidebar in mobile view by adding/removing the "active" class to `sideBar`.

## Page Navigation Functionality

- For each navigation link (`navItemLinks`), an event listener is added to handle click events.
- When a navigation link is clicked, the corresponding section/page associated with the link's text content is displayed by adding the "active" class to the relevant page and link. Other pages and links have the "active" class removed.

## Filtering Functionality

- Event listeners are added to each filter button (`filterBtn`) to handle click events.
- When a filter button is clicked, it adds the "active" class to itself and filters the displayed items based on the category text content (`itemCategory`).
- Items with matching category text or when "All" is clicked will have the "active" class added, while others will have it removed.

## Note:

- The script uses class toggling and iteration through HTML elements to control the visibility and behavior of sidebar, navigation, and filtering functionality on the webpage.
- Ensure the HTML elements match the JavaScript variables and classes for proper functionality.
