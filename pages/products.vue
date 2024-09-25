<template>
  <Header />
  <main>
    <section class="products">
      <Container>
        <div class="products__title">
          <p>Products and Services</p>
        </div>
        <div class="products__description">
          <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque
            consectetur elementum velit nec feugiat. Aliquam eget mauris lorem.
          </p>
        </div>
        <div class="product-list">
          <div class="product-list__title">
            <p>Eye Exams</p>
          </div>
          <div class="product-list__items">
            <div class="product">
              <div class="product__image">
                <img src="/assets/images/product-1.jpg" alt="" />
              </div>
              <div class="product__description">
                <p>
                  Pellentesque consequat nulla et lorem fermentum, vitae
                  sagittis erat cursus. Sed nec fringilla turpis.
                </p>
              </div>
            </div>
            <div class="product">
              <div class="product__image">
                <img src="/assets/images/product-2.jpg" alt="" />
              </div>
              <div class="product__description">
                <p>
                  Pellentesque consequat nulla et lorem fermentum, vitae
                  sagittis erat cursus. Sed nec fringilla turpis.
                </p>
              </div>
            </div>
          </div>
        </div>
        <div class="product-list">
          <div class="product-list__title">
            <p>Eye Surgery & IOL</p>
          </div>
          <div class="product-list__items">
            <div class="product">
              <div class="product__image">
                <img src="/assets/images/product-3.jpg" alt="" />
              </div>
              <div class="product__description">
                <p>
                  Pellentesque consequat nulla et lorem fermentum, vitae
                  sagittis erat cursus. Sed nec fringilla turpis.
                </p>
              </div>
            </div>
          </div>
        </div>
        <div class="product-list">
          <div class="product-list__title">
            <p>Optical lab & Optical lenses</p>
          </div>
          <div class="product-list__items">
            <div class="product">
              <div class="product__image">
                <img src="/assets/images/product-4.jpg" alt="" />
              </div>
              <div class="product__description">
                <p>
                  Pellentesque consequat nulla et lorem fermentum, vitae
                  sagittis erat cursus. Sed nec fringilla turpis.
                </p>
              </div>
            </div>
            <div class="product">
              <div class="product__image">
                <img src="/assets/images/product-5.jpg" alt="" />
              </div>
              <div class="product__description">
                <p>
                  Pellentesque consequat nulla et lorem fermentum, vitae
                  sagittis erat cursus. Sed nec fringilla turpis.
                </p>
              </div>
            </div>
            <div class="product">
              <div class="product__image">
                <img src="/assets/images/product-6.jpg" alt="" />
              </div>
              <div class="product__description">
                <p>
                  Pellentesque consequat nulla et lorem fermentum, vitae
                  sagittis erat cursus. Sed nec fringilla turpis.
                </p>
              </div>
            </div>
            <div class="product">
              <div class="product__image">
                <img src="/assets/images/product-7.jpg" alt="" />
              </div>
              <div class="product__description">
                <p>
                  Pellentesque consequat nulla et lorem fermentum, vitae
                  sagittis erat cursus. Sed nec fringilla turpis.
                </p>
              </div>
            </div>
            <div class="product">
              <div class="product__image">
                <img src="/assets/images/product-8.jpg" alt="" />
              </div>
              <div class="product__description">
                <p>
                  Pellentesque consequat nulla et lorem fermentum, vitae
                  sagittis erat cursus. Sed nec fringilla turpis.
                </p>
              </div>
            </div>
          </div>
        </div>
        <div class="product-list">
          <div class="product-list__title">
            <p>Contact lenses & accessories</p>
          </div>
          <div class="product-list__items">
            <div class="product">
              <div class="product__image">
                <img src="/assets/images/product-9.jpg" alt="" />
              </div>
              <div class="product__description">
                <p>
                  Pellentesque consequat nulla et lorem fermentum, vitae
                  sagittis erat cursus. Sed nec fringilla turpis.
                </p>
              </div>
            </div>
            <div class="product">
              <div class="product__image">
                <img src="/assets/images/product-10.jpg" alt="" />
              </div>
              <div class="product__description">
                <p>
                  Pellentesque consequat nulla et lorem fermentum, vitae
                  sagittis erat cursus. Sed nec fringilla turpis.
                </p>
              </div>
            </div>
          </div>
        </div>
        <div class="product-list">
          <div class="product-list__title">
            <p>Eye wears & sunglasses</p>
          </div>
          <div class="product-list__items">
            <div class="product">
              <div class="product__image">
                <img src="/assets/images/product-11.jpg" alt="" />
              </div>
              <div class="product__description">
                <p>
                  Pellentesque consequat nulla et lorem fermentum, vitae
                  sagittis erat cursus. Sed nec fringilla turpis.
                </p>
              </div>
            </div>
            <div class="product">
              <div class="product__image">
                <img src="/assets/images/product-12.jpg" alt="" />
              </div>
              <div class="product__description">
                <p>
                  Pellentesque consequat nulla et lorem fermentum, vitae
                  sagittis erat cursus. Sed nec fringilla turpis.
                </p>
              </div>
            </div>
            <div class="product">
              <div class="product__image">
                <img src="/assets/images/product-13.jpg" alt="" />
              </div>
              <div class="product__description">
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
/* Product */
.products__title {
  margin-top: 40px;
  margin-bottom: 20px;
  font-size: 25px;
  font-weight: 700;
  color: var(--primary-color);
}
.products__description {
  max-width: 480px;
  font-size: 12px;
}
/* Product List */
.product-list {
  margin-top: 60px;
}
.product-list__title {
  margin-bottom: 20px;
  font-weight: 700;
  color: var(--primary-color);
}
.product-list__items {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr 1fr;
  gap: 20px;
}
/* Product */
.product {
  padding: 10px;
  background-color: #fff;
  border-radius: 10px;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.4);
}
.product__image {
  margin-bottom: 10px;
}
.product__image img {
  width: 100%;
}
.product__description {
  margin-bottom: 10px;
  font-size: 12px;
  color: #6c6c6c;
}
</style>
