<template>
  <Header />
  <main>
    <section class="promotions">
      <Container>
        <div class="promotions__title">
          <p>Promotions</p>
        </div>
        <div class="promotions__description">
          <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque
            consectetur elementum velit nec feugiat. Aliquam eget mauris lorem.
          </p>
        </div>
        <div class="promotion-list">
          <div class="promotion-item">
            <div class="promotion-item__title">
              <p>October 2024 promotion</p>
            </div>
            <div class="promotion-item__body">
              <div class="promotion-item__image">
                <img src="/assets/images/promotion-1.jpg" alt="" />
              </div>
              <div class="promotion-item__description">
                <p>
                  Pellentesque consequat nulla et lorem fermentum, vitae
                  sagittis erat cursus. Sed nec fringilla turpis.
                </p>
              </div>
            </div>
          </div>
          <div class="promotion-item">
            <div class="promotion-item__title">
              <p>New Product!</p>
            </div>
            <div class="promotion-item__body">
              <div class="promotion-item__image">
                <img src="/assets/images/promotion-2.jpg" alt="" />
              </div>
              <div class="promotion-item__description">
                <p>
                  Pellentesque consequat nulla et lorem fermentum, vitae
                  sagittis erat cursus. Sed nec fringilla turpis.
                </p>
              </div>
            </div>
          </div>
          <div class="promotion-item">
            <div class="promotion-item__title">
              <p>Latest Treatment</p>
            </div>
            <div class="promotion-item__body">
              <div class="promotion-item__image">
                <img src="/assets/images/promotion-3.jpg" alt="" />
              </div>
              <div class="promotion-item__description">
                <p>
                  Pellentesque consequat nulla et lorem fermentum, vitae
                  sagittis erat cursus. Sed nec fringilla turpis.
                </p>
              </div>
            </div>
          </div>
          <div class="promotion-item">
            <div class="promotion-item__title">
              <p>New Eye Wares!</p>
            </div>
            <div class="promotion-item__body">
              <div class="promotion-item__image">
                <img src="/assets/images/promotion-4.jpg" alt="" />
              </div>
              <div class="promotion-item__description">
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
/* Promotions */
.promotions__title {
  margin-top: 60px;
  margin-bottom: 20px;
  font-size: 25px;
  font-weight: 700;
  color: var(--primary-color);
}
.promotions__description {
  max-width: 480px;
  font-size: 12px;
}
/* Promotions List */
.promotion-list {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 40px;
  margin-top: 60px;
}
.promotion-item__title {
  margin-bottom: 20px;
  font-weight: 700;
  color: var(--primary-color);
}
.promotion-item__description {
  margin: 10px 0;
  font-size: 12px;
  color: #6c6c6c;
}
.promotion-item__body {
  padding: 10px;
  background-color: #fff;
  border-radius: 10px;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.4);
}
</style>
