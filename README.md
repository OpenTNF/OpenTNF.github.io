<h1><img src="https://github.com/OpenTNF/opentnf/blob/master/logo.png" tag="OpenTNF" style="float: left"> OpenTNF</h1>

OpenTNF™ is an open specification for interoperability and exchange of data on Transport Networks. The format enables users to read and write OpenTNF™ data files using either self-written or Open Source software. 

OpenTNF™ is and shall be free of charge, globally useful and an open complement to international standards such as INSPIRE DS TN, GDF and ISO 19100 and national standards such as SOSI (Norway) and SS63700x (Sweden). Our common goal for the work is characterized by openness and simple and effective solutions.

OpenTNF's mission statement:

_Create and maintain, as a community, an international, open and efficient solution for exchange of Transport Network data. The solution will enable easier usage of data on multiple platforms._

The OpenTNF™ format is specified as a set of data tables that in principal may be implemented in any relational database engine. An OpenTNF™ dataset is compliant with INSPIRE DS TN and may contain the following types of data:

* Transport network including the definition of linear referencing, geometric, topological and temporal aspects
* Attribution and features, here called transport properties, related to the geography and/or transport network using linear referencing mechanisms. OpenTNF™ uses a generic approach where all types use the same schema where the types are defined in a separate catalogue data structure.
* A transport property type catalogue defining the various transport property types. This catalogue may also contain definitions of secondary linear referencing systems.
* Metadata, also according to any XML compliant standard such as ISO 19139
* Update (transaction) information for the case that the dataset represents a set of updates

To align to this specification an implementation shall implement all mandatory and conditional elements as specified. Optional elements may be implemented and if they are implemented they shall be implemented as specified. Finally, an implementation may add additional elements and extend this specification provided that all mandatory, conditional and optional elements are not affected. This means that implementations are free to add tables or columns.

The first release of the specification is available for download <a href="https://github.com/OpenTNF/opentnf/blob/master/OpenTNF%20-%20white%20paper.pdf" target="_blank">OpenTNF 1.0  <img src="https://github.com/OpenTNF/opentnf/blob/master/pdf_icon.png" tag="pdf"></a>

Everyone is invited to contribute to further development and maintenance of OpenTNF™. We encourage you to read, review, evaluate, use, discuss and comment this initiative and document.

The OpenTNF™ specification is licensed under the Creative Commons Attribution-No Derivative Works 4.0 Unported License. To view a copy of this license, visit http://creativecommons.org/licenses/by-nd/4.0/.


## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/OpenTNF/OpenTNF.github.io/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

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

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/OpenTNF/OpenTNF.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
