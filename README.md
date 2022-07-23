# css-grid-template-areas

### Crash course by Traversy Media


My main takeaway from this crash course is that we can add the following within the div container in the grid areas to add the layout. 

``` css
body
{
display: grid;
grid-template-areas: 
  'header header header'
  'nav content sidebar'
  'nav footer footer';
}

header 
{
grid-area: header; 

}

nav
{
grid-area: nav; 
}

main 
{
grid-area: content;
}

aside
{
grid-area: sidebar;
}

footer
{
grid-area: footer;
}

```

