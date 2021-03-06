# Static Website: To-Do List

Simple static website design for to-do list.

In this project, you will follow step-by-step instructions to fix a to-do web app. All of the HTML and most of the CSS is intact, however, a few Flexbox values are missing.

In order to complete this project, you must know how to set an element’s Flexbox properties.

We recommend that you review our Flexbox Lesson before beginning.

The website’s existing index.html and style.css files are displayed in the text
editor to the right. Good luck!

[!image](https://github.com/abemsq/to-do-list/blob/master/image.png)

## HTML
```
Flexbox: To-Do App
In this project, you will follow step-by-step instructions to fix a to-do web app. All of the HTML and most of the CSS is intact, however, a few Flexbox values are missing.

In order to complete this project, you must know how to set an element’s Flexbox properties.

We recommend that you review our Flexbox Lesson before beginning.

The website’s existing index.html and style.css files are displayed in the text editor to the right. Good luck!
```

## CSS
```
/* Universal Styles */

body {
  margin: 0px;
  background-color: WhiteSmoke;
  font-family: 'Rock Salt', cursive;
  text-align: center;
}

.secondary-background {
  background-color: Snow;
}

.tagline {
  font-family: 'Quicksand', sans-serif;
  color: LightSlateGrey;
  line-height: 125px;
}

/* Header */

h1 {
  margin: 0;
  background-color: SkyBlue;
  line-height: 100px;
  color: Khaki;
}

h2 {
  margin: 10px;
}

/* App Container */

.container {
  border: 2px solid Snow;
  display: flex;
}

/* To Do Section */

.week {
  display: inline-flex;
  flex-grow: 3;
  flex-direction: column;
}

.row {
  min-height: 200px;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
  align-items: center;
}

.square {
  width: 125px;
  height: 125px;
  padding: 10px;
  display: flex;
  justify-content: center;
  align-items: center;
}

.day.square {
  background-color: SkyBlue;
  border: 1px solid white;
}

.task.square {
  background-color: Khaki;
  border: 1px solid white;
}

.task p {
  font-family: 'Quicksand', sans-serif;
  font-weight: 700;
  font-size: 12px;
}

/* Reminders */

.reminders {
  background-color: Khaki;
  display: inline-flex;
  flex-grow: 2;
}

.reminders h3 {
  width: 100%;
  margin: 10px;
  color: black;
  line-height: 90px;
  font-size: 24px;
}

/* Footer */

footer {
  font-size: 24px;
}
```