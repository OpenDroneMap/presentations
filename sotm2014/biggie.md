OpenDroneMap

---

1st, a computer vision / Structure from Motion intro:

---

photosynth:
https://www.youtube.com/watch?v=s-DqZ8jAmv0
https://www.youtube.com/watch?v=4LxlhoemR3A

---

spotscale:
http://spotscale.com/
http://showroom.spotscale.com/

---

How to use Mapillary:
https://www.youtube.com/watch?v=yIUgBsHr2O4

---

How to really use Mapillary:
https://www.youtube.com/watch?v=ruxnjzvUCWI

---

Quick diversion:
![](https://raw.githubusercontent.com/OpenDroneMap/OpenDroneMap-Intro/gh-pages/img/geohipster.png)

---

<em>"While the last decade has been dominated by the growing hegemony of the global base map, mapping will swing now for a while towards the principle of mapping the world, one organic pixel at a time. 2014 is the beginning of artisanal satellite mapping, where we discover the value in 1-inch pixels from personally and professionally flown unmanned aerial systems (drones)."<em>

---

![](https://upload.wikimedia.org/wikipedia/commons/thumb/f/f8/Group_photo_of_aerial_demonstrators_at_the_2005_Naval_Unmanned_Aerial_Vehicle_Air_Demo.jpg/1024px-Group_photo_of_aerial_demonstrators_at_the_2005_Naval_Unmanned_Aerial_Vehicle_Air_Demo.jpg)

---

Not this:

---

![](https://raw.githubusercontent.com/smathermather/OpenDroneMap/gh-pages/img/notmydrone.png)

---

More like this:

---

![](http://upload.wikimedia.org/wikipedia/commons/9/9a/Inview_UAV_medium.jpg)

---

or this:

---

![](https://raw.githubusercontent.com/smathermather/OpenDroneMap/gh-pages/img/sensefly.png)

---

Why are small UAS's (ahem drones) so cool?

---

much data.

---

for example from sensefly website, super-high resolution images-- 5cm / 2"

---

![](https://raw.githubusercontent.com/smathermather/OpenDroneMap/gh-pages/img/lod.png)

---

Can support other mapping efforts--

prior art (OpenStreetMap use):

---

![](https://raw.githubusercontent.com/smathermather/OpenDroneMap/gh-pages/img/sudekum.png)

---

But do we have to fly? What if we start by walking?

---

![](https://raw.githubusercontent.com/smathermather/OpenDroneMap/gh-pages/img/cameras.png)

---

![](https://raw.githubusercontent.com/smathermather/OpenDroneMap/gh-pages/img/pc.png)

---

For this we need not SenseFly, but...

---

Lots of FOSS.  And super super high resolution. Like really high. Like, uh, 0.01' pixels:

---

![](https://smathermather.files.wordpress.com/2014/04/apt_ortho.png)

---

Wait-- how did we get here?

---

Take some photos:

---

![](https://raw.githubusercontent.com/smathermather/OpenDroneMap/gh-pages/img/tape 001.jpg)

---

![](https://raw.githubusercontent.com/smathermather/OpenDroneMap/gh-pages/img/tape 002.jpg)

---

![](https://raw.githubusercontent.com/smathermather/OpenDroneMap/gh-pages/img/tape 003.jpg)

---

![](https://raw.githubusercontent.com/smathermather/OpenDroneMap/gh-pages/img/tape 004.jpg)

---

![](https://raw.githubusercontent.com/smathermather/OpenDroneMap/gh-pages/img/tape 005.jpg)

---

![](https://raw.githubusercontent.com/smathermather/OpenDroneMap/gh-pages/img/tape 006.jpg)

---

![](https://raw.githubusercontent.com/smathermather/OpenDroneMap/gh-pages/img/tape 007.jpg)

---

![](https://raw.githubusercontent.com/smathermather/OpenDroneMap/gh-pages/img/tape 008.jpg)

---

![](https://raw.githubusercontent.com/smathermather/OpenDroneMap/gh-pages/img/tape 009.jpg)

---

![](https://raw.githubusercontent.com/smathermather/OpenDroneMap/gh-pages/img/tape 010.jpg)

---

![](https://raw.githubusercontent.com/smathermather/OpenDroneMap/gh-pages/img/tape 011.jpg)

---

![](https://raw.githubusercontent.com/smathermather/OpenDroneMap/gh-pages/img/tape 012.jpg)

---

This is all about stereo vision (multi-view stereo vision, to be precise):
![](http://www.rickgibson.net/Images/intro/viewmaster.jpg)

---


![](https://www.cs.cornell.edu/~snavely/bundler/images/Colosseum.jpg)

---

![](http://smathermather.files.wordpress.com/2014/02/cmvs.png?w=698&h=313)

---

![](http://www.di.ens.fr/pmvs/images/hall-2.jpg)

---

![](http://www.lancaster.ac.uk/staff/jamesm/software/sfm_georef_in_use.png)

---

![](https://raw.githubusercontent.com/smathermather/OpenDroneMap/gh-pages/img/ldpc.png)

---

![](https://raw.githubusercontent.com/smathermather/OpenDroneMap/gh-pages/img/dense_cloud1.png)

---

![](https://raw.githubusercontent.com/smathermather/OpenDroneMap/gh-pages/img/dense_cloud2.png)

---

![](https://raw.githubusercontent.com/smathermather/OpenDroneMap/gh-pages/img/dense_cloud3.png)

---

![](https://raw.githubusercontent.com/smathermather/OpenDroneMap/gh-pages/img/mesh1.png)

---

![](https://raw.githubusercontent.com/smathermather/OpenDroneMap/gh-pages/img/mesh2.png)

---

![](https://raw.githubusercontent.com/smathermather/OpenDroneMap/gh-pages/img/textured_model.png)

---

![](https://raw.githubusercontent.com/smathermather/OpenDroneMap/gh-pages/img/textured_surface_w_orig_photos.png)

---

![](https://raw.githubusercontent.com/smathermather/OpenDroneMap/gh-pages/img/apt-ortho2.png)

---

Where from here?

---

Initial Steps

* Play with drone processing techniques
* Improve documentation / tutorials on tools
* Improve usability / integration of tools
* Participate, augment, and grow existing efforts (e.g. UAViators)

---

Other Steps

* Provide hosted services for processing
* Improve georeferencing tools / processes
* Find synergies with OSM and
* Provide hosted storage / retrieval / sharing portals

---

![](https://raw.githubusercontent.com/hobu/greyhound/master/pointcloud.png)

---

Limited links list

Structure from Motion (SfM)
* http://flightriot.com/post-processing-software/
* http://wedidstuff.heavyimage.com/index.php/2013/07/12/open-source-photogrammetry-workflow/
* http://www.lancaster.ac.uk/staff/jamesm/software/sfm_georef.htm
* http://www.agisoft.ru/products/photoscan/professional/
* http://www.agisoft.ru/products/photoscan/standard/
* http://ccwu.me/vsfm/

---

Small Unmanned Vehicles (sUAVs)
* http://uaviators.org/
* https://www.mapbox.com/blog/processing-drone-imagery/
* http://conservationdrones.org/

---

Point Clouds
* https://github.com/hobu/greyhound
* http://www.pdal.io/

---

Recruiting
* funding
* people's time / thought
* demonstrable projects
* user testing

---

http://smathermather.github.io/OpenDroneMap

---

![](http://smathermather.files.wordpress.com/2013/12/uas_footprints.png?w=368&h=213)

---

![](http://smathermather.files.wordpress.com/2013/12/uas_individual_actual_overlay.png?w=1024&h=592)

---

![](http://smathermather.files.wordpress.com/2013/12/drone_scribbles.png?w=663&h=629)

---
