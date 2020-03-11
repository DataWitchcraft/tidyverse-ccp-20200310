## Actual schedule:

Visualization: 9:15 - 12:35  
Data transformation: 13:40 - 16:00  
Markdown: 16:10 - 16:45   

Joins: 9:00 - 10:15    
Types:  
Tidy data:  
Lists:  

## Issues / TO DO

- RStudio IDE - describe how to work with that (files, console, basic keyboars shortcuts, maybe distribute cheatsheet?), discourage just typing to console

### Data visualization

- update facet slides to the new syntax (as on the cheatsheet)
- ggplot now uses a different default palette
- diamonds - density plot: the p1 plot is not defined anywhere
- scales: package viridisLite instead of viridis, scale_colour_viridis_c, scale_colour_viridis_d (already installed with tidyverse) 
- get working directory without the underscore: getwd()

### Data transformation

- new syntax to facets  
- slide 119 may count with using the Rmd examples, it can be quite difficult to do it from the scratch  
- mutate: min_rank() is quite difficult to get  
- we skipped $ and needed it in Rmarkdown
- group_by and summarise wasn't clear after day 1

### Report

- they don't know for loop yet  

### Joins

- first() is confusing   
```
> first(c(2, 3, 4))
[1] 2
```

### Data types

- Factors are introduced in a hard way
- Slides 71-79 can be cut out
