<template>
<div class= "container">
    <div class="header">
      <div>
        <div class="title-1">Reliable,efficient delivery</div>
        <div class="title-2"> Powered by Technology</div>
        <div class="title-3"> Our Artificial Intelligence powered tools use millions of project data <br>points to
          ensure that your project is
          successful</div>
      </div>
    </div>
    <div class="cards-container">
      <div class="card-container end">
        <div class="card">
          <div class="hr-cyan"></div>
          <div class="card-header">Supervisor</div>
          <div class="card-title">Monitors activity to identify project roadblocks</div>
          <div class="card-image"><img src="./assets/icon-supervisor.svg"></div>
        </div>
      </div>
      <div class="double-card-container">
        <div class="card">
          <div class="hr-red"></div>
          <div class="card-header">Team Builder</div>
          <div class="card-title"> Scans our talent network to create the optimal team for your project</div>
          <div class="card-image"><img src="./assets/icon-team-builder.svg"></div>
        </div>
        <div class="card">
          <div class="hr-orange"></div>
          <div class="card-header">Karma</div>
          <div class="card-title">Regularly evaluates our talent to ensure quality</div>
          <div class="card-image"><img src="./assets/icon-karma.svg"></div>
        </div>
      </div>
      <div class="card-container start">
        <div class="card ">
          <div class="hr-blue"></div>
          <div class="card-header">Calculator</div>
          <div class="card-title">Uses data from past projects to provide better delivery estimates</div>
          <div class="card-image"><img src="./assets/icon-calculator.svg"></div>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
body {
  margin: 0;
}
.container {
  width: 100%;
  height: 100vh;
  display: flex;
  flex-flow: column;
  align-items: center;
  justify-content: flex-start;
  overflow-y: scroll;
  background-color: rgb(250, 250, 250);
}

.header {
  height: 25%;
  width: 100%;
  font-family: "Poppins";
  font-size: 35px;
  display: flex;
  flex-flow: column;
  align-items: center;
  justify-content: flex-start;
  text-align: center;
  padding-top:10px;
  padding-bottom:20px
}

.header .title-1 {
  font-size: 23px;
  font-weight: 200;
  color: hsl(229, 6%, 66%);
  margin-top: 5px;
}

.header .title-2 {
  font-size: 23px;
  color: hsl(234, 12%, 34%);
  margin-top: 5px;
  font-weight: 600;
}

.header .title-3 {
  font-size: 12px;
  color: hsl(229, 6%, 66%);
  margin-top: 10px;
}

.cards-container {
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
}

.cards-container .end {
  align-items: flex-end;
}

.cards-container .start {
  align-items: flex-start;
}

.double-card-container {
  width: 100%;
  height: 100%;
  display: flex;
  flex-flow: column;
  align-items: center;
  justify-content: space-around;
}

.double-card-container .card {
  margin-bottom: 30px;
}

.card {
  margin-bottom: 90px;
}

.card-container {
  width: 100%;
  height: 100%;
  display: flex;
  flex-flow: column;
  justify-content: flex-end;
}

.card {
  background-color: white;
  width: 300px;
  height: 180px;
  font-size: 20px;
  box-shadow: 0px 5px 5px 2px #e6e7eb;
}

.card-header {
  font-family: "Poppins";
  font-size: 20px;
  padding-top: 20px;
  padding-left: 30px;
  color: hsl(234, 12%, 34%);
}

.hr-cyan {
  width: 100%;
  height: 5px;
  background-color: hsl(180, 62%, 55%);
}

.hr-red {
  width: 100%;
  height: 5px;
  background-color: hsl(0, 78%, 62%);
}

.hr-blue {
  width: 100%;
  height: 5px;
  background-color: hsl(212, 86%, 64%);
}

.hr-orange {
  width: 100%;
  height: 5px;
  background-color: hsl(34, 97%, 64%);
}

.card-title {
  font-family: "Poppins";
  font-size: 13px;
  padding-left: 30px;
  padding-top: 10px;
  color: hsl(229, 6%, 66%);
}

.card-image {
  text-align: right;
}

.card-image img {
  width: 40px;
  padding-right: 20px;
}

@media screen and (max-width: 900px) {
  .container {
    overflow: scroll;
  }

  .cards-container {
    flex-flow: column;
  }
  .cards-container .end {
    align-items: center;
  }
  
  .cards-container .start {
    align-items: center;
  }
  .card {
    width: 270px;
    margin: 10px;
  }
 
}
</style>