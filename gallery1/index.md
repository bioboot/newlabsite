---
layout: page
title: Image and Movie Gallery
---

A brief sampling of [images](#image) and [animations](#movie) arising from our recent research. Click on an individual image for more details and a larger view. Mouse over movies/videos for play/pause and full-screen options.


<a name="image"></a>

<div>
      {% for image in site.static_files %}
          {% if image.path contains 'img/slider' %}
              {% unless image.path contains 'thumb' %}

                  <a href="{{ site.baseurl }}{{ image.path }}" class="fancybox" rel="pubimg">
                  <img src="{{ site.baseurl }}{{ image.path }}" class='resizegallery imghover' alt="image"/>
                  </a>

              {% endunless %}
          {% endif %}
      {% endfor %}
</div>


<br />

<a name="movie"></a>

## Movies and animations

<div>
  <center>
  
  <!-- <object width="300" height="225">
  <param name="allowfullscreen" value="true" /><param name="allowscriptaccess" value="always" /><param name="movie" value="http://vimeo.com/moogaloop.swf?clip_id=10426396&amp;server=vimeo.com&amp;show_title=0&amp;show_byline=0&amp;show_portrait=0&amp;color=00adef&amp;fullscreen=1" />
  <embed src="http://vimeo.com/moogaloop.swf?clip_id=10426396&amp;server=vimeo.com&amp;show_title=0&amp;show_byline=0&amp;show_portrait=0&amp;autoplay=1&amp;loop=1&amp;color=00adef&amp;fullscreen=1" type="application/x-shockwave-flash" allowfullscreen="true" allowscriptaccess="always" width="300" height="225">
  </embed>
  </object><p><a href="http://vimeo.com/10426396">Ras accelerated molecular dynamics simulation</a>.
  </p>
  
  <br /><br />
  -->

  <iframe src="https://player.vimeo.com/video/10426396?loop=1&byline=0" width="640" height="480" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
  <p><a href="https://vimeo.com/10426396">Ras accelerated molecular dynamics simulation</a>.</p>

<br /><br />

  <iframe src="https://player.vimeo.com/video/27214521?loop=1&byline=0" width="640" height="188" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
  <p><a href="https://vimeo.com/27214521">Integrated Biomolecular Trajectory Analysis with Bio3D</a>.</p>

<br /><br />

  <iframe src="https://player.vimeo.com/video/33052467?loop=1&byline=0" width="640" height="292" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen>
  </iframe>
  <p><a href="https://vimeo.com/33052467">Surface mapped electrostatic potentials of the kinesin family</a>.</p>

<br /><br />

  <iframe src="https://player.vimeo.com/video/176062431?loop=1&byline=0" width="640" height="794" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen>
  </iframe>
  <p><a href="https://vimeo.com/176062431">Kinesin-1 electrostatic features upon nucleotide cycling</a>.</p>

<br /><br />

  <iframe src="https://player.vimeo.com/video/32016374?loop=1&byline=0" width="640" height="676" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
  <p><a href="https://vimeo.com/32016374">Rab GTPases</a>.</p>

<br /><br />

  <iframe src="https://player.vimeo.com/video/60216336?loop=1&byline=0" width="640" height="726" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
  <p><a href="https://vimeo.com/60216336">Kinesin structure ensemble classified</a>.</p>

<br /><br />

  <iframe src="https://player.vimeo.com/video/24146793?loop=1&byline=0" width="640" height="328" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
  <p><a href="https://vimeo.com/24146793">Ras ensemble fragment mapping</a>.</p>

<br /><br />

  <iframe src="https://player.vimeo.com/video/17350409?loop=1&byline=0" width="640" height="512" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
  <p><a href="https://vimeo.com/17350409">Computational Drug Screening</a>.</p>

<br /><br />

  <iframe src="https://player.vimeo.com/video/10765434?loop=1&byline=0" width="640" height="384" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
  <p><a href="https://vimeo.com/10765434">Proline racemase from T. cruzi</a>.</p>

<br /><br />

  <iframe src="https://player.vimeo.com/video/16893643?loop=1&byline=0" width="640" height="584" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
  <p><a href="https://vimeo.com/16893643">Kinesin-Tubulin Association With Brownian Dynamics</a>.</p>

<br /><br />

  <iframe src="https://player.vimeo.com/video/5239966?loop=1&byline=0" width="640" height="248" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
  <p><a href="https://vimeo.com/5239966">Kinesin electrostatics</a>.</p>

<br /><br />

  <iframe src="https://player.vimeo.com/video/10537639?loop=1&byline=0" width="640" height="480" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
  <p><a href="https://vimeo.com/10537639">Microtubule Electrostatics</a>.</p>

<br /><br />

  <iframe src="https://player.vimeo.com/video/15853775?loop=1&byline=0" width="640" height="360" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
  <p><a href="https://vimeo.com/15853775">MTBD-tubulin encounter complexes from BD simulation</a>.</p>

  </center>
			
</div>



