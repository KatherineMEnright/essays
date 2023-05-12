<param ve-config 
       title="Essay Title"
       author="Author"
       banner="https://iiif.wellcomecollection.org/image/V0044770/full/1338%2C/0/default.jpg"
       layout="vertical">
       
## This is a quick Markdown tutorial. Two hashes precede a heading
*This makes things italics*. 

This is how you add a footnote. [^1]
<param ve-image title="Roasted Coffee Beans" url="https://upload.wikimedia.org/wikipedia/commons/c/c5/Roasted_coffee_beans.jpg">

[This is how you add a link](https://www.juncture-digital.org/KatherineMEnright/speciesstories/)
<param ve-image 
       manifest="https://iiif.wellcomecollection.org/image/V0044770/full/1338%2C/0/default.jpg"
       label="Mangosteen Photograph" 
       description="A mangosteen plant (Garcinia mangostana): fruiting branch and halved fruit. Photograph. Wellcome Collection.">

This is how you add a mouse-over information panel from Wiki data: <span eid="Q170662">Mangosteen</span>
You can find the wikidata IDs by searching for proper nouns (including relevant background information) [here](https://www.wikidata.org/wiki/Wikidata:Main_Page). The ID is the series of digits following the letter Q.
       
You can use this within a sentence. For example: The <span eid="Q170662">Mangosteen</span> is a non-native fruit found in Singapore.
<param ve-image 
       manifest="https://iiif.wellcomecollection.org/image/V0044770/full/1338%2C/0/default.jpg"
       label="Mangosteen Photograph" 
       description="A mangosteen plant (Garcinia mangostana): fruiting branch and halved fruit. Photograph. Wellcome Collection.">
       
Marianne North painted this painting of a 'Singapore monkey' amongst mangosteen fruits in 1875.
<param ve-image
       title="Image comparison of the canopy of a dragon tree (_Dracaena draco_) with a classical Greek depiction of the dragon Ladon."
       url="https://free.iiifhosting.com/iiif/7e103f8b67bc1ce1be0a738a6a34265de93fe18ad5978f48c076da1da1fbf636/info.json"
       curtain="true"
       fit="contain"
       ref="1">
       
## Map

Mangosteens are found in Singapore.
<param ve-map center="Q334" zoom="11" prefer-geojson>

## Multiple viewers

Multiple viewers may be defined for a single paragraph of text.  The first viewer defined is displayed as the default viewer.  
Others are selectable using icons displayed in the top right margin of the paragraph.
<param ve-image 
       url="https://iiif.wellcomecollection.org/image/V0044770/full/1338%2C/0/default.jpg"
       label="Mangosteen Photograph" 
       description="A mangosteen plant (Garcinia mangostana): fruiting branch and halved fruit. Photograph. Wellcome Collection."
       license="public domain">
<param ve-image 
       url="https://d3d00swyhr67nd.cloudfront.net/w1200h1200/collection/LSW/RBGM/LSW_RBGM_MN_CD6_577-001.jpg"
       label="Flowers and Fruit of the Mangosteen, and a Singapore Monkey" 
       description="Held by Kew Gardens."
       license="CC BY-NC">
<param ve-map center="Q334" zoom="11" prefer-geojson>

# References

[^1]: Citation. Make sure you include the colon or this won't work!
