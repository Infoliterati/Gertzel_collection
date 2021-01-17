---
title: About
layout: about
permalink: /about.html
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---

{% include feature/jumbotron.html %}

{% include feature/nav-menu.html sections="About the Collection;About the About Page" %}


## About the collection 

This collection provides a broad overview of the published material in the Gertzel Library. 

It provides the subject areas as well as the quantity and types of published material in the Library. 

The aim is to make information about the collection available in order to find suitable homes for the material so that it can be made avaiable for the benefit of Africanist scholars and researchers. 

There are two types of 'items' in the collection: a visual description of the monographs (as photos of the bookshelves) and textual descriptions of the published periodicals, reports and research papers.  

There are currently 264 items in this collection consisting of:
- 170 images of monographs.  Each photograph represents a shelf of books (between 20-30 titles). These images provide a visual reference of the books in the collection.  

- 94 entries each of which represents a 50L box of published material including reports, periodicals and research papers.   
 
Download a list of all 264 items.  

{% include feature/item-pdf-embed.html objectid="demo_002" width="25" %}


#### Monographs: 
There are 170 images of monographs, rerpresenting approximately 4000 titles.  The majority of the books are about Africa and have been categorised either according to country (69 items) or subject area (54 items).  The remaining 47 items are of other more general topics such as third world development and political theory.

#### Periodicals: 
There are 26 boxes holding around 150 periodical titles.  Approximately 135 of these titles are not available electronically. There are some large runs, such as the Kenua Weekly Review (a complete set from 1970s - 1990s) as well as hard to obtain titles that date back to the 1950s. 

See list of periodical titles here

{% include feature/item-pdf-embed.html objectid="demo_002" width="25" %}
 
#### Government reports  

Extensive collection (approximately 50 boxes) of government reports from Kenya, Uganda, Zambia, East-Central Africa and Australia. Includes parliamentary reports, hansards and legislative documents and generally ranges from 1960s to the 2000s.

#### Non-government reports  

Extensive collection (approximately 7 boxes) of non-government reports from Kenya, Uganda, Zambia, UK, Australia, and international organisations.

#### Research papers 

Extensive collection of seminar papers (7 boxes) and conference papers (4 boxes) mainly from universities and reseach centres in Africa, UK and Australia. 

#### Archives 
Work on the unpublished, archival material is in process and broad descriptions may be provided to this collection in the future. The John Curtin Prime Ministerial Library at Curtin University is currently processing and will be housing some of the archival materials from the Gerzel Library. 


- Image --> `{% raw %}{% include feature/item-figure.html objectid="demo_001" width="25" %}{% endraw %}`

{% include feature/item-figure.html objectid="demo_001" width="25" %}

- PDF -- > `{% raw %}{% include feature/item-pdf-embed.html objectid="demo_002"  width="25" %}{% endraw %}`



- Video: `{% raw %}{% include feature/item-video-embed.html objectid="demo_004" %}{% endraw %}`

{% include feature/item-video-embed.html objectid="demo_004" %}

- Card -- > `{% raw %}{% include feature/card.html header="This is a Card" text="The card features an image from the collection as a cap" objectid="demo_004" width="25" centered=true %}{% endraw %}`

{% include feature/card.html header="This is a Card" text="The card features an image from the collection as a cap" objectid="demo_004" width="25" centered=true %}

- Buttons -- > `{% raw %}{% include feature/button.html text="Button Link to Somewhere" link="https://collectionbuilder.github.io/" color="success" %}{% endraw %}`

{% include feature/button.html text="Button Link to Somewhere" link="https://collectionbuilder.github.io/" color="success" centered=true %}
  
- Alerts -- > `{% raw %}{% include feature/alert.html text="this is an *alert* that 'warns' a user" color="warning" align="center" %}{% endraw %}`

{% include feature/alert.html text="This is an *alert* that 'warns' a user with centrally aligned text." color="warning" align="center"  %}

- Modals -- > `{% raw %}{% include feature/modal.html button="This is a modal using a 'primary' colored button to invite clicking" title="when clicked:" text="A Modal will pop out a box with some more information" color="primary"  %}{% endraw %}`

{% include feature/modal.html button="This is a modal using a 'primary' colored button to invite clicking" title="When clicked:" text="A Modal will pop out a box with some more information" color="primary"  %}

We hope this makes it easier for site builders to develop the collection AND add interesting and engaging contextual information.  

## About Collection Builder

This site is generated using [`collectionbuilder-gh`](https://collectionbuilding.github.io/gh/), a project to create a free and simple digital collection using [GitHub Pages](https://pages.github.com/) from: 

- a CSV of collection metadata
- a folder of JPEG images or PDF documents
