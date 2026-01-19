# Animation Tests

This repository contains a collection of animation tests for different micro interaction animations with plain CSS and JavaScript (if necessary).

## How to run

1. Clone the repository
2. run `yarn` to install dependencies
3. run `yarn dev` to start the development server

## Available animations

### Chatbar animation

A Chatbar animation that toggles between message input state and media upload state.

It uses Grid layout for element positioning, transforms for animation, and linear easing functions for smooth and bouncy transitions.

### Email App

A user interface that animates the opening of user email inbox.

It uses Grid layout for element positioning, transforms for animation, and cubic-bezier easing functions for smooth and bouncy transitions. and FLIP animation technique for animating the unread count from one state to another

### Extra menu

A user interface that animates the opening of a menu with extra options.

It uses Grid layout for element positioning, transforms for animation, linear easing functions for smooth and bouncy transitions. and SVG morphing from Hamburger menu to caret icon

### Finger Toolbar

A user interaction that animates an indicator to the icon user selected.

It uses mix-blend-mode for color invertion, Javascript for calculating the position of the selected item and animates indicator to that position, linear easing functions for smooth and realistic transitions.

### Grid boxes

An interaction that tries to uncover how 'AnimatePresence' works under the hood by using the FLIP animation technique. It animates the grid boxes entry and exiting of the DOM with plain CSS and Javascript.

### Ovelay View

A user interface that animates the opening of a modal view.

It uses Grid layout for element positioning, transforms for animation, and cubic-bezier, linear easing functions for smooth and bouncy transitions.

SVG morphing is also used to morph the close button from caret to close icon

CSS Clip path is used to reveal and hide the content of the modal view

### Simple justify content test

A simple test that animates the justify-content property of a flex container to simulate the switching of a Checkbox. this is how Framer-motion animates CSS items that are not naturally animatable, using the FLIP animation technique.

### Switcher

An animated toggle switch with smooth spring physics and morphing SVG animations.

It uses a custom spring easing function defined with CSS `linear()` for realistic bouncy transitions, CSS `d` path morphing to transform a circle into a vertical line when toggled, and dynamic background color transitions. The switch features a pill-shaped container with a sliding indicator that translates 100% on toggle, complete with scale-down effect on active press and smooth shadow transitions that match the current state color.
