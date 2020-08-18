<template>
  <div class="home">
    <div class="container">
  <div class="row">
    <div class="col">
      <h1>Pourquoi les chiens sont les meilleurs ?</h1>
    </div>
  </div>
</div>
<div class="container">
<div class="row">
<div class="col">
  <h2>Parce qu'ils sont beaux !</h2>
</div>
</div>
</div>
<div class="container">
  <div class="row">
    <div class="col">
      <card1/>
    </div>
    <div class="col">
      <card2/>
    </div>
    <div class="col">
      <card3/>
    </div>
  </div>
</div>
    <div class="container">
        <div class="row">
            <div class="col">
                <h2>Parce qu'ils sont intelligents !</h2>
              </div>
        </div>
      </div>
    <div class="container">
        <div class="row">
            <div class="col">
                <selectedcolor/>
              </div>
          </div>
        </div>
        <div class="container">
          <div class="row">
            <div class="col">
              <h2>On finit par créer un lien spécial avec eux</h2>
            </div>
          </div>
        </div>
        <div class="container">
          <div class="row">
            <div class="col">
              <cycle/>
            </div>
          </div>
        </div>
        <div class="container">
          <div class="row">
            <div class="col">
              <h2>Alors, convaincu ?</h2>
            </div>
          </div>
        </div>
        <div class="container">
          <div class="row">
            <div class="col">
              <div class="btnclick"><usage/></div>
            </div>
          </div>
        </div>
      </div>
    </template>
    <script>
    import card1 from '../components/card1.vue';
    import card2 from '../components/card2.vue';
    import card3 from '../components/card3.vue';
    import usage from '../components/usage.vue';
    import selectedcolor from '../components/selectedcolor.vue';
    import cycle from '../components/cycle.vue';

    export default {
      components: {
        card1,
        card2,
        card3,
        usage,
        selectedcolor,
        cycle
      },
    }
    </script>
    <style>
      h1 {
        text-align: center;
        color: DarkRed;
      }
      h2 {
        text-align: center;
        color: FireBrick;
      }
    </style>
