# From Design System to Code - Ignite Lab

This is the result of Ignite Lab, a Rocketseat event whose theme was the creation of a design system, from the conception using figma to the construction of the interface using React JS.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [About Project](#about-project)
  - [Link](#link)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### Screenshot

![](./src/assets/images/screenshot.png)

### About Project

The creation and construction of the Design System started with Figma, where the color tokens, font sizes, styles and the creation of the components used in the layout were created.

Once ready, we made a transition to the code, which used React JS to build the interface and Tailwind for the styling, where we imported all our color tokens, font sizes, etc...

Storybook was used as a tool for documenting application components. With it, it is possible to visualize the components in isolation from the rest of the code with all its variations, in addition to being able to check accessibility issues and even perform unit tests on the components.

### Link

[Documentation - Storybook](https://kevenpacheco.github.io/ignite-lab-design-system/?path=/story/pages-sign-in--default&globals=backgrounds.value:!hex(333333);backgrounds.grid:false)

## My process

### Built with

- [Typescript](https://www.typescriptlang.org/)
- [React](https://reactjs.org/)
- [Tailwind](https://tailwindcss.com/)
- [Vite](https://vitejs.dev/)
- [Radix-UI](https://www.radix-ui.com/)
- [Storybook](https://storybook.js.org/)
- [Figma](https://www.figma.com/)

### What I learned

Among the many new concepts I learned, I can mention:
- The concepts of the design system and how it is created;
- A new React pattern called Composition, which is a component, which is actually composed of several other smaller components, making it easier to create custom components without having to create new properties for those variations. The example is the `<TextInput>` component, which is composed of three smaller components, `<TextInput.Root>` which involves the entire component, `<TextInput.Icon>` which may or may not exist and `<TextInput.Input>`;
- The creation of components that can have their html tag changed in certain contexts in a simple way using the Radix-UI Slot component, such as a `<button>` that can become an `<a>`;
- And how to document the Front-end using Storybook.

## Author

- [LinkedIn](https://www.linkedin.com/in/kevenpacheco/)
