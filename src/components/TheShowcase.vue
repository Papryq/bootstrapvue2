<template>
    <section class="bg-dark text-light p-5 text-center text-sm-start">
        <div class="container">
          <div class="d-sm-flex align-items-center justify-content-between">
            <div class="showcase-left">
              <h1>Become More <span class="text-warning">Athletic!</span></h1>
              <p class="lead my-4 showcase-left">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Autem explicabo voluptatibus voluptatum officia quaerat architecto esse nesciunt tempore deserunt animi, perferendis, similique qui? Nobis ex quod in doloribus voluptatibus voluptates! </p>
              <button class="btn btn-primary btn-lg btn-showcase" data-bs-toggle="modal" data-bs-target="#enroll">Start right now!</button>
            </div>
            <img class="img-fluid w-50 d-none d-sm-block showcase-right" src='@/assets/photos/Selfie.svg' alt="">
          </div>
        </div>
     </section>
</template>

<script>
export default {
    name: 'TheShowcase'
}
</script>
