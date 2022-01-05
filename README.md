![App logo](./public/img/fodee_logo.png)

# Fodee

Food ordering dashboard app

![Splash page](./public/img/fodee_Splash.png)

## Why this app as created:

Proof of concept: This app was created as an example of React state, regular expressions, core Javascript functions and seamless U.X design.

## How to use:

1. Clone repo into desired directory `git clone https://github.com/Toughee/Fodee.git` or `gh repo clone Toughee/Fodee`
2. Run `npm install` in your terminal to install all app node modules and dependencies
3. Run `yarn start` in your terminal to run app on http://localhost:3000/

## Testing tools used for app:

-   React Testing library
-   Jest
-   Cypress
-   TravisCI
-   CircleCI

## Project resources:

-   [Current roadmap for app](https://github.com/Toughee/Fodee/projects/1)
-   [Wiki page for app](https://github.com/Toughee/Fodee/wiki)
-   [Documentation for project contributors](https://github.com/Toughee/Fodee/tree/main/docs)

### Completed app tasks:

-   [x] Include CircleCI and Travis-CI inside project
-   [x] Improve U.I. design for app

### Future app goals:

-   [ ] Fix addition error with float number where sum shows dozens of numbers after float period (example: cart sum shows up as $32.2000000000 instead of fixed amount)
-   [ ] Working checkout button for numbers. With boolean conditionals that show data when cart is active or not
-   [ ] Fix subtraction error where numbers keep subtracting from each state even as state has 0 values inside of it. (example: cart goes negative when remove button is pressed after no item and cart sum is at 0)
-   [ ] Disable remove button when no item is in car
-   [ ] Perfect U.X. design for app
-   [ ] Refactor code and cut code volume. Divive the majority of UI elements into smaller components
