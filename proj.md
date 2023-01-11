---
layout: default
title:  Embeds
nav_order: 4
---

# Embedding from your digital collections

When embedding an item the best option is to look for an embed code option for the item you would like to add to your markdown page. You can slap html or an iframe directly into markdown.
____

# YouTube:
Just grab the embed link from the share button, add the iframe to your markdown file.

```html
<iframe width="560" height="315" src="https://www.youtube.com/embed/4vXB2R8ybDE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
```

<iframe width="560" height="315" src="https://www.youtube.com/embed/4vXB2R8ybDE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


# Embedding a slide deck:  

# Reveal.js slides

Are you hosting Reveal.js slides on your GitHub Pages? Just paste the link into an iframe!

```html
<iframe width="720" height="480" frameborder="0" marginheight="0" marginwidth="0" src="https://ubc-lib-geo.github.io/gis-workshop-waml-template/content/slides/waml_github20"></iframe>
```

<iframe width="720" height="480" frameborder="0" marginheight="0" marginwidth="0" src="https://ubc-lib-geo.github.io/gis-workshop-waml-template/content/slides/waml_github20"></iframe>  



# Google slides

In Google Slides, go to File, Publish to Web, Embed and publish your slides. Copy the embed code then paste the code into your Markdown file:

```html
<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vT5hKsfivsyGgfRjsl0nKCHasqOuuZ3Rdoqm_OwVwPAWEo8HYDwx4RHy8LlZgYi1MSELhhUwh8ID3vZ/embed?start=false&loop=false&delayms=3000" frameborder="0" width="720" height="480"
allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
```

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vT5hKsfivsyGgfRjsl0nKCHasqOuuZ3Rdoqm_OwVwPAWEo8HYDwx4RHy8LlZgYi1MSELhhUwh8ID3vZ/embed?start=false&loop=false&delayms=3000" frameborder="0" width="720" height="480" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>




# From a digital repository:

```html
<iframe id="widgetPreview" frameBorder="0"  width="900px"  height="450px"  border="0px" style="border:0px solid white"  src="https://cudl.colorado.edu/luna/servlet/workspace/handleMediaPlayer?lunaMediaId=CUB~13~13~27~151317&embedded=true&cic=CUB%7E13%7E13&widgetFormat=javascript&widgetType=workspace&controls=1&nsip=1" ></iframe>  
```

<iframe id="widgetPreview" frameBorder="0"  width="900px"  height="450px"  border="0px" style="border:0px solid white"  src="https://cudl.colorado.edu/luna/servlet/workspace/handleMediaPlayer?lunaMediaId=CUB~13~13~27~151317&embedded=true&cic=CUB%7E13%7E13&widgetFormat=javascript&widgetType=workspace&controls=1&nsip=1" ></iframe>  


# A digital map:

**Basic Map**

We'll start with a basic map. Once you've saved any map in ArcGIS Online, you can get it's embed code by clicking Share. Because you can add HTML directly to Markdown, just paste the code provided by AGOL directly into the Markdown file:

```
<style>.embed-container {position: relative; padding-bottom: 80%; height: 0; max-width: 100%;} .embed-container iframe, .embed-container object, .embed-container iframe{position: absolute; top: 0; left: 0; width: 100%; height: 100%;} small{position: absolute; z-index: 40; bottom: 0; margin-bottom: -15px;}</style><div class="embed-container"><iframe width="500" height="400" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" title="CU Aerial Photo Collection (final)" src="//ucboulder.maps.arcgis.com/apps/Embed/index.html?webmap=68fe25f1df2149878fa88e15a4044d52&extent=-108.1261,38.2881,-101.4079,41.3297&zoom=true&previewImage=false&scale=true&disable_scroll=true&theme=light"></iframe></div>
```

<style>.embed-container {position: relative; padding-bottom: 80%; height: 0; max-width: 100%;} .embed-container iframe, .embed-container object, .embed-container iframe{position: absolute; top: 0; left: 0; width: 100%; height: 100%;} small{position: absolute; z-index: 40; bottom: 0; margin-bottom: -15px;}</style><div class="embed-container"><iframe width="500" height="400" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" title="CU Aerial Photo Collection (final)" src="//ucboulder.maps.arcgis.com/apps/Embed/index.html?webmap=68fe25f1df2149878fa88e15a4044d52&extent=-108.1261,38.2881,-101.4079,41.3297&zoom=true&previewImage=false&scale=true&disable_scroll=true&theme=light"></iframe></div>


**Embedding a StoryMap**

Want to embed a Story Map? Same exact procedure. Replace everything after `src=` and before </iframe> with the url for the Story Map:

```
<style>.embed-container {position: relative; padding-bottom: 80%; height: 0; max-width: 100%;} .embed-container iframe, .embed-container object, .embed-container iframe{position: absolute; top: 0; left: 0; width: 100%; height: 100%;} small{position: absolute; z-index: 40; bottom: 0; margin-bottom: -15px;}</style><div class="embed-container"><iframe width="500" height="400" frameborder="0" scrolling="yes" marginheight="0" marginwidth="0" title="CU Aerial Photo Collection (final)" src="https://storymaps.arcgis.com/stories/d3088d9b0e974dc7876e8a7d0ce90b0d"></iframe></div>
```


<style>.embed-container {position: relative; padding-bottom: 80%; height: 0; max-width: 100%;} .embed-container iframe, .embed-container object, .embed-container iframe{position: absolute; top: 0; left: 0; width: 100%; height: 100%;} small{position: absolute; z-index: 40; bottom: 0; margin-bottom: -15px;}</style><div class="embed-container"><iframe width="500" height="400" frameborder="0" scrolling="yes" marginheight="0" marginwidth="0" title="CU Aerial Photo Collection (final)" src="https://storymaps.arcgis.com/stories/d3088d9b0e974dc7876e8a7d0ce90b0d"></iframe></div>

*Note: if you want to enable scrolling, you'll need to set the following: `scrolling="yes"`. This is in the iframe code.

Presto!
