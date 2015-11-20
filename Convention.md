##Conventions.
Divide the classes by a '-'. A single one, never use two (not a BEM fan).
There will be "Conditional fields" (not the module).
The fields will be:
1. The type of the page, example: "panel".*
2. What the page shows, example: "node", "taxonomy", "view".
3. An identifier to name what is is being shown, example: "blog", "blogpost".
5. After that, the specific detail of the fields or element, example: title.*
6. Wrapper, in case there is one, of a single element: "wrapper".*

The ones marked with a (*) are conditional. Not necessary.
What is useful about them being conditional is that by avoiding some of them, it can be clear that a class is meant for a specific part of the page, for example, "panel-taxonomy-blogcategory-title", is meant for the title of the blog category taxonomy, which is in fact, a panel. But, "taxonomy-blogcategory-title" is meant for the title of the node, in the blog category term of the taxonomy.

A few examples of this convention are shown below: 
"panel-node-blogpost-title"
"panel-taxonomy-blogcategory-title"
"view-blog-"
