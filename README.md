Polymer Paper Form on Fire
============

[so far](https://youtu.be/BqSPdjLXcPE)

##What is it

It's a quick and easy form we created. It is a Polymer Component Form based on Material Design using the [Polymer Project](https://www.polymer-project.org/) as a guide. It is using Firebase, a realitme server service owned by Google. The Firebase element was designed by the Google Polymer Team. It is also using [paper-date-picker](https://github.com/HackITtoday/paper-datepicker) another component we have created.

For confirmation pop up when form is sent it uses [paper-toast](https://github.com/Polymer/paper-toast)

We have put in an URL pointing to a demo firebase server in which you can see data being updated in realtime.

The paper-datepicker element is [here](https://github.com/HackITtoday/paper-datepicker)

The polymer firebase element is [here](https://github.com/Polymer/firebase-element)

Firebase server service is [here](https://www.firebase.com)

It was also created on the [polymer seed-element](https://github.com/PolymerLabs/seed-element) template hence the contributors. Apart from the Authors the contributors on the list did not add directly to the form, just the seed-element.

#Hacks

You can change the Firebase URL to your own URL. We have used [form.firebase.io-demo.com](form.firebase.io.demo.com). If you use the demo and send the form you can see the data update in real time. Which we think is very cool.

Remember it's free to create a starter account so it's easy to get it up and running.

Also we connected [Zapier](https://zapier.com/) for ourselves with Firebase to get confirmation emails with the details of the form. You can change and use the form for anythying you like and get confirmations using a service like Zapier to anywhere you want. Very simple Hack.


#How to Use

##Bower Install

To install using bower.

>bower install paper-form-on-fire  --save

##Add a link

>\<link rel="import" href="bower_components/paper-input/paper-input.html" /\>

##Add a Tag
>\<paper-form-on-fire\>\</paper-form-on-fire\>

##Firebase
Change the Firebaser URL to whatever you like or just use the demo

#Need Your Help
We put this up quickly as we thought how powerful it could be and how quick it would be to make. There are some issues and would love for anyone to add more or help with some Pull Requests. We have [Waffle.io](https://waffle.io/) board integration below to show we are working on it. It shows the number of issues we are working on and the throughput of issues.

[![Stories in Ready](https://badge.waffle.io/hackittoday/paper-form-on-fire.svg?label=ready&title=Ready)](http://waffle.io/hackittoday/paper-form-on-fire)

[![Throughput Graph](https://graphs.waffle.io/hackittoday/paper-form-on-fire/throughput.svg)](https://waffle.io/hackittoday/paper-form-on-fire/metrics)

#Authors

This was created by [Marcus7777](https://github.com/marcus7777) with very little help from [woisme](https://github.com/woisme) for [HackIT](https://github.com/hackit)
## Testing Your Element

Add the logic specific to your new element and verify its functionality. Good unit tests are essential to your verification plan but a good way to quickly sanity test your component is to access your demo.html file via a local web server. There are several ways to do this but one easy method is to run a simple web server that ships with Python, using the commands:

```sh
python -m SimpleHTTPServer
```

Or other method using NodeJS:

```sh
http-server ./
```

This starts a web server on port 8000, so you can test your new element by navigating a browser to `localhost:8000/test/index.html`.

### web-component-tester

The tests are also compatible with [web-component-tester](https://github.com/Polymer/web-component-tester). You can run them on multiple local browsers via:

```sh
npm install -g web-component-tester
wct
```

Licence: [MIT](http://opensource.org/licenses/MIT)
