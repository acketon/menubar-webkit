# Menubar WebKit

**menubar-webkit** helps you create Mac menubar app using HTML and JavaScript without writing any Objective-C code. menubar-webkit exposes an JavaScript object called ``mw`` to provide system functions.

## API

```JavaScript
// Quit application
mw.quit()

// Open URL in default browser
mw.openURL("http://pomotodo.com")

// Set menubar icon
mw.setMenubarIcon("images/icon.png")

// Auto start with system
mw.setAutoStart(true)

// Send system notification
mw.notify({
  title: "Pomotodo",
  content: "Break is over!"
})
```

## Integrating Web App

Too see the sample app:

```bash
mv sample public
```

To add your own app:

```bash
git clone your.repository.address public
```

## Progress

| API               | Implemented? |
| ----------------- | ------------ |
| mw.quit           | Yes          |
| mw.openURL        | Yes          |
| mw.setMenubarIcon | No           |
| mw.setAutoStart   | No           |
| mw.notify         | Yes          |