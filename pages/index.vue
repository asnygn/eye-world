<template>
  <Header />
  <main>
    <section class="welcome">
      <Container>
        <div class="welcome__text1">
          <p>Eye World Group Provides,</p>
        </div>
        <div class="welcome__text2">
          <p>World Class Optical Equipment And Service Support</p>
        </div>
      </Container>
    </section>
    <section class="services">
      <Container>
        <div class="services__title">
          <p>Our Services</p>
        </div>
        <div class="services__list">
          <div class="service-item">
            <div>
              <div class="service-item__title"><p>For Eye Exam</p></div>
              <div class="service-item__description">
                <p>
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla
                  ultricies ultricies orci in volutpat. Phasellus ut magna sed
                  libero facilisis imperdiet sed eget justo.
                </p>
              </div>
            </div>
            <div class="service-item__link">
              <NuxtLink to="/">Read more</NuxtLink>
            </div>
          </div>
          <div class="service-item">
            <div>
              <div class="service-item__title"><p>For Equipment</p></div>
              <div class="service-item__description">
                <p>
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla
                  ultricies ultricies orci in volutpat. Phasellus ut magna sed
                  libero facilisis imperdiet sed eget justo.
                </p>
              </div>
            </div>
            <div class="service-item__link">
              <NuxtLink to="/">Read more</NuxtLink>
            </div>
          </div>
          <div class="service-item">
            <div>
              <div class="service-item__title"><p>For Operation</p></div>
              <div class="service-item__description">
                <p>
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla
                  ultricies ultricies orci in volutpat. Phasellus ut magna sed
                  libero facilisis imperdiet sed eget justo.
                </p>
              </div>
            </div>
            <div class="service-item__link">
              <NuxtLink to="/">Read more</NuxtLink>
            </div>
          </div>
        </div>
      </Container>
    </section>
    <section class="equipment">
      <Container>
        <div class="equipment__title">
          <p>Laser Optical Equipment</p>
        </div>
        <div class="equipment-list">
          <div class="equipment-list__item"></div>
        </div>
      </Container>
    </section>
  </main>
</template>

<style scopd>
.welcome {
  margin-top: 80px;
  margin-bottom: 80px;
}
.welcome__text1 {
  margin-bottom: 20px;
  font-size: 14px;
}
.welcome__text2 {
  max-width: 420px;
  font-size: 25px;
  font-weight: 700;
  color: var(--primary-color);
}
/* Services */
.services {
  margin-bottom: 80px;
}
.services__title {
  margin-bottom: 20px;
  font-size: 20px;
  font-weight: 500;
}
.services__list {
  display: flex;
  gap: 15px;
}
/* Service Item */
.service-item {
  position: relative;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  flex: 1;
  padding: 20px;
  background-image: url("../assets/images/service-1.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  border-radius: 10px;
  z-index: 1;
}
.service-item::before {
  content: "";
  position: absolute;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  background-color: rgba(0, 134, 134, 0.4);
  border-radius: 10px;
  z-index: -1;
}
.service-item__title {
  margin-bottom: 20px;
  font-size: 25px;
  font-weight: 700;
  color: #fff;
}
.service-item__description {
  margin-bottom: 20px;
  font-size: 14px;
  font-weight: 500;
  color: #fff;
}
.service-item__link a {
  font-size: 16px;
  font-weight: 700;
  color: #fff;
  text-decoration: none;
}
/* Equipment */
.equipment {
  position: relative;
  margin-bottom: 100px;
}
.equipment__title {
  position: relative;
  padding-bottom: 10px;
  font-size: 20px;
  font-weight: 500;
  text-align: center;
}
.equipment__title::before {
  content: "";
  position: absolute;
  left: 0;
  right: 0;
  bottom: 0;
  width: 50px;
  height: 4px;
  margin: 0 auto;
  background-color: var(--primary-color);
}
</style>
