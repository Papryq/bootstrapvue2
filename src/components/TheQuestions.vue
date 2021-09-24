<template>
        <section class="p-5">
          <div class="container">
            <h2 class="text-center mb-4">Most Asked Questions</h2>
            <div class="accordion accordion-flush" id="questions">
              <!--Item1-->
               <div class="accordion-item">
                <h2 class="accordion-header" id="flush-headingOne">
                  <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#question-one">
                    How should I start?
                  </button>
                </h2>
              </div>
                <div id="question-one" class="accordion-collapse collapse" data-bs-parent="#questions">
                  <div class="accordion-body">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Perferendis quo ad deserunt et, non eveniet similique, repudiandae reiciendis in itaque dignissimos doloribus incidunt. Neque optio minus quibusdam assumenda tenetur adipisci temporibus facilis! Eius quasi aperiam repellendus deleniti quis esse omnis excepturi recusandae, odio voluptatum maiores corrupti consequuntur reiciendis! Quam, consectetur?</div>
                </div>
              <!--Item2-->
               <div class="accordion-item">
                <h2 class="accordion-header" id="flush-headingTwo">
                  <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#question-two">
                    Which sport should I choose?
                  </button>
                  </h2>
                </div>

                <div id="question-two" class="accordion-collapse collapse" data-bs-parent="#questions">
                  <div class="accordion-body">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Dolor obcaecati odit consequuntur iste recusandae quisquam iure dolores saepe fuga, optio porro velit incidunt atque fugit soluta facere. Dignissimos, odio ullam. </div>
                </div>
              <!--Item3-->
               <div class="accordion-item">
                <h2 class="accordion-header" id="flush-headingThree">
                  <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#question-three">
                    What to do with lack of motivation?
                  </button>
                  </h2>
                </div>
                <div id="question-three" class="accordion-collapse collapse" data-bs-parent="#questions">
                  <div class="accordion-body">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Non nemo asperiores expedita molestias incidunt sapiente itaque nulla unde labore nihil. Nostrum vitae, architecto doloribus voluptates sapiente quas non perspiciatis dolorem porro quibusdam quia dolorum error nihil reiciendis fuga sed explicabo!</div>
                </div>
            </div>
          </div>
        </section>
</template>

<script>
export default {
    name: 'TheQuestions',
}
</script>