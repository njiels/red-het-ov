<template>
    <div>
      <a 
          href="https://forms.gle/qJayftASV1sf1Puw7"
          aria-label="Ga naar de petitie"
          title="Naar de petitie"
          class="ov-button font-primary uppercase"
      >
          Teken de petitie
      </a>
    </div>
  </template>
  
  <script>
  export default {
  
  }
  </script>
  
  <style>
  .ov-button{
    transition: all .5s;
    background-color: #2751C5;
    color: #F8DFDF;
    max-width: fit-content;
    padding: .25em;
    font-size: 4em;
    transform: skewY(-5deg);
    box-shadow: #0E1D46 5px 5px;
    line-height: .9em;
    margin-bottom: 2em;
  }
  .ov-button:hover{
    transition: all .5s;
    padding: .5em;
  }
  @media (max-width: 767px){
    .ov-button{
      font-size: 3em;
    }
  }
  </style>