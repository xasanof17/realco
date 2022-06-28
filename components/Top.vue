<template>
  <div class="header-top flex items-center justify-center py-2.5">
    <div class="container">
      <div class="header-top__content flex items-center justify-end">
        <div
          class="header-top__content-inner flex items-center justify-between w-3/5 lg:w-4/6"
        >
          <p>Get your dream house in a week.</p>
          <button><img src="../assets/close.svg" alt="close" /></button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "NuxtTop",
};
</script>

<style scoped>
.header-top {
  background: var(--green);
  /* height: 40px; */
}

.header-top__content-inner p {
  font-weight: 400;
  font-size: 17px;
  line-height: 21px;
  color: var(--white);
}
.header-top__content-inner button{
  display: flex;
  align-items: center;
  justify-content: center;
}
.header-top__content-inner button img{
  width: 30px;
  height: 30px;
  pointer-events: none;
  user-select: none;
}
</style>
