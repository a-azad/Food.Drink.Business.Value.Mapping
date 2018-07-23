### Motivation

- __Have you__ ever thought about funding a business in the  __food and drink__ industry? Have you ever wanted to have your own business but you did not know what and where? 
- __You__ did not know to what capacity you should invest. You did not know what kind, i.e., restaurant, coffee shop, pub, pizza place or stake house. You did not know in downtown, near your apartment, north of town, in an expensive area, etc. You did not know what menu you should offer. You did not know about your business model. And of course tens of other key questions.
- __You__ wanted to talk to a financial advisor, a business consultant, a talented chef, your mom, your friend who likes sushi, ... You were thinking of having a conversation with someone on Wall Street ... And, many other approaches.  
- __Is__ there any one-fit-all solution? I think there is. Data can help us out. It is no longer in hands of some genius people who can predict the future. This is a multi-dimensional problem and we have data in many of those dimensions. 
- __This__ is a multi-tier problem solving project in business analytics. The idea is very simple.Through data, we know how often people go to what restaurant and roughly how much they spend. We know economics of different areas in a city, we know how hard/easy it is for people to move around to reach a popular place, we can estimate traffic, we know parking capacity, we know weather challenges, we know ... and there are huge amount of data that is available to support us. It is the matter of how efficient we can link them.
- __Result__ of this project is a map. A map that can help businesses to think about their next move. If you already have a business, you want to know what near future might look like in your specialty. If you want to open a new business, what cuisine you should think of and where.

![](pix/map_.png)


### Experiment Unit
I live and eat in __Seattle__. No need to explain why I would love to start this work in Seattle. To start focus would be on restaurants only. There are some early hypothesis testing and proxy modeling that need to be made before I can firmly scale it up and include more dimensions to the project.

![](pix/seattle.jpg)


### Tier One

In the first step, I needed a proxy to be able to estimate financial health of different areas 

The attractive [Yelp Open Dataset](https://www.yelp.com/dataset) as promoted by its owners is _an all-purpose dataset for learning_ which continually is used across the data science community. In this project, __YELP__ dataset is explored to show the advantage of using large dataset in helping businesses --the food industry in this case. 

### Access to data

Yelp provides access to data via their API (GraphQL) as well as direct access to a SQL dump. In this project, I set up a local SQL server to provide access to data directly within Python environment. So, 


![](pix/yelp_dataset_schema_.png)



### Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/a-azad/Yelp.Data.Project/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/a-azad/Yelp.Data.Project/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
