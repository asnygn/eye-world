<template>
  <Header />
  <main>
    <section class="about">
      <Container>
        <div class="about__content">
          <div class="about__text-content">
            <div class="about__title">
              <p>About Us</p>
            </div>
            <div class="about__subtitle">
              <p>
                Eye World Group Co., Ltd., rooted deeply in the vibrant city of
                Yangon, Myanmar,
              </p>
            </div>
            <div class="about__description">
              <p>
                stands as a beacon of excellence and innovation in the eye and
                healthcare industry for nearly three decades. As a pioneer in
                advancing eye health, our reputation has been built on a
                foundation of quality, expertise, and an unwavering commitment
                to delivering superior eye care solutions to the people of
                Myanmar.
              </p>
            </div>
          </div>
          <div class="about__image-content">
            <div class="about__image">
              <img src="/assets/images/about.png" alt="" />
            </div>
          </div>
        </div>
      </Container>
    </section>
    <section class="statement">
      <Container>
        <div class="statement__item statement__item--left">
          <div class="statement__title"><p>Our Mission</p></div>
          <div class="statement__description">
            <p>
              To pave the path for a brighter, healthier future by making
              premier eye care accessible to every individual in Myanmar.
              Through our concerted efforts, we envision a Myanmar where eye
              health is not a privilege but a right enjoyed by all.
            </p>
          </div>
        </div>
        <div class="statement__item statement__item--right">
          <div class="statement__title"><p>Our Mission</p></div>
          <div class="statement__description">
            <p>
              To pave the path for a brighter, healthier future by making
              premier eye care accessible to every individual in Myanmar.
              Through our concerted efforts, we envision a Myanmar where eye
              health is not a privilege but a right enjoyed by all.
            </p>
          </div>
        </div>
      </Container>
    </section>
    <section class="venture">
      <Container>
        <div class="venture__content">
          <div class="venture__image">
            <img src="/assets/images/venture.jpg" alt="" />
          </div>
          <div class="venture__text">
            <div class="venture__title">
              <p>Our Ventures</p>
            </div>
            <div class="venture__description">
              <p>
                Beyond just distribution, we have ventured deep into the
                healthcare sector as investors, spearheading the establishment
                of private eye hospitals and Eye institutes across Myanmar.
              </p>
              <p>
                Through these institutions, we are pioneering a new era of eye
                healthcare, blending world-class expertise with local insights
                to offer unmatched eye care services.
              </p>
            </div>
          </div>
        </div>
      </Container>
    </section>
  </main>
  <Footer />
</template>

<style scopd>
.about {
  margin-top: 40px;
}
.about__title {
  margin-bottom: 20px;
  font-size: 16px;
}
.about__subtitle {
  margin-bottom: 20px;
  font-size: 24px;
  font-weight: 700;
  color: var(--primary-color);
}
.about__content {
  display: flex;
  align-items: center;
  gap: 40px;
  clear: both;
}
/* Statement */
.statement {
  margin-top: 80px;
}
.statement:after {
  content: "";
  display: table;
  clear: both;
}
.statement__item {
  padding: 30px;
  max-width: 80%;
  margin-bottom: 40px;
  background-color: #00bdbd;
  border-radius: 8px;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.4);
}
.statement__title {
  margin-bottom: 20px;
  font-size: 24;
  font-weight: 700;
  color: #fff;
}
.statement__description {
  font-weight: 500;
  color: #fff;
}
.statement__item--left {
  float: left;
}
.statement__item--right {
  float: right;
}
/* Venture */
.venture {
  margin-top: 80px;
}
.venture__content {
  display: flex;
  gap: 40px;
}
.venture__title {
  margin-bottom: 20px;
  font-size: 24px;
  font-weight: 700;
  color: var(--primary-color);
}
</style>
