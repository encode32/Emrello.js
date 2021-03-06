# Emrello.js

Embed Trello cards, lists, and even boards on your web page with periodic updates.

## Embed a card

```
<div data-emrello-type="card" data-emrello-id="{card short name/id}"></div>
```

## Embed a list

```
<div data-emrello-type="list" data-emrello-id="{list id}"></div>
```

## Embed a board

```
<div data-emrello-type="board" data-emrello-id="{board short name/id}"></div>
```

## One more thing

Add `emrello.js` at the end of your HTML page. You will also need a Trello API key,
which you can easily generate from [here](https://trello.com/1/appKey/generate).

```
<script type="text/javascript" src="emrello.js" data-emrello-key="{app key}"></script>
```

## Why?

Trello lets you embed cards and boards in your page like this:

```
<!-- embed as image -->
<img src="https://trello.com/c/ShRTNamE.png" /><!-- a card -->
<img src="https://trello.com/b/sHRtNaMe.png" /><!-- a board -->

<!-- embed as a JavaScript that renders the object by document.write -->
<script src="https://trello.com/c/ShRTNamE.js"></script><!-- a card -->
<script src="https://trello.com/b/sHRtNaMe.js"></script><!-- a board -->

<!-- using an iframe -->
<iframe src="https://trello.com/c/ShRTNamE.html"></iframe><!-- a card -->
<iframe src="https://trello.com/b/sHRtNaMe.html"></iframe><!-- a board -->
```

These methods get you a static card or board, and would not get updated with
realtime changes (These files are generated every few minutes though). If you
want to update your embedded Trello object more often than that, you need to
use **Emrello.js**.

With **Emrello.js** you get the ability to embed lists as well.

## Contributing

Emrello.js is still at alpha stage. It has to have a lot more things before
it can ever be used in production. Your contributions are welcome.

Head over to [Emrello.js's Trello board](https://trello.com/b/vUMIXgBw). You
will finds some things that need immediate attention in "Bugs" and "Features
to be added" lists.

Kindly send all your pull requests to `dev` branch.
