# webarch-status
Webarchitects Service Status Website

Available at:

* https://webarch-coop.github.io/

Due to be available at:

* https://status.webarch.net/

To add a status update, (assuming you have write access and have setup your `ssh` public keys) clone the code:

```bash
git clone git@github.com:webarch-coop/webarch-coop.github.io.git
```

And then find this in the `index.html` page:

```html
<!--

Copy the following HTML at add a status update...

<h2 id="d-2016-08-12_13:00">2016-08-12 13:00</h2>

<p>Oh no something broke :-(</p>

-->
```

And copy the `<h2>` and `<p>` and amend as needs be.

One day we might write a `bash` script to add to this page to make life easier...
