# ionic-ssr-flickering-example
This example demostrates that ionic ssr has visible flickering when switching between server and browser version.

It has been made to demonstrate this issue: https://github.com/ionic-team/ionic/issues/21245

It visualizes the loading process by showing the text "Server" and "Browser" in the app-header and on the page-header, depending of where the content was rendered.

**To see it in detail:**
 
1) npm run build:ssr   (to have prod version with minimum bundle size)
2) npm run serve:ssr
3) open browser, set network speed to slow-3g
4) load localhost:4000
     -> blank page when swapping between server side rendered page and client side rendered page



**Comparison Project**


This Example has been made in comparison to the complete same app in angular alone:
https://github.com/KevinBassaDevelopment/angular-ssr-no-flickering-example

In comparison to angular alone, using ionic introduces 2 visible steps when changing from server to browser version.


**Live Examples**

https://angular-ssr.bassa-solutions.at/

https://ionic-ssr.bassa-solutions.at/
