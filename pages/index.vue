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
        <div class="services__content">
          <div class="services__title">
            <p>Our Services</p>
          </div>
          <div class="services__list">
            <div class="service-item">
              <div>
                <div class="service-item__title"><p>For Eye Exam</p></div>
                <div class="service-item__description">
                  <p>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                    Nulla ultricies ultricies orci in volutpat. Phasellus ut
                    magna sed libero facilisis imperdiet sed eget justo.
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
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                    Nulla ultricies ultricies orci in volutpat. Phasellus ut
                    magna sed libero facilisis imperdiet sed eget justo.
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
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                    Nulla ultricies ultricies orci in volutpat. Phasellus ut
                    magna sed libero facilisis imperdiet sed eget justo.
                  </p>
                </div>
              </div>
              <div class="service-item__link">
                <NuxtLink to="/">Read more</NuxtLink>
              </div>
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
        <div class="equipment__list">
          <div class="equipment-item">
            <div class="equipment-item__image">
              <img src="/assets/images/equipment-1.png" alt="" />
            </div>
            <div class="equipment-item__logo">
              <img src="/assets/images/equipment-logo.png" alt="" />
            </div>
            <div class="equipment-item__title">
              <p>Optical Coherence Tomography RS-1 Glauvas</p>
            </div>
          </div>
          <div class="equipment-item">
            <div class="equipment-item__image">
              <img src="/assets/images/equipment-1.png" alt="" />
            </div>
            <div class="equipment-item__logo">
              <img src="/assets/images/equipment-logo.png" alt="" />
            </div>
            <div class="equipment-item__title">
              <p>Optical Coherence Tomography RS-1 Glauvas</p>
            </div>
          </div>
          <div class="equipment-item">
            <div class="equipment-item__image">
              <img src="/assets/images/equipment-1.png" alt="" />
            </div>
            <div class="equipment-item__logo">
              <img src="/assets/images/equipment-logo.png" alt="" />
            </div>
            <div class="equipment-item__title">
              <p>Optical Coherence Tomography RS-1 Glauvas</p>
            </div>
          </div>
          <div class="equipment-item">
            <div class="equipment-item__image">
              <img src="/assets/images/equipment-1.png" alt="" />
            </div>
            <div class="equipment-item__logo">
              <img src="/assets/images/equipment-logo.png" alt="" />
            </div>
            <div class="equipment-item__title">
              <p>Optical Coherence Tomography RS-1 Glauvas</p>
            </div>
          </div>
        </div>
      </Container>
    </section>
    <section class="brands">
      <Container>
        <div class="brands__title">Brands We Work With</div>
        <ul class="brands__list">
          <li>
            <img src="/assets/images/brand-1.png" alt="" />
          </li>
          <li>
            <img src="/assets/images/brand-2.png" alt="" />
          </li>
          <li>
            <img src="/assets/images/brand-3.png" alt="" />
          </li>
          <li>
            <img src="/assets/images/brand-4.png" alt="" />
          </li>
          <li>
            <img src="/assets/images/brand-5.png" alt="" />
          </li>
        </ul>
      </Container>
    </section>
  </main>
</template>

<style scopd>
main {
  padding-bottom: 100px;
}
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
  padding-top: 40px;
  padding-bottom: 80px;
  background-color: #f8f8f8;
}
.equipment__title {
  position: relative;
  margin-bottom: 80px;
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
  height: 3px;
  margin: 0 auto;
  background-color: var(--primary-color);
}
.equipment__list {
  position: relative;
  display: flex;
  flex: 1;
  gap: 25px;
}
/* Equipment Item */
.equipment-item {
  position: relative;
  flex: 1;
  padding: 15px;
  border-radius: 10px;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.4);
}
.equipment-item__image {
  margin-bottom: 20px;
}
.equipment-item__image img {
  max-width: 100%;
}
.equipment-item__logo {
  margin-bottom: 20px;
  text-align: center;
}
.equipment-item__title {
  margin-bottom: 20px;
  font-size: 12px;
  color: #6c6c6c;
}
/* Brands */
.brands__title {
  position: relative;
  margin-bottom: 80px;
  padding-bottom: 10px;
  font-size: 20px;
  font-weight: 500;
  text-align: center;
}
.brands__title::before {
  content: "";
  position: absolute;
  left: 0;
  right: 0;
  bottom: 0;
  width: 50px;
  height: 3px;
  margin: 0 auto;
  background-color: var(--primary-color);
}
.brands__list {
  list-style: none;
  text-align: center;
}
.brands__list li {
  display: inline-block;
  margin: 20px;
}
.brands__list li img {
  max-width: 100%;
}
</style>
