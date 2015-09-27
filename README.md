# PersonalPresentations

This repository contains all the presentations that I gave, in IPython notebook format 

Here is a short guide about how to convert the Ipython into the actual presentation format in my blog. In my blog, which is forked from [Stephan's Blog](http://stephen-brennan.com/talks/), I use Reveal.js which works with markdown files

### Step 1:

- Convert Ipython file into the markdown

```
$ jupyter nbconvert <name.ipynb> --to markdown
```

- It will create a markdown file from the ipython notebook. 

> BTW, you can directly make a presentation by using nbconvert. You simply;

```
$ jupyter nbconvert <name.ipynb> --to slides --post serve
```

- Then it will run on the local host perfectly.  (If you don't know how to make slides in notebook check out my [presentation]() on that)

### Step 2:

- Ok, now we have the markdown, we need to say the render where the slides end and where they change type...

```
{{slide}}

```

> Will continue to edit
