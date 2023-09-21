<script>

export default {

  data() {

    return {

      message : 'Jumbotron'

    }

  }

}
</script>

<template>

  <div class="jumbo">
    {{ message }}
  </div>
  
</template>

<style>

.jumbo {
    height: 300px;
    border: 1px solid lightpink;
    padding: 5rem;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 2rem;
    color: lightseagreen;
}

</style>