# Tailwind CSS Implementation

This repository showcase my previous HTML and CSS project but integrated with Tailwind CSS a styling framework.

## How does it work?
Tailwind CSS works by scanning all of your HTML files, JavaScript components, and any other templates for class names, generating the corresponding styles and then writing them to a static CSS file. This means that CSS files is no longer required as the styling will be writing directly in the html files.

This results in fast, flexible and reliable with zero-run time

## How does the styling works?
styling works by editing the html tag and adding styling properties directly.

### Example
lets say we want to add padding to both left and right of an element. We can use the standard CSS styling by writing

```css
padding-left: 0.25rem; /* 4px */  
padding-right: 0.25rem; /* 4px */

```
However we can reduce this code by using Tailwind CSS and writing

`
px-1`

### 'P' Padding 
In Tailwind, majority of the properties are reduced to their abreviation. If it is padding we use `p`, if it is margin `m`.  Some properties may be different so please have a look at the documentation. 

### 'X' Direction of padding 
Next we require the direction, since left and right can also be translated as x (when you think of x axis on a graph) this allows a unique way of grouping. This also applies to y-axis (can be different depends on the type of properties so please look at documentation for more information). There are also 'l' and 'r' for single side direction

### '1' The length or Unit

The unit '1' will actually represent 4px and if its '2' it will be 8px. This result the unit to be multiple of 4px. This can be change if you desire [Customising Spacing](https://tailwindcss.com/docs/customizing-spacing)


**NOTE:** if you want to look at more of padding example click [here](https://tailwindcss.com/docs/padding).

If you want to see more examples click [here](https://tailwindcss.com/docs/utility-first)


## Likes

1. **Very quick and simple:** After reading the documentation, you dont have to think much on writing standard CSS as the naming convention removes long extensible properties 

2. **Only HTML files:** theres no need to switch to a css file as you can work directly in the html file saving huge amount of time.

## Dislikes
1. **Reptitive** If you are working mul

2. **Only HTML files:** theres no need to switch to a css file as you can work directly in the html file saving huge amount of time.








