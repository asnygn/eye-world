<template>
  <Header />
  <main>
    <section class="contact">
      <Container>
        <div class="contact__content">
          <div class="contact__image">
            <img src="/assets/images/contact.jpg" alt="" />
          </div>
          <div class="contact__form">
            <div class="contact__title">
              <p>Let's get in touch...</p>
            </div>
            <div class="contact__description">
              <p>or just reach us via info@eyeworldgroup.com</p>
            </div>
            <div class="contact-form">
              <form>
                <div class="form-field">
                  <label for="name">Full Name</label>
                  <input type="text" name="name" class="input-text" />
                </div>
                <div class="form-field">
                  <label for="email">Email Address</label>
                  <input type="text" name="email" class="input-text" />
                </div>
                <div class="form-field">
                  <label for="phone">Phone Number</label>
                  <input type="text" name="phone" class="input-text" />
                </div>
                <div class="form-field">
                  <div>
                    <label for="message">Message</label>
                    <textarea name="message" class="input-textarea"></textarea>
                  </div>
                </div>
                <div class="form-actions">
                  <button class="btn" type="submit">Submit</button>
                </div>
              </form>
            </div>
          </div>
        </div>
      </Container>
    </section>
  </main>
  <Footer />
</template>

<style scoped>
/* Contact */
.contact__content {
  display: flex;
  flex-direction: row;
  gap: 40px;
  margin-top: 80px;
  margin-bottom: 80px;
}
.contact__title {
  flex: 1;
  margin-bottom: 10px;
  font-size: 24px;
  font-weight: 700;
  color: var(--primary-color);
}
.contact__description {
  flex: 1;
  font-size: 14px;
  font-weight: 500;
}
/* Contact Form */
.contact-form {
  margin-top: 40px;
}
</style>
