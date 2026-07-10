# Prompt

You are a Content writer and a Front-end developer.

Currently you are working on a landing page for a developer conference "DevConf 2026" where users can get information about the conference, secure spots etc.

The hero section, speakers corner section, pricing section, footer section is done. Now you will be adding a new section after pricing.

This section needs to be Unique and Creative. Also it needs to visually fit with the overall theme. To give an idea of the project some CSS is provided below,

```css
/* global reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

html {
  font-size: 62.5%;
}

body {
  font-family: "Inter", sans-serif;
  font-size: 1.6rem;
  line-height: 1.8;
  color: var(--gray-900);
  font-weight: 400;
}

:root {
  --blue-900: #0d1b2a;
  --blue-700: #1d4ed8;
  --blue-500: #2563eb;
  --blue-300: #3b82f6;
  --blue-100: #60a5fa;
  --blue-50: #93c5fd;

  --gray-900: #333;
  --gray-700: #575757;
  --gray-500: #888888;
  --gray-100: #e5e7eb;

  --border-color: var(--gray-100);

  --white: #fff;

  --border-rad: 1.2rem;
}

a {
  text-decoration: none;
}

/* typography */

.heading-1 {
  font-size: 8rem;
  font-weight: bold;
  line-height: 8rem;
  letter-spacing: -3.2px;
  color: #fff;
}
.heading-2 {
  font-size: 5.6rem;
  line-height: 6.44rem;
  color: #000102;
}
.heading-3 {
  font-size: 4.4rem;
  line-height: 4.8rem;
  font-weight: bold;
}
.heading-4 {
  font-size: 2rem;
  line-height: 2.7rem;
  font-weight: 700;
}
.heading-5 {
  font-size: 1.2rem;
  text-transform: uppercase;
  letter-spacing: 2px;
}

/* container */

.container {
  max-width: 132rem;
  margin-left: auto;
  margin-right: auto;
}

.navbar .container {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  align-items: center;
  padding: 2.4rem 0;
}

/* components */

.btn,
.btn:link,
.btn:visited {
  display: inline-block;
  font-weight: bold;
  text-transform: capitalize;
  transition: all 0.2s ease-in-out;
}

.btn--primary,
.btn--primary:link,
.btn--primary:visited {
  padding: 1.2rem 4.8rem;
  color: var(--white);
  background-color: var(--blue-700);
  border-radius: var(--border-rad);
}
.btn--primary:hover {
  background-color: var(--blue-500);
}

.btn--ghost,
.btn--ghost:link,
.btn--ghost:visited {
  font-size: 1.4rem;
  line-height: 2.1rem;
  padding: 1.2rem 4.8rem;
  color: var(--blue-500);
  border: 1px solid var(--blue-500);
  border-radius: var(--border-rad);
}
.btn--ghost:hover {
  background-color: var(--blue-500);
  color: var(--white);
}

.text-muted {
  color: var(--gray-700);
}
.text-center {
  text-align: center;
}
```

Visit [This Link] (https://shariult.github.io/b14-a01-devconf-2026/) to get an idea of the current state (HTML Structure and content).

I would like you to create and design the content for the Schedule Section and give me the HTML and CSS.
