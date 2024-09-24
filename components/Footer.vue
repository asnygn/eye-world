<template>
  <div class="main-footer">
    <Container>
      <div class="main-footer__content">
        <div class="main-footer__title">
          <p>Address</p>
        </div>
        <div class="main-footer__body">
          <div class="main-footer__description">
            <p>Eye World Trading Distribution Center</p>
          </div>
          <div class="main-footer__address">
            <p>
              No., 52/53, Phan Chaet Wun U Shwe Oh Road, Industrial Zone 3,
              Hlaing Tharyar Tsp., Yangon 11401, Myanmar
            </p>
          </div>
          <div class="main-footer__link">
            <div>
              <span><img src="/assets/images/phone.svg" alt="" /></span>
              <p>09 777 701 379</p>
            </div>
            <div>
              <span><img src="/assets/images/message.svg" alt="" /></span>
              <p>info@eyeworldgroup.com</p>
            </div>
          </div>
        </div>
      </div>
    </Container>
  </div>
</template>

<style scoped>
.main-footer {
  padding-bottom: 80px;
}
.main-footer__title {
  margin-bottom: 20px;
  font-weight: 500;
}
.main-footer__content {
  padding-top: 40px;
  border-top: 1px solid #c0c0c0;
}
.main-footer__body {
  display: flex;
  gap: 100px;
  flex: 1;
}
.main-footer__description {
  flex: 1;
  font-size: 14px;
}
.main-footer__address {
  flex: 1;
  font-size: 14px;
}
.main-footer__link {
  flex: 1;
  font-size: 14px;
}
.main-footer__link div {
  display: flex;
  margin-bottom: 5px;
}
.main-footer__link span {
  margin-right: 5px;
  width: 20px;
}
</style>
