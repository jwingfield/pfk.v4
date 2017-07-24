{% include pfk.css %}
{% include bootstrap.html %}
{% include top-nav.html %}
<div id="myCarousel" class="carousel slide" data-ride="carousel">
  <!-- Indicators -->
  <ol class="carousel-indicators">
    <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
    <li data-target="#myCarousel" data-slide-to="1"></li>
    <li data-target="#myCarousel" data-slide-to="2"></li>
  </ol>

  <!-- Wrapper for slides -->
  <div class="carousel-inner">
    <div class="item active">
      <img src="pics/pic1.jpg" alt="Los Angeles">
        <div class="carousel-caption">
          <h3>On A Rug</h3>
        <p>Visiting Nana &amp; Papa</p>
      </div>
    </div>

    <div class="item">
      <img src="pics/pic2.jpg" alt="Chicago">
        <div class="carousel-caption">
          <h3>Shades</h3>
        <p>LA is always so much fun!</p>
      </div>
    </div>

    <div class="item">
      <img src="pics/pic3.jpg" alt="New York">
        <div class="carousel-caption">
          <h3>Cheeky</h3>
        <p>Dude</p>
      </div>
    </div>
  </div>

  <!-- Left and right controls -->
  <a class="left carousel-control" href="#myCarousel" data-slide="prev">
    <span class="glyphicon glyphicon-chevron-left"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="right carousel-control" href="#myCarousel" data-slide="next">
    <span class="glyphicon glyphicon-chevron-right"></span>
    <span class="sr-only">Next</span>
  </a>
</div>
