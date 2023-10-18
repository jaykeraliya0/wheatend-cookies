<script setup></script>

<template>
  <button>Shop Now</button>
</template>

<style scoped>
button {
  width: fit-content;
  display: flex;
  padding: 14px 12px;
  justify-content: center;
  align-items: center;
  gap: 6px;
  border-radius: 8px;
  background: var(--yellow-pri, #fddc2e);
  border: none;
  color: #14141e;
  font-family: Inter;
  font-size: 18px;
  font-style: normal;
  font-weight: 500;
  line-height: normal;
}
</style>

<script>
export default {
  name: "Button",
};
</script>
