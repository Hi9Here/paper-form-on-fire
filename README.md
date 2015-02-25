Polymer Paper Form on Fire
============

##What it is

It is a Polymer Component Form that is based on Firebase a realitme server service owned by Google. The Firebase element it is on is called Firebase Element and was designed by the Google Polymer Team. It is also using [paper-date-picker](https://github.com/HackITtoday/paper-datepicker) another component we have created

We have put in an URL pointing to a demo firebase server in which you can see data being updated in realtime. 

The paper-date-picker element is [here](https://github.com/HackITtoday/paper-datepicker)

The polymer firebase element is [here](https://github.com/Polymer/firebase-element)

Firebase server service is [here](https://www.firebase.com)



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
