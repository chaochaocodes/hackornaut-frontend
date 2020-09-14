# Hackornaut

Hackornaut (Have you been Hacked or Not?) is a single page web application where a user can search to see if their email addresses have been compromised in any database breaches.  A user can view the details of all recorded breaches and learn about ways to increase their email security. 

This React app was created in collaboration with [Allen](https://github.com/azhang9328) and [Eric](https://github.com/EricStukenberg) at Flatiron School.  The [backend](https://github.com/chaochaocodes/hackornaut-backend) is built with Ruby on Rails. Hackornaut's data is available through [HaveIBeenPwnd's API](https://haveibeenpwned.com/API/v3). 

## How to Use

1. Clone this repo and this [repo](https://github.com/chaochaocodes/hackornaut-backend).
2. In hackornaut-backend, run bundle, rails db:migrate, and rails s to start the server
3. In hackornaut-frontend, run npm start, which will open the app in localhost:3001

## Stack

- React.js with implementation of React Router
- Bootstrapped with Create React App
- Ruby on Rails
- HIBP API
- Styled with Material UI 

##

![Image of Privacy Page](https://github.com/chaochaocodes/hackornaut-frontend/blob/master/screenshots/privacy.png)
