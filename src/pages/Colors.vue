<template>
  <q-page class="q-pa-xl">
    <section class="q-mb-xl">
      <div class="text-h4">Headings</div>
      <q-separator class="q-my-md" />
      <div class="bg-primary text-yellow">primary</div>
      <div class="bg-secondary text-white">secondary</div>
      <div class="bg-accent text-white">accent</div>
      <div class="bg-dark text-white">dark</div>
      <div class="bg-positive text-white">positive</div>
      <div class="bg-negative text-white">negative</div>
      <div class="bg-info text-white">info</div>
      <div class="bg-warning text-white">warning</div>
      <div class="bg-orange-4">orange-4</div>
      <div class="bg-light-green-6">light-green-6</div>
      <div class="bg-blue-grey-1">blue-grey-1</div>
      <div class="bg-error">error</div>
      <p>Variables</p>
    </section>
    <section class="q-mb-xl">
      <div class="text-h4">Components</div>
      <div class="q-pa-md q-gutter-sm">
        <q-btn color="white" text-color="black" label="Standard" />
        <q-btn color="primary" label="Primary" />
        <q-btn color="secondary" label="Secondary" />
        <q-btn color="amber" glossy label="Amber" />
        <q-btn color="brown-5" label="Brown 5" />
        <q-btn color="deep-orange" glossy label="Deep Orange" />
        <q-btn color="purple" label="Purple" />
        <q-btn color="black" label="Black" />
        <q-btn color="error" label="Error" />
      </div>
    </section>
  </q-page>
</template>

<script setup></script>

<style lang="scss" scoped>
p {
  color: $red;
  background-color: $grey-5;
}
.text-error {
  // 컬러 명칭 생성
  color: $red;
}
.bg-error {
  background: $red;
}
</style>
