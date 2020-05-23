---
layout: page
subheadline:  "Food"
title:  "Türkisches Frühstück"
teaser: "In Deutschland unserer Meinung nach viel zu wenig verbreitet ist die türkische Frühstückskultur. Wie ich mittlerweile durch unsere Reisen in die Türkei sowie unsere Rituale am Wochenende gerlernt habe, ein reichhaltiges und abwechslungsreiches Frühstück das jeder mal ausprobieren sollte. Am besten in Ruhe mit ausreichend Zeit und in guter Gesellschaft:-)"
categories:
    - design
tags:
    - post format
header:
    image_fullwidth: TF_3.jpg 
thumb: "TF_3.jpg"
gallery:
    - image_url: TF_1.jpg
      caption: Wo gibt es so frischen Honig?
      caption_url: ""
    - image_url: TF_2.jpg
      caption: Great images by Unsplash.com
    - image_url: TF_3.jpg
      caption: Die Auswahl kann überwältigend sein.
    - image_url: TF_4.jpg
      caption: Wo gibt es so frischen Honig?
    - image_url: TF_5.jpg
      caption: Great images by Unsplash.com
    - image_url: TF_6.jpg
      caption: Die Auswahl kann überwältigend sein.
---

## Galerie
Um euch eine schnelle Übersicht zu geben haben wir ein paar Bilder in der Galerie hinterlegt. Unten findet ihr außerdem Links zu allen Rezepten. 

**Guten Appetit, Afiyet olsun!**

{% include gallery %}


## Rezepte

`{% raw %}{% include gallery %}{% endraw %}` lets you easily embed a gallery into your post. To use the gallery-include...


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
