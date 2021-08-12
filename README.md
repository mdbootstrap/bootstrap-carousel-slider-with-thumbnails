# Bootstrap Carousel Slider with Thumbnails - examples & tutorial

Responsive Carousel Slider with Thumbnails built with the latest Bootstrap 5. An improved version of the standard Bootstrap Carousel Image Gallery additionally equipped with thumbnails.

To learn more read [Carousel Docs](https://mdbootstrap.com/docs/standard/components/carousel/).

## Basic example

```html
<!-- Carousel wrapper -->
<div
  id="carouselExampleIndicators"
  class="carousel slide carousel-fade"
  data-mdb-ride="carousel"
>
  <!-- Slides -->
  <div class="carousel-inner mb-5">
    <div class="carousel-item active">
      <img
        src="https://mdbootstrap.com/img/Photos/Slides/img%20(88).jpg"
        class="d-block w-100"
        alt="..."
      />
    </div>
    <div class="carousel-item">
      <img
        src="https://mdbootstrap.com/img/Photos/Slides/img%20(121).jpg"
        class="d-block w-100"
        alt="..."
      />
    </div>
    <div class="carousel-item">
      <img
        src="https://mdbootstrap.com/img/Photos/Slides/img%20(31).jpg"
        class="d-block w-100"
        alt="..."
      />
    </div>
  </div>
  <!-- Slides -->

  <!-- Controls -->
  <button
    class="carousel-control-prev"
    type="button"
    data-mdb-target="#carouselExampleIndicators"
    data-mdb-slide="prev"
  >
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button
    class="carousel-control-next"
    type="button"
    data-mdb-target="#carouselExampleIndicators"
    data-mdb-slide="next"
  >
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
  <!-- Controls -->

  <!-- Thumbnails -->
  <div class="carousel-indicators" style="margin-bottom: -20px;">
    <button
      type="button"
      data-mdb-target="#carouselExampleIndicators"
      data-mdb-slide-to="0"
      class="active"
      aria-current="true"
      aria-label="Slide 1"
      style="width: 100px;"
    >
      <img
        class="d-block w-100"
        src="https://mdbootstrap.com/img/Photos/Others/Carousel-thumbs/img%20(88).jpg"
        class="img-fluid"
      />
    </button>
    <button
      type="button"
      data-mdb-target="#carouselExampleIndicators"
      data-mdb-slide-to="1"
      aria-label="Slide 2"
      style="width: 100px;"
    >
      <img
        class="d-block w-100"
        src="https://mdbootstrap.com/img/Photos/Others/Carousel-thumbs/img%20(121).jpg"
        class="img-fluid"
      />
    </button>
    <button
      type="button"
      data-mdb-target="#carouselExampleIndicators"
      data-mdb-slide-to="2"
      aria-label="Slide 3"
      style="width: 100px;"
    >
      <img
        class="d-block w-100"
        src="https://mdbootstrap.com/img/Photos/Others/Carousel-thumbs/img%20(31).jpg"
        class="img-fluid"
      />
    </button>
  </div>
  <!-- Thumbnails -->
</div>
<!-- Carousel wrapper -->
```

#### Much more examples and a detailed description can be found at [📄 Carousel Slider with Thumbnails documentation page](https://mdbootstrap.com/docs/standard/extended/carousel-with-thumbnails/)
