### PWA combines the best of web application and native mobile apps.

#### PWA VS. Native mobile apps

Native apps: high capability; low reach. Top ranking apps occupy most customers, while other apps lost opportunity;

Traditional WA:limited device feature access; high reach, no boarders;

PWA: high capability, high reach.



### App Manifest.

Make your PWA installable.

Properties: {"name":"","start_url":"/index.html","scope":".","display":"standalone","background_color":"","theme_color":"", ...}



### Service workers

#### Enable you install WA on home screen.  Make your application work offline.

1. Runs on additional thread, decoupled from HTML pages;
2. Manage all pages on given scope. So html page is not only attached to its javascript;
3. Run in background. Live on even after pages have been closed. 

#### The events that service workers listen to:

1. Fetch
2. Push notifications from server
3. User interaction with notification
4. Background syncronization
5. Service worker life cycle
