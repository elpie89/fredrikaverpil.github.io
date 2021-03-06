---
layout: portfolioitem
title: Le Mont Saint Michel
preview: saintmichel/saintmichel_preview.jpg
---
<!--more-->

[Mont Saint Michel project page](http://www.holoforge.io/work/history-and-culture-through-mixed-reality)

[Mont Saint Michel - Microsoft page](https://www.microsoft.com/inculture/arts/le-mont-saint-michel-mixed-reality/)

 _"The Mont Saint-Michel: Digital perspectives on the model"_ a HoloLens experience celebrating French culture and innovation: The goal of the exhibit is to use mixed reality technology in a way that empowers the Musée des Plans-Reliefs to unlock a more vital kind of storytelling.

<a href="{{ site.baseurl }}/assets/portfolio/saintmichel/visualcatalog.jpg" ><img src="{{ site.baseurl }}/assets/portfolio/saintmichel/visualcatalog.jpg" alt="Visual Catalog" width="1280"/>

Here you can find the 3 official Microsoft Today in Technology episodes.

<iframe width="425" height="310" src="https://www.youtube.com/embed/o30fGoDy660" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<iframe width="425" height="310" src="https://www.youtube.com/embed/-uv0Aa-o9xo" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<iframe width="425" height="310" src="https://www.youtube.com/embed/x8uskAYFvAk" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


The biggest challenge on this project was to find a way to display a 3d scanned object of 13,5 million polygons inside a Hololens application
In order, the textures were gorgeous and completely non-optimized (21 Texture of 16Kx16K resolution)


<img src="{{ site.baseurl }}/assets/portfolio/saintmichel/original.jpg" alt="Original model" width="600"/> | <img src="{{ site.baseurl }}/assets/portfolio/saintmichel/textures.jpg" alt="Textures" width="600"/>

<img src="{{ site.baseurl }}/assets/portfolio/saintmichel/final.jpg" alt="Acchieved result" width="1280"/>

This challenge has been accomplished using a combination of Maya, ZBrush, Sympligon and Turtle Bake Renderer  
I'm proud of this job because it was originally estimated on 4 weeks of full work for one man.
The original idea was to model everything in low poly(crazy).
Thanks to this workflow I reduced the modeling time in 2 days and 3 other days were used to unwrap properly the UVs

I will write a more detailed article in the next days, on how to face this type of problem.

<img src="{{ site.baseurl }}/assets/portfolio/saintmichel/mont.gif" alt="Textures" width="1280"/>

As always I have been responsible for:
- Performance check, be sure that the application runs at 60 fps
- Management of stage assistant, and be sure his work was properly integrated into the application
- Instruct the UI designer and Motion designer of a proper workflow to reduce production time
- Creation of Unity utilities, to leave freedom to the artist on the artistic side of the project
- Integration of custom FX like the Point Cloud Renderer 
