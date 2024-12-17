<template>
  <div class="cow">
    <h1>Варианты коворкинга</h1>
  </div>
  <div class="about_cow">
    <div class="about">
      <div class="about__img">
        <img src="../assets/img/coworking_office.jpg" alt="" />
        <p>А-Центр, коворкинг</p>
        <p style="font-size: 24px; color: #2b7af1; font-weight: 700; margin-top: 20px">
          450 ₽ Разовое
        </p>
        <div class="location_cow">
          <img src="../assets/img/Location_Icon.svg" alt="" />
          <p>ул. Максима Горького 151</p>
        </div>
        <button class="but but_six">Подробнее</button>
      </div>
    </div>
    <div class="about">
      <div class="about__img">
        <img src="../assets/img/coworking_site.jpg" alt="" />
        <p>Бьюти-коворкинг Power Place</p>
        <p style="font-size: 24px; color: #2b7af1; font-weight: 700; margin-top: 20px">
          100 ₽ Разовое
        </p>
        <div class="location_cow">
          <img src="../assets/img/Location_Icon.svg" alt="" />
          <p>ул. Серафимовича 61</p>
        </div>
        <button class="but but_six">Подробнее</button>
      </div>
    </div>
    <div class="about">
      <div class="about__img">
        <img src="../assets/img/coworking_site2.jpg" alt="" />
        <p>Коворкинг Рубин</p>
        <p style="font-size: 24px; color: #2b7af1; font-weight: 700; margin-top: 20px">
          500 ₽ Разовое
        </p>
        <div class="location_cow">
          <img src="../assets/img/Location_Icon.svg" alt="" />
          <p>ул. Театральный 85</p>
        </div>
        <button class="but but_six">Подробнее</button>
      </div>
    </div>
  </div>
  <div class="about_cow">
    <div class="about">
      <div class="about__img">
        <img src="../assets/img/coworking_site3.jpg" alt="" />
        <p>Коворкинг Место</p>
        <p style="font-size: 24px; color: #2b7af1; font-weight: 700; margin-top: 20px">
          2 400 ₽ Разовое
        </p>
        <div class="location_cow">
          <img src="../assets/img/Location_Icon.svg" alt="" />
          <p>ул. Максима Горького 151</p>
        </div>
        <button class="but but_six">Подробнее</button>
      </div>
    </div>
    <div class="about">
      <div class="about__img">
        <img src="../assets/img/coworking_site5.jpg" alt="" />
        <p>Бьюти Коворкинг `Персона`</p>
        <p style="font-size: 24px; color: #2b7af1; font-weight: 700; margin-top: 20px">
          150 ₽ Разовое
        </p>
        <div class="location_cow">
          <img src="../assets/img/Location_Icon.svg" alt="" />
          <p>ул. Максима Горького 151</p>
        </div>
        <button class="but but_six">Подробнее</button>
      </div>
    </div>
    <div class="about">
      <div class="about__img">
        <img src="../assets/img/coworking_site4.jpg" alt="" />
        <p>Коворкинг `Под Крышей`</p>
        <p style="font-size: 24px; color: #2b7af1; font-weight: 700; margin-top: 20px">Бесплатно</p>
        <div class="location_cow">
          <img src="../assets/img/Location_Icon.svg" alt="" />
          <p>ул. Максима Горького 151</p>
        </div>
        <button class="but but_six">Подробнее</button>
      </div>
    </div>
  </div>
</template>

<style>
.about_cow {
  display: flex;
  column-gap: 45px;
  margin-left: 80px;
  margin-top: 40px;
}
.about {
  width: 395px;
}

.cow {
  margin-top: 50px;
  margin-left: 80px;
}

.cow h1 {
  color: #2b7af1;
  font-size: 36px;
}

.about__img {
}

.about__img img {
  border-radius: 10px;
}

.about__img p {
  font-weight: 700;
  font-size: 24px;
  margin-top: 20px;
}

.location_cow {
  column-gap: 10px;
  display: flex;
  margin-top: 15px;
}

.location_cow p {
  font-size: 18px;
  font-weight: 100;
  margin: 0;
}

.but_six {
  margin-top: 20px;
  width: 170px;
  height: 40px;
}
</style>
