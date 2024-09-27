<template>
  <Header />
  <main>
    <section class="events">
      <Container>
        <div class="events__title">
          <p>Event and News</p>
        </div>
        <div class="events__description">
          <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque
            consectetur elementum velit nec feugiat. Aliquam eget mauris lorem.
          </p>
        </div>
        <div class="events-list">
          <div class="events-item">
            <div class="events-item__title">
              <p>Donation for Flooded Areas</p>
            </div>
            <div class="events-item__body">
              <div class="events-item__image">
                <img src="/assets/images/promotion-1.jpg" alt="" />
              </div>
              <div class="events-item__description">
                <p>
                  Pellentesque consequat nulla et lorem fermentum, vitae
                  sagittis erat cursus. Sed nec fringilla turpis.
                </p>
              </div>
            </div>
          </div>
          <div class="events-item">
            <div class="events-item__title">
              <p>October Conference</p>
            </div>
            <div class="events-item__body">
              <div class="events-item__image">
                <img src="/assets/images/promotion-2.jpg" alt="" />
              </div>
              <div class="events-item__description">
                <p>
                  Pellentesque consequat nulla et lorem fermentum, vitae
                  sagittis erat cursus. Sed nec fringilla turpis.
                </p>
              </div>
            </div>
          </div>
          <div class="events-item">
            <div class="events-item__title">
              <p>September 2024 Training</p>
            </div>
            <div class="events-item__body">
              <div class="events-item__image">
                <img src="/assets/images/promotion-3.jpg" alt="" />
              </div>
              <div class="events-item__description">
                <p>
                  Pellentesque consequat nulla et lorem fermentum, vitae
                  sagittis erat cursus. Sed nec fringilla turpis.
                </p>
              </div>
            </div>
          </div>
        </div>
      </Container>
    </section>
  </main>
  <Footer />
</template>

<style scopd>
main {
  padding-bottom: 100px;
}
/* Events */
.events__title {
  margin-top: 60px;
  margin-bottom: 20px;
  font-size: 25px;
  font-weight: 700;
  color: var(--primary-color);
}
.events__description {
  max-width: 480px;
  font-size: 12px;
}
/* News List */
.events-list {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 40px;
  margin-top: 60px;
}
.events-item__title {
  margin-bottom: 20px;
  font-weight: 700;
  color: var(--primary-color);
}
.events-item__description {
  margin: 10px 0;
  font-size: 12px;
  color: #6c6c6c;
}
.events-item__body {
  padding: 10px;
  background-color: #fff;
  border-radius: 10px;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.4);
}
</style>
