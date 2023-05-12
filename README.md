<param ve-config 
       title="Essay Title"
       author="Author"
       banner="https://iiif.wellcomecollection.org/image/V0044770/full/1338%2C/0/default.jpg"
       layout="vertical">
       
First, go ahead and enter your essay title in the "title" field above, and your name as you'd like it to appear in "author". For the banner image, you can pick anything you already have permissions to use. The image will be automatically scaled to fit the field (or you can crop/create an image 1200 by 400 pixels)

## This is a quick Markdown tutorial. Two hashes precede a heading. You can use these headings to divide sections of your essay.

*This makes things italics*. 

This is how you add a footnote. [^1]

[This is how you add a link](https://www.juncture-digital.org/KatherineMEnright/speciesstories/)

This is how you add a mouse-over information panel from Wiki data: <span eid="Q170662">Mangosteen</span>
You can find the wikidata IDs by searching for proper nouns (including relevant background information) [here](https://www.wikidata.org/wiki/Wikidata:Main_Page). The ID is the series of digits following the letter Q.

##Adding Images
       
You can use the QID tag within a sentence. For example: The <span eid="Q170662">mangosteen</span> is a non-native fruit found in Singapore.
<param ve-image 
       url="https://iiif.wellcomecollection.org/image/V0044770/full/1338%2C/0/default.jpg"
       title="Mangosteen Photograph" 
       description="A mangosteen plant (Garcinia mangostana): fruiting branch and halved fruit. Photograph. Wellcome Collection.">
       
<span eid="Q271648">Marianne North</span> painted this painting of a 'Singapore monkey' amongst mangosteen fruits in 1875.
<param ve-image 
       url="https://d3d00swyhr67nd.cloudfront.net/w1200h1200/collection/LSW/RBGM/LSW_RBGM_MN_CD6_577-001.jpg"
       title="Flowers and Fruit of the Mangosteen, and a Singapore Monkey" 
       description="Held by Kew Gardens."
       license="CC BY-NC">
       
These are both examples of images added *from urls*. This is the preferred method. However, there might be some images you have to upload yourself. That's totally fine! Ideally, these files should be *as small as possible* and only .jpg or .png files will work. You should create a folder in your repository called "media" and upload the file there. 
       
## Map

Mangosteens are found in Singapore. This takes a base map and sets the center to the Wiki ID for Singapore.
<param ve-map center="Q334" zoom="11" prefer-geojson>

## Multiple viewers

Multiple viewers may be defined for a single paragraph of text.  The first viewer defined is displayed as the default viewer.  
Others are selectable using icons displayed in the top right margin of the paragraph.
<param ve-image 
       url="https://iiif.wellcomecollection.org/image/V0044770/full/1338%2C/0/default.jpg"
       label="Mangosteen Photograph" 
       description="A mangosteen plant (Garcinia mangostana): fruiting branch and halved fruit. Photograph. Wellcome Collection."
       license="public domain">
<param ve-map center="Q334" zoom="11" prefer-geojson>

# References

[^1]: Citation. Make sure you include the colon or this won't work!
