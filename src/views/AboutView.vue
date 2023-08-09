<template>
  <div class="about">
    <h1>Vue Todos</h1>
    <span>
      <p>
        Vue Todos is a CRUD Todo tracking application created for a Vue 3 Crash Course by John Komarnicki.
      </p>
      <p>
        Track your daily task's using this todo tracker with abilities to save, complete, edit & delete todos.
      </p>
      <p>
        Feel free to add on to this application with functionalities such as the ability to drag and reorder todos, animate creation/deletion of todos or even create this into a full stack application with the ability to have different lists for different days of tracking todos!
      </p>
    </span>
  </div>
  
  

  

  
</template>

<style lang="scss" scoped>
.about {
  padding: 15px 25px;

  h1 {
    margin-bottom: 15px;
  }

  span p {
    margin-bottom: 10px;
  }
}
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
