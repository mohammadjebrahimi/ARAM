<template>
  <div class="flex column items-center login q-pa-xl">
    <div class="flex items-start full-width">
      <q-icon name="arrow_back"  size="2em" />
    </div>
    <q-img class="login__image" src="/src/assets/Group_3552.svg" />
    <div class="flex column full-width login__form">
      <q-input mask="(####) ### - ####" filled bg-color="white" class="full-width " placeholder="(0915) 235 - 9821"
        dense="true" />

      <q-btn class="full-width login__form-btn" label="ورود صاحب كار" />
    </div>
  </div>
</template>

<script setup>
</script>
<style lang="scss" scoped>
.login {
  gap: 2rem;

  &__form {
    gap: 1rem;

    &-btn {
      background-color: #da0037;
      color: white;
      border-radius: 5px;
    }
  }

  &__image {
    max-height: 477px;
    max-height: 477px;
  }
}
</style>

