This Project is a React application with SASS installed in it and a folder structure that I used for my personal projects

The folder structure is the following

```
example-project
  public/
  src/
    assets/
      styles/
        1-helpers/
        2-tools/
        3-basics/
        4-layout/
        5-modules/
        6-pages/
        main.scss
    images/
    ...
```

### 1-helpers

Inside this folders goes all files that helps you while building the application. Like for example mixins, functions, variables/constants, etc.

### 2-tools

Inside the tools folder I like to put all the third party scss code, vendors that I will use in the project.

### 3-basics

Basics folder contains the bare bones basics of the project like global styles, buttons, links, inputs, typography.

### 4-layout

Inside the layout will go the bigger portions of the application, like footer, navigation, header

### 5-modules

Here you put everything that is modular, those things that you can use across the app, like a logo section, stats section, video section

### 6-pages

As the name of this folder says here goes the styles for the different pages in the app

# Remember to cascade your files correctly

## In SASS the order of the imports matter
