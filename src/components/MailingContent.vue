<script setup>

import MailingSubscriptions from "@/components/MailingSubscriptions.vue";
</script>

<template>
  <div class="mailing__content">
      <h2 class="mt-5 mb-5">Выберите рассылки, которые подходят именно вам</h2>

      <div class="mailing__mail">
        <input type="text" class="mailing__input" placeholder="Электронная почта">
        <button class="mailing__btn">Подписаться</button>
        <button class="mailing__btn small">
          <svg width="9" height="14" viewBox="0 0 9 14" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M0.349976 12.355L5.69331 7L0.349976 1.645L1.99498 0L8.99498 7L1.99498 14L0.349976 12.355Z" fill="white"/>
          </svg>
        </button>
      </div>
      <div class="mailing__subscribe-all">
        <label class="switch small" for="checkbox">
          <input type="checkbox" id="checkbox" />
          <span class="slider round"></span>
        </label>
        <span class="text">Подписаться на все рассылки</span>
      </div>

    <mailing-subscriptions />
  </div>
</template>