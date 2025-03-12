<template>
  <div class="movie-add-form">
    <h3>Add a new movie</h3>
    <form class="add-form d-flex">
      <input type="text" class="form-control new-movie-label" placeholder="What movie?" />
      <input
        type="text"
        class="form-control new-movie-label"
        placeholder="How many times watched?"
      />
      <button class="btn btn-outline-dark" type="submit">Add</button>
    </form>
  </div>
</template>
<script>
export default {};
</script>

<style>
.movie-add-form {
  margin-top: 2rem;
  padding: 1.5rem;
  background: #fcfaf5;
  border-radius: 4px;
  box-shadow: 15px 15px 15px rgba(0, 0, 0, 0.15);
}
</style>
