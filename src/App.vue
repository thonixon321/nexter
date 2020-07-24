<template>
  <div
    class="container"
    id="app"
  >
    <div class='sidebar'>
      <button class='nav-btn'></button>
    </div>

    <header class='header'>
      <img
        src='./assets/img/logo.png'
        alt='Nexter logo'
        class='header__logo'
      >
      <h3 class='heading-3'>Your own home:</h3>
      <h1 class='heading-1'>The ultimate personal freedom
      </h1>
      <button class='btn header__btn'>View our properties</button>
      <div class='header__seenon-text'>As seen on</div>
      <div class='header__seenon-logos'>
        <img
          src='./assets/img/logo-bbc.png'
          alt='Seen on logo 1'
        >
        <img
          src='./assets/img/logo-forbes.png'
          alt='Seen on logo 2'
        >
        <img
          src='./assets/img/logo-techcrunch.png'
          alt='Seen on logo 3'
        >
        <img
          src='./assets/img/logo-bi.png'
          alt='Seen on logo 4'
        >
      </div>
    </header>

    <div class='realtors'>
      <h3 class='heading-3'>Top 3 Realtors</h3>
      <div class='realtors__list'>
        <img
          src='./assets/img/realtor-1.jpeg'
          alt='Realtor 1'
          class='realtors__img'
        >
        <div class='realtors__details'>
          <h4 class='heading-4 heading-4--light'>Erik Feinman</h4>
          <p class='realtors__sold'>245 houses sold</p>
        </div>
        <img
          src='./assets/img/realtor-2.jpeg'
          alt='Realtor 2'
          class='realtors__img'
        >
        <div class='realtors__details'>
          <h4 class='heading-4 heading-4--light'>Kim Brown</h4>
          <p class='realtors__sold'>212 houses sold</p>
        </div>
        <img
          src='./assets/img/realtor-3.jpeg'
          alt='Realtor 3'
          class='realtors__img'
        >
        <div class='realtors__details'>
          <h4 class='heading-4 heading-4--light'>Toby Ramsey</h4>
          <p class='realtors__sold'>198 houses sold</p>
        </div>
      </div>
    </div>

    <section class='features'>
      <div class='feature feature--1'>
        <svg class='feature__icon'>
          <use xlink:href="./assets/img/sprite.svg#icon-global"></use>
        </svg>
        <h4 class='heading-4 heading-4--dark'>World's best luxury homes</h4>
        <p class='feature__text'>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Tenetur distinctio necessitatibus pariatur voluptatibus.</p>
      </div>
      <div class='feature feature--2'>
        <svg class='feature__icon'>
          <use xlink:href="./assets/img/sprite.svg#icon-trophy"></use>
        </svg>
        <h4 class='heading-4 heading-4--dark'>Only the best properties</h4>
        <p class='feature__text'>Voluptatum mollitia quae. Vero ipsum sapiente molestias accusamus rerum sed a eligendi aut quia.</p>
      </div>
      <div class='feature feature--3'>
        <svg class='feature__icon'>
          <use xlink:href="./assets/img/sprite.svg#icon-map-pin"></use>
        </svg>
        <h4 class='heading-4 heading-4--dark'>All homes in top locations</h4>
        <p class='feature__text'>Tenetur distinctio necessitatibus pariatur voluptatibus quidem consequatur harum.</p>
      </div>
      <div class='feature feature--4'>
        <svg class='feature__icon'>
          <use xlink:href="./assets/img/sprite.svg#icon-key"></use>
        </svg>
        <h4 class='heading-4 heading-4--dark'>New home in one week</h4>
        <p class='feature__text'>Vero ipsum sapiente molestias accusamus rerum. Lorem, ipsum dolor sit amet consectetur adipisicing elit.</p>
      </div>
      <div class='feature feature--5'>
        <svg class='feature__icon'>
          <use xlink:href="./assets/img/sprite.svg#icon-presentation"></use>
        </svg>
        <h4 class='heading-4 heading-4--dark'>Top 1% realtors</h4>
        <p class='feature__text'>Quidem consequatur harum, voluptatum mollitia quae. Tenetur distinctio necessitatibus pariatur voluptatibus.</p>
      </div>
      <div class='feature feature--6'>
        <svg class='feature__icon'>
          <use xlink:href="./assets/img/sprite.svg#icon-lock"></use>
        </svg>
        <h4 class='heading-4 heading-4--dark'>Secure payments on nexter</h4>
        <p class='feature__text'>Pariatur voluptatibus quidem consequatur harum, voluptatum mollitia quae.</p>
      </div>
    </section>

    <div class='story__pictures'>
      <img
        src='./assets/img/story-1.jpeg'
        alt='Couple with new house'
        class='story__img--1'
      >
      <img
        src='./assets/img/story-2.jpeg'
        alt='new house'
        class='story__img--2'
      >
    </div>

    <div class='story__content'>
      <h3 class='heading-3 mb-sm'>Happy Customers</h3>
      <h2 class='heading-2 heading-2--dark mb-md'>&ldquo;The best decision of our lives&rdquo;</h2>
      <p class='story__text '>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Tenetur distinctio necessitatibus pariatur voluptatibus. Quidem consequatur harum volupta!</p>
      <button class="btn">Find your own home</button>
    </div>

    <section class='homes'>
      <div class='home'>
        <img
          src='./assets/img/house-1.jpeg'
          alt='House 1'
          class='home__img'
        >
        <svg class='home__like'>
          <use xlink:href="./assets/img/sprite.svg#icon-heart-full"></use>
        </svg>
        <h5 class='home__name'>Beautiful Family House</h5>
        <div class='home__location'>
          <svg class='home__like'>
            <use xlink:href="./assets/img/sprite.svg#icon-map-pin"></use>
          </svg>
          <p>USA</p>
        </div>
        <div class='home__rooms'>
          <svg class='home__like'>
            <use xlink:href="./assets/img/sprite.svg#icon-profile-male"></use>
          </svg>
          <p>5 rooms</p>
        </div>
        <div class='home__area'>
          <svg class='home__like'>
            <use xlink:href="./assets/img/sprite.svg#icon-expand"></use>
          </svg>
          <p>325 m<sup>2</sup></p>
        </div>
        <div class='home__price'>
          <svg class='home__like'>
            <use xlink:href="./assets/img/sprite.svg#icon-key"></use>
          </svg>
          <p>$1,200,000</p>
        </div>
        <button class='btn home__btn'>Contact realtor</button>
      </div>
      <div class='home'>
        <img
          src='./assets/img/house-2.jpeg'
          alt='House 2'
          class='home__img'
        >
        <svg class='home__like'>
          <use xlink:href="./assets/img/sprite.svg#icon-heart-full"></use>
        </svg>
        <h5 class='home__name'>Modern Glass Villa</h5>
        <div class='home__location'>
          <svg class='home__like'>
            <use xlink:href="./assets/img/sprite.svg#icon-map-pin"></use>
          </svg>
          <p>Canada</p>
        </div>
        <div class='home__rooms'>
          <svg class='home__like'>
            <use xlink:href="./assets/img/sprite.svg#icon-profile-male"></use>
          </svg>
          <p>6 rooms</p>
        </div>
        <div class='home__area'>
          <svg class='home__like'>
            <use xlink:href="./assets/img/sprite.svg#icon-expand"></use>
          </svg>
          <p>450 m<sup>2</sup></p>
        </div>
        <div class='home__price'>
          <svg class='home__like'>
            <use xlink:href="./assets/img/sprite.svg#icon-key"></use>
          </svg>
          <p>$2,750,000</p>
        </div>
        <button class='btn home__btn'>Contact realtor</button>
      </div>
      <div class='home'>
        <img
          src='./assets/img/house-3.jpeg'
          alt='House 3'
          class='home__img'
        >
        <svg class='home__like'>
          <use xlink:href="./assets/img/sprite.svg#icon-heart-full"></use>
        </svg>
        <h5 class='home__name'>Cozy Country House</h5>
        <div class='home__location'>
          <svg class='home__like'>
            <use xlink:href="./assets/img/sprite.svg#icon-map-pin"></use>
          </svg>
          <p>UK</p>
        </div>
        <div class='home__rooms'>
          <svg class='home__like'>
            <use xlink:href="./assets/img/sprite.svg#icon-profile-male"></use>
          </svg>
          <p>4 rooms</p>
        </div>
        <div class='home__area'>
          <svg class='home__like'>
            <use xlink:href="./assets/img/sprite.svg#icon-expand"></use>
          </svg>
          <p>250 m<sup>2</sup></p>
        </div>
        <div class='home__price'>
          <svg class='home__like'>
            <use xlink:href="./assets/img/sprite.svg#icon-key"></use>
          </svg>
          <p>$850,000</p>
        </div>
        <button class='btn home__btn'>Contact realtor</button>
      </div>
      <div class='home'>
        <img
          src='./assets/img/house-4.jpeg'
          alt='House 4'
          class='home__img'
        >
        <svg class='home__like'>
          <use xlink:href="./assets/img/sprite.svg#icon-heart-full"></use>
        </svg>
        <h5 class='home__name'>Large Rustical Villa</h5>
        <div class='home__location'>
          <svg class='home__like'>
            <use xlink:href="./assets/img/sprite.svg#icon-map-pin"></use>
          </svg>
          <p>Portugal</p>
        </div>
        <div class='home__rooms'>
          <svg class='home__like'>
            <use xlink:href="./assets/img/sprite.svg#icon-profile-male"></use>
          </svg>
          <p>6 rooms</p>
        </div>
        <div class='home__area'>
          <svg class='home__like'>
            <use xlink:href="./assets/img/sprite.svg#icon-expand"></use>
          </svg>
          <p>480 m<sup>2</sup></p>
        </div>
        <div class='home__price'>
          <svg class='home__like'>
            <use xlink:href="./assets/img/sprite.svg#icon-key"></use>
          </svg>
          <p>$1,950,000</p>
        </div>
        <button class='btn home__btn'>Contact realtor</button>
      </div>
      <div class='home'>
        <img
          src='./assets/img/house-5.jpeg'
          alt='House 5'
          class='home__img'
        >
        <svg class='home__like'>
          <use xlink:href="./assets/img/sprite.svg#icon-heart-full"></use>
        </svg>
        <h5 class='home__name'>Majestic Palace House</h5>
        <div class='home__location'>
          <svg class='home__like'>
            <use xlink:href="./assets/img/sprite.svg#icon-map-pin"></use>
          </svg>
          <p>Germany</p>
        </div>
        <div class='home__rooms'>
          <svg class='home__like'>
            <use xlink:href="./assets/img/sprite.svg#icon-profile-male"></use>
          </svg>
          <p>18 rooms</p>
        </div>
        <div class='home__area'>
          <svg class='home__like'>
            <use xlink:href="./assets/img/sprite.svg#icon-expand"></use>
          </svg>
          <p>4230 m<sup>2</sup></p>
        </div>
        <div class='home__price'>
          <svg class='home__like'>
            <use xlink:href="./assets/img/sprite.svg#icon-key"></use>
          </svg>
          <p>$9,500,000</p>
        </div>
        <button class='btn home__btn'>Contact realtor</button>
      </div>
      <div class='home'>
        <img
          src='./assets/img/house-6.jpeg'
          alt='House 6'
          class='home__img'
        >
        <svg class='home__like'>
          <use xlink:href="./assets/img/sprite.svg#icon-heart-full"></use>
        </svg>
        <h5 class='home__name'>Modern Family Apartment</h5>
        <div class='home__location'>
          <svg class='home__like'>
            <use xlink:href="./assets/img/sprite.svg#icon-map-pin"></use>
          </svg>
          <p>Italy</p>
        </div>
        <div class='home__rooms'>
          <svg class='home__like'>
            <use xlink:href="./assets/img/sprite.svg#icon-profile-male"></use>
          </svg>
          <p>3 rooms</p>
        </div>
        <div class='home__area'>
          <svg class='home__like'>
            <use xlink:href="./assets/img/sprite.svg#icon-expand"></use>
          </svg>
          <p>180 m<sup>2</sup></p>
        </div>
        <div class='home__price'>
          <svg class='home__like'>
            <use xlink:href="./assets/img/sprite.svg#icon-key"></use>
          </svg>
          <p>$6,000</p>
        </div>
        <button class='btn home__btn'>Contact realtor</button>
      </div>

    </section>

    <section class='gallery'>
      <figure class='gallery__item gallery__item--1'>
        <img
          src='./assets/img/gal-1.jpeg'
          alt='gallery image 1'
          class='gallery__img'
        >
      </figure>
      <figure class='gallery__item gallery__item--2'>
        <img
          src='./assets/img/gal-2.jpeg'
          alt='gallery image 2'
          class='gallery__img'
        >
      </figure>
      <figure class='gallery__item gallery__item--3'>
        <img
          src='./assets/img/gal-3.jpeg'
          alt='gallery image 3'
          class='gallery__img'
        >
      </figure>
      <figure class='gallery__item gallery__item--4'>
        <img
          src='./assets/img/gal-4.jpeg'
          alt='gallery image 4'
          class='gallery__img'
        >
      </figure>
      <figure class='gallery__item gallery__item--5'>
        <img
          src='./assets/img/gal-5.jpeg'
          alt='gallery image 5'
          class='gallery__img'
        >
      </figure>
      <figure class='gallery__item gallery__item--6'>
        <img
          src='./assets/img/gal-6.jpeg'
          alt='gallery image 6'
          class='gallery__img'
        >
      </figure>
      <figure class='gallery__item gallery__item--7'>
        <img
          src='./assets/img/gal-7.jpeg'
          alt='gallery image 7'
          class='gallery__img'
        >
      </figure>
      <figure class='gallery__item gallery__item--8'>
        <img
          src='./assets/img/gal-8.jpeg'
          alt='gallery image 8'
          class='gallery__img'
        >
      </figure>
      <figure class='gallery__item gallery__item--9'>
        <img
          src='./assets/img/gal-9.jpeg'
          alt='gallery image 9'
          class='gallery__img'
        >
      </figure>
      <figure class='gallery__item gallery__item--10'>
        <img
          src='./assets/img/gal-10.jpeg'
          alt='gallery image 10'
          class='gallery__img'
        >
      </figure>
      <figure class='gallery__item gallery__item--11'>
        <img
          src='./assets/img/gal-11.jpeg'
          alt='gallery image 11'
          class='gallery__img'
        >
      </figure>
      <figure class='gallery__item gallery__item--12'>
        <img
          src='./assets/img/gal-12.jpeg'
          alt='gallery image 12'
          class='gallery__img'
        >
      </figure>
      <figure class='gallery__item gallery__item--13'>
        <img
          src='./assets/img/gal-13.jpeg'
          alt='gallery image 13'
          class='gallery__img'
        >
      </figure>
      <figure class='gallery__item gallery__item--14'>
        <img
          src='./assets/img/gal-14.jpeg'
          alt='gallery image 14'
          class='gallery__img'
        >
      </figure>

    </section>

    <footer class='footer'>
      <ul class='nav'>
        <li class='nav__item'><a
            href='#'
            class='nav__link'
          >Find your dream home</a></li>
        <li class='nav__item'><a
            href='#'
            class='nav__link'
          >Come work with us!</a></li>
        <li class='nav__item'><a
            href='#'
            class='nav__link'
          >Request proposal</a></li>
        <li class='nav__item'><a
            href='#'
            class='nav__link'
          >Download home planner</a></li>
        <li class='nav__item'><a
            href='#'
            class='nav__link'
          >Contact us</a></li>
        <li class='nav__item'><a
            href='#'
            class='nav__link'
          >Submit your property</a></li>
      </ul>
      <p class='copyright'>
        &copy; Copyright 2020 by Jonas Schmedtmann.
      </p>
    </footer>
  </div>
</template>

<script>
export default {
  name: "App",
  components: {},
};
</script>

<style lang="scss">
@import "./styles/global.scss";

.story {
  &__pictures {
    background-color: $color-primary;
    grid-column: full-start / col-end 4;
    background-image: linear-gradient(
        rgba($color-primary, 0.5),
        rgba($color-primary, 0.5)
      ),
      url(./assets/img/back.jpg);
    background-size: cover;

    display: grid;
    grid-template-rows: repeat(6, 1fr);
    grid-template-columns: repeat(6, 1fr);
    align-items: center;

    @media only screen and (max-width: $bp-medium) {
      grid-column: 1 / -1;
      padding: 6rem;
    }
  }

  &__img--1 {
    width: 100%;
    grid-row: 2 / 6;
    grid-column: 2 / 6;
    box-shadow: 0 2rem 5rem rgba(#000, 0.1);

    @media only screen and (max-width: $bp-medium) {
      grid-column: 1 / 5;
      grid-row: 1/-1;
      width: 100%;
    }
  }

  &__img--2 {
    width: 115%;
    grid-row: 4 / 6;
    grid-column: 4 / 7;
    z-index: 30;
    box-shadow: 0 2rem 5rem rgba(#000, 0.2);
    @media only screen and (max-width: $bp-medium) {
      grid-row: 1/-1;
      width: 100%;
    }
  }

  &__content {
    background-color: $color-grey-light-1;
    grid-column: col-start 5 / full-end;

    padding: 6rem 8vw;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: flex-start;

    @media only screen and (max-width: $bp-medium) {
      grid-column: 1 / -1;
      grid-row: 5 / 6;
    }
  }

  &__text {
    font-size: 1.5rem;
    font-style: italic;
    margin-bottom: 4rem;
  }
}

.header {
  background-color: $color-grey-dark-1;
  grid-column: full-start / col-end 6;
  background-image: linear-gradient(
      rgba($color-secondary, 0.93),
      rgba($color-secondary, 0.93)
    ),
    url(./assets/img/hero.jpeg);
  background-size: cover;
  background-position: center;
  padding: 8rem;
  padding-top: 4rem;

  display: grid;
  grid-template-rows: 1fr min-content minmax(6rem, min-content) 1fr;
  grid-template-columns: minmax(min-content, max-content);
  row-gap: 1.5rem;
  justify-content: center;

  @media only screen and (max-width: $bp-medium) {
    grid-column: 1 / -1;
  }

  @media only screen and (max-width: $bp-small) {
    padding: 5rem;
  }

  &__logo {
    height: 3rem;
    justify-self: center;
  }

  &__btn {
    align-self: start;
    justify-self: start;
  }

  &__seenon-text {
    display: grid;
    grid-template-columns: 1fr max-content 1fr;
    column-gap: 1.5rem;
    align-items: center;
    font-size: 1.6rem;
    color: $color-grey-light-2;

    &::before,
    &::after {
      content: "";
      height: 1px;
      display: block;
      background-color: currentColor;
    }
  }

  &__seenon-logos {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    column-gap: 3rem;
    justify-items: center;
    align-items: center;

    img {
      max-height: 2.5rem;
      max-width: 100%;
      filter: brightness(70%);
    }
  }
}
</style>
