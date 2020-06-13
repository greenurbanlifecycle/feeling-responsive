---
layout: page-fullwidth
subheadline:  "Eier, Tomate & Paprika"
title:  "Menemen"
teaser: "Wanna create a responsive gallery to showcase your portfolio, recent photos or images? It's quite easy thanks to Foundation and <a href='http://foundation.zurb.com/docs/components/clearing.html'>Clearing Lightbox</a>."
categories:
    - food
    - tuerkischesFruehstueck
tags:
    - menemen
image:
   thumb: "TF_3.jpg"
---


## Zutaten
  <div class="row">
    <div class="small-12 columns b60">
      <p>
      <p class="subheadline"><span class="subheader">Eier, Tomate & Paprika</span></p>
      <a href="/food/tuerkischesFruehstueck/menemen/" title="Menemen"><img src="\images\Menemen_Zutaten.jpg" class="alignleft" width="150" height="150" alt="Blog of G.U.L.C."></a>
      Platzhalter Platzhalter Platzhalter Platzhalter Platzhalter Platzhalter Platzhalter Platzhalter Platzhalter Platzhalter Platzhalter Platzhalter Platzhalter Platzhalter Platzhalter Platzhalter Platzhalter Platzhalter Platzhalter Platzhalter Platzhalter Platzhalter Platzhalter Platzhalter Platzhalter Platzhalter Platzhalter Platzhalter Platzhalter Platzhalter Platzhalter Platzhalter Platzhalter Platzhalter Platzhalter Platzhalter Platzhalter Platzhalter Platzhalter Platzhalter Platzhalter Platzhalter Platzhalter Platzhalter Platzhalter Platzhalter Platzhalter Platzhalter
      </p>
    </div><!-- /.small-12.columns -->
  </div><!-- /.row -->


### Step 1

1. Make two images: a thumbnail and a big image.
2. Name the thumbnail *gallery-image-thumb.jpg* and...
3. ...name the big *gallery-image.jpg*.
4. Place them in the *images*-folder.


### Step 2

Define the big version in frontmatter,  

~~~
gallery:
    - image_url: gallery-image.jpg
~~~

If you like captions, give each image a caption:

~~~
gallery:
    - image_url: gallery-image.jpg
       caption: Starting Page with huge One Logo
~~~

### Step 3

Add the include whereever you want in your content with `{% raw %}{% include gallery %}{% endraw %}`.

{% include alert info='Have a look at this example-entry. And have a look into the images-folder. :)' %}











## Other Post Formats
{: .t60 }
{% include list-posts tag='post format' %}



 [1]: http://foundation.zurb.com/docs/components/clearing.html
 [2]: http://foundation.zurb.com/docs/components/block_grid.html
 [3]: {{ site.url }}{{ site.baseurl }}/design/page/
 [4]: {{ site.url }}{{ site.baseurl }}/design/page-fullwidth/
