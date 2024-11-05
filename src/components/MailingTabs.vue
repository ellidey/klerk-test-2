<script setup>

import {ref} from "vue";

const active = ref('send')
</script>

<template>
  <div class="mailing__tabs flex justify-center gap-8 mt-10">
    <button
        class="mailing__tab"
        :class="{ active: active === 'send' }"
        @click="active = 'send'"
    >
      Рассылки
    </button>
    <button
        class="mailing__tab"
        :class="{ active: active === 'social' }"
        @click="active = 'social'"
    >
      Соцсети
    </button>
    <button
        class="mailing__tab"
        :class="{ active: active === 'message' }"
        @click="active = 'message'"
    >
      Мессенджеры
    </button>
  </div>
</template>