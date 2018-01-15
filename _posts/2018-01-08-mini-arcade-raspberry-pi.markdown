---
layout: post
title:  "Mini Arcade Raspberry Pi - part 1"
date:   2018-01-08 16:16:01 -0600
categories: retrogaming arcade raspberrypi kodi diy
excerpt_separator: <!--more-->
---
<center><img src="{{ site.baseurl }}/images/20180108_2.jpg"></center>

Hi Everyone. It's been a while since I started to think about doing a small [RetroPie](https://retropie.org.uk/ "Retropie Homepage") project. I was always fascinated by real arcade machines as a child, and they were always sort of a "forbidden fruit" back then. So I decided to do my own. <!--more--> Fast forward two decades and I have a Raspberry Pi 2 in my living room, and from time to time I do spin up some old school classics, but it is, somehow, limiting. There is just something about having to pick up a modern looking controller and pairing via bluetooth and restarting [Kodi](https://kodi.tv "Kodi Homepage") (which is what is usually on on the Pi) that breaks down the will to revive the good old days playing NES games on a [NES Sega Mega Drive (Genesis) looking clone](http://ultimateconsoledatabase.com/famiclones/megapower.htm) while everyone was already in the Playstation world.


A couple of weeks ago, I stumbled upon the recent phenomenon of nano arcade machines and ended up buying [this one from Amazon](https://www.amazon.de/gp/product/B01GKE0XRE/ref=oh_aui_detailpage_o03_s00?ie=UTF8&psc=1). I have watched reviews of many different types, and it was not a surprise that it was filled with > 200 games, but they were mostly poor clones of classic NES ones. Names were different, colors were off, often game modes were hidden and, equally important, music and sound effects were replaced by some annoying low quality ones. Retro experience was *way off*.

Under this circumstances I have decided it would be a great idea and a good project to embed a latest version of the Raspberry Pi (3) on it, not only to become a trully portable retro gaming machine but, equally importantly, my portable media player box. We plan on doing some travelling this year, and being able to carry your already configured kodi installation on such a small and iconic form factor, that supports both wired (for my house) and wireless connectivity (for other places like Hostels or Airbnb) is a big plus.

The small issue all this planning has is just one: I barely have any experience in anything electrical, including solding and de-solding (more on this later). Here goes an initial list of requirements:
* Wireless Connectivity
* Bluetooth Connectivity
* Wired (ethernet) Connectivity
* HDMI-out
* USB-out (at least one)
* Speaker
* Small screen (using current one, if possible by any means)
* Joystick and 6 buttons + Select + Start.
* Volume Wheel/Mechanism
* Battery

So, this is a pretty big list. Ideally the in-device screen would work with the controllers via GPIO/USB, and would go down as soon as the HDMI connection is on. 6 button controlls would be interesting for an array of emulators, not limiting entirely to the really old consoles since we're running a Raspberry Pi 3. Speaking of which, initial thoughts went to Raspberry Pi W Zero, but there seems to be a good ammount of space inside and we could use the extra performance for good emulation with bluetooth controllers and HD video reproducion. Here follow a couple of pictures of the insides of it and some rough size schematics.

So, there will be various challenges, but the biggest one will be to research for material, try to find a fitting screen and overall soldering and desoldering components. But best approach is probably try as much as possible to not have to solder anything at all.

<div class="m-p-g">
    <div class="m-p-g__thumbs">
        <div data-google-image-layout data-max-width="200">
            <img class="m-p-g__thumbs-img" src="{{ site.baseurl }}/images/IMG_20180113_174517_2.jpg" data-full="{{ site.baseurl }}/images/IMG_20180113_174517_1.jpg"/>
        </div>
        <div data-google-image-layout data-max-width="200">
            <img class="m-p-g__thumbs-img" src="{{ site.baseurl }}/images/IMG_20180113_174528_2.jpg" data-full="{{ site.baseurl }}/images/IMG_20180113_174528_1.jpg"/>
        </div>
        <div data-google-image-layout data-max-width="200" >
            <img class="m-p-g__thumbs-img" src="{{ site.baseurl }}/images/IMG_20180113_174551_2.jpg" data-full="{{ site.baseurl }}/images/IMG_20180113_174551_1.jpg"/>
        </div>
    </div>
    <div class="m-p-g__fullscreen"></div>
</div>

So stay tuned for the next posts and feel free to give tips and recommendations.

