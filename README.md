# pwa-features

This is a demo of different features available in Progressive Web Apps (PWA) with Service Workers in Angular.

## Demo
Demo is [here](https://pwafeatures.herokuapp.com/) or scan the QR code

![QR code](https://chart.googleapis.com/chart?cht=qr&chl=https%3A%2F%2Fpwafeatures.herokuapp.com%2F&chs=180x180&choe=UTF-8&chld=L|2 "PWA Demo")


## Current PWA capabilites in this demo

- [Camera based on HTML5](https://pwafeatures.herokuapp.com/camerahard)
- [Camera based on Hardware](https://pwafeatures.herokuapp.com/camerasoft)
- [Push notifications with HTML5](https://pwafeatures.herokuapp.com/pushhtml5)
- [Push notifications with Service Worker](https://pwafeatures.herokuapp.com/pushworker)
- [Motion](https://pwafeatures.herokuapp.com/motion)
- [Orientation](https://pwafeatures.herokuapp.com/gyro)


## Documentation

Read our [blog](https://www.silveridea.net/category/pwa/) for documentation.

Google Official Documentation for PWA is [here](https://developers.google.com/web/fundamentals/codelabs/)


## Setup

```ts
git clone https://github.com/silveridea/pwa-features.git
cd pwa-features
npm install
```
Since "service worker" works only in production mode, we need to build it for prod.
```ts
ng build --prod
```

We need to serve the built version from the "dist" folder.
We will use lite-server to run it.
```ts
npm run lite
```
Now browse to http://localhost:3000


Your feedback is important


[Silveridea](http://www.silveridea.net/?utm_source=github&utm_campaign=link2) is a JavaScript agency in Sydney, Australia       [Hire us](http://www.silveridea.net)
