# Project2_Lede

# Title: The bridge

# Short description of what I tried to accomplish

This project began with a complete failure. My first idea was to look at rare earth mining with a focus on China. I found good data (or so it seemed) and thought it would be great to showcase all the rare earth deposits around the world: https://mrdata.usgs.gov/pp1802/.
I spent three days working with the dataset in QGIS, trying to put everything on a map. I needed to reorganize the data, explode geometries, delete some entries, etc. After a while, I realized that this dataset was actually not that helpful. It was difficult to make all the data points visible, and I started to question the point of it all — especially since China, as the biggest producer, is also sourcing rare earths from other places.
I gave up on the whole idea and moved on to something else. At least I learned a lot about QGIS — even though I couldn't get many things to work.

I decided to pivot to another idea about infrastructure projects in China. It's supposed to be a long-term project I actually want to work on, but I thought I could start small and see what my new skills could bring to the table. I tried to focus on the sheer size of the bridge and its location to show the purpose of the project.

# Short description of your findings/ Overview of the data analysis process
I started with deep-dive research to find a suitable infrastructure project and eventually chose a bridge in Shandong, East China. Based on the material I found, I tried to highlight the sheer dimensions of the project and its geographic context.

Once again, the map became a huge project in itself. I drew the bridge manually using geojson.io.

I added cities and provinces using Overpass Turbo, then imported them into Datawrapper. A process that turned out to be more difficult than expected. For instance, I needed to know the correct admin_level for each city, and had to figure out which language version (English, Chinese or pinyin) to use for each name.

The biggest challenge was visualizing the railway network. Especially identifying which high-speed rail lines already exist and where the new ones will be built. I spent another three days trying to add those rail trails.

Everyone suggests QGIS as the quick solution for these tasks. I found this data: https://data.humdata.org/dataset/hotosm_chn_railways But for me, it ended up being a rabbit hole full of bugs and failed exports. The data turned out to be more complicated than expected and was also missing key information. For example I only needed the high-speed network, not all rail lines. I wanted to isolate one province, but for whatever reason, changing its color wouldn’t work.

I spent endless hours in Datawrapper, QGIS and Wikipedia and then finally found this post, which nearly made me cry:  https://www.datawrapper.de/blog/weekly-china-high-speed-rail-geojson-import

After importing those rail lines, I repeated the same  process for the Yellow River. But again, the full river was too much data for Datawrapper, which meant back to QGIS and realizing after a while that it didn't work really.

In the end all was done but not really satisfying.

# A section about what new skills, approaches, etc you used, or where you grew the most during the project

What looks easy in class rarely works that smoothly in real life. I realized, just as we were told in class, that you either need really good data or you have to make it look great. So I guess I wanted too much. Good data is really very hard to find if you need to find it yourself. And mine was mostly incomplete or lacked the necessary attributes etc.. In this project, I explored many new platforms, including Chinese ones and even Wikipedia, which I had never used in such detail before. I also learned to search for data on GitHub. One major takeaway: Managing my frustration is part of the process.

I used Figma instead of Illustrator, both tools are new to me. But Figma seems a bit easier for quick intuitive tasks. So I learned a little bit about its settings. I learned a ton about QGIS, but mostly that I don't know enough about it yet to work with it efficiently. 

I developed a better understanding of where to get Geojsons, what kind of editing is possible within Geojsons versus in Datawrapper and what Overpass Turbo is used for.

In terms of design I used the template for scrolly-stories. I am not sure I really understand all/most of the details of that html/css template.  

# A section about things you tried to do or wanted to do but did not have the skills/time (but if you have more time you might do)

Some things (many) didn’t turn out as I had hoped. The image quality isn’t high enough. I tried to improve it, but couldn’t find a better solution. The map could also be more informative, and there’s a slight jump between images when scrolling during the transition from picture 1 to 2 and from 3 to 4. It might be due to my internet connection, but the images also seem to load with a slight delay.

Text-wise, this clearly isn’t what I envision for a long-term project. For that, I would want to do proper on-the-ground research and reporting. This piece is more of a starting point to explore how to work with infrastructure data and try out a format that might still be an interesting, quick read.

Another technical issue I couldn’t solve: the display across devices. On my computer, the layout looks fine, but on my phone, the images aren’t shown well. Strangely enough, the font size feels perfect on mobile, but too small on desktop. I didn’t dare to change the html or css too much, afraid I might break something else in the process.


