<template>
  <li class="list-group-item d-flex justify-content-between">
    <span class="list-group-item-label">Squid Game</span>
    <input type="number" class="list-group-item-input" defaultValue="811" />
    <div class="d-flex justify-content-center align-items-center">
      <button type="button" class="btn-cookie btn-sm">
        <i class="fas fa-cookie"></i>
      </button>

      <button type="button" class="btn-trash btn-sm">
        <i class="fas fa-trash"></i>
      </button>

      <i class="fas fa-star"></i>
    </div>
  </li>
</template>

<script>
export default {};
</script>

<style scoped>
.list-group-item {
  padding: 15px 20px;
  border-bottom: 1px solid #3d5a80;
}

.list-group-item:last-child {
  border-bottom: none;
}

.list-group-item span {
  line-height: 35px;
  font-size: 20px;
  cursor: pointer;
  width: 550px;
}
</style>
