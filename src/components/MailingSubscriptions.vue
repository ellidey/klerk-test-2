<script setup>

</script>

<template>
<div class="mailing__subscriptions">

<!-- subscription 1 -->
  <div class="mailing__subscription">
    <div>
      <span class="subscription__subtitle">Перед рассветом</span>
      <h3 class="subscription__title">Утренний бухгалтер</h3>
        <div class="subscription__text">
          Самые важные новости и события за день. Кратко, по делу, структурировано.
        </div>
      <div class="subscription__items">
        <span>
          <img src="../assets/img/check.svg" alt="-">
          Новости для бухгалтеров, ИП и директора
        </span>
        <span>
          <img src="../assets/img/check.svg" alt="-">
          Подборка статей за день
        </span>
      </div>

      <div class="subscription__checkbox">
        <label class="switch" for="subscription-one">
          <input type="checkbox" id="subscription-one" />
          <span class="slider round"></span>
        </label>
        <span class="text">Уже получает 59 342 человек</span>
      </div>
    </div>

    <div class="subscription__img">
      <img src="../assets/img/subscription-one.png" alt="one">
    </div>
  </div>


  <!-- subscription 2 -->
  <div class="mailing__subscription">
    <div>
      <span class="subscription__subtitle">После заката</span>
      <h3 class="subscription__title">Ночной бухгалтер</h3>
      <div class="subscription__text">
        Самая краткая газета о налогах и бухучете в мире — современная рассылка для чтения.
      </div>
      <div class="subscription__items">
        <span>
          <img src="../assets/img/check.svg" alt="-">
          Анализ, оценка и только самое главное
        </span>
        <span>
          <img src="../assets/img/check.svg" alt="-">
          Лучшие комменты юзеров в обзоре
        </span>
      </div>

      <div class="subscription__checkbox">
        <label class="switch" for="subscription-two">
          <input type="checkbox" id="subscription-two" />
          <span class="slider round"></span>
        </label>
        <span class="text">Уже получает 37 480 человек</span>
      </div>
    </div>

    <div class="subscription__img">
      <img src="../assets/img/subscription-two.png" alt="two">
    </div>
  </div>

  <!-- subscription 3 -->
  <div class="mailing__subscription">
    <div>
      <span class="subscription__subtitle">Раз в две недели</span>
      <h3 class="subscription__title">Ножницы скидок</h3>
      <div class="subscription__text">
        Подборка самых выгодных и полезных спецпредложений от надежных компаний.
      </div>
      <div class="subscription__items">
        <span>
          <img src="../assets/img/check.svg" alt="-">
          Акции и скидки от лидеров рынка
        </span>
        <span>
          <img src="../assets/img/check.svg" alt="-">
          Те, кто подписался – экономят много денег
        </span>
      </div>

      <div class="subscription__checkbox">
        <label class="switch" for="subscription-three">
          <input type="checkbox" id="subscription-three" />
          <span class="slider round"></span>
        </label>
        <span class="text">Уже получает 92 118 человек</span>
      </div>
    </div>

    <div class="subscription__img">
      <img src="../assets/img/subscription-three.png" alt="three">
    </div>
  </div>


  <!-- subscription 4 -->
  <div class="mailing__subscription">
    <div>
      <span class="subscription__subtitle">По мере появления анонсов</span>
      <h3 class="subscription__title">Чемодан вебинаров</h3>
      <div class="subscription__text">
        Подборка с анонсами бесплатных вебинаров
        на самые топовые темы при участии экспертов.
      </div>
      <div class="subscription__items">
        <span>
          <img src="../assets/img/check.svg" alt="-">
          <b>Никогда не пришлем платные вебинары</b>
        </span>
        <span>
          <img src="../assets/img/check.svg" alt="-">
          Подборка топовых тем для вебинаров
        </span>
      </div>

      <div class="subscription__checkbox">
        <label class="switch" for="subscription-four">
          <input type="checkbox" id="subscription-four" />
          <span class="slider round"></span>
        </label>
        <span class="text">Уже получает 92 082 человек</span>
      </div>
    </div>

    <div class="subscription__img">
      <img src="../assets/img/subscription-four.png" alt="four">
    </div>
  </div>
</div>
</template>