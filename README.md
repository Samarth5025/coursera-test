<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>menu</title>
<style>
* {
  box-sizing: border-box;
}
h1 {
  margin-bottom: 50px;
  margin-top: 50px;
  font-family: cursive; 
}

section {
  border: 1px solid black;
  background-color:grey;
  width: 90%;
  height: 150px;
  margin-right: auto;
  margin-left: auto;
  font-family:comic sans ms, comic-sans, cursive;
  color: black;
}
#beef{
  background-color: pink; 
}
#chicken{
  background-color: red;
}
#sushi{
  background-color: yellow;
}
.row {
  width: 100%;
}
@media (min-width: 1200px) {
  .col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12 {
    float: left;
  
  }
  .col-lg-1 {
    width: 8.33%;
  }
  .col-lg-2 {
    width: 16.66%;
  }
  .col-lg-3 {
    width: 25%;
  }
  .col-lg-4 {
    width: 33.33%;
  }
  .col-lg-5 {
    width: 41.66%;
  }
  .col-lg-6 {
    width: 50%;
  }
  .col-lg-7 {
    width: 58.33%;
  }
  .col-lg-8 {
    width: 66.66%;
  }
  .col-lg-9 {
    width: 74.99%;
  }
  .col-lg-10 {
    width: 83.33%;
  }
  .col-lg-11 {
    width: 91.66%;
  }
  .col-lg-12 {
    width: 100%;
  }
}

@media (min-width: 992px) and (max-width: 1199px) {
  .col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-11, .col-md-12 {
    float: left;
  }
  .col-md-1 {
    width: 8.33%;
  }
  .col-md-2 {
    width: 16.66%;
  }
  .col-md-3 {
    width: 25%;
  }
  .col-md-4 {
    width: 33.33%;
  }
  .col-md-5 {
    width: 41.66%;
  }
  .col-md-6 {
    width: 50%;
  }
  .col-md-7 {
    width: 58.33%;
  }
  .col-md-8 {
    width: 66.66%;
  }
  .col-md-9 {
    width: 74.99%;
  }
  .col-md-10 {
    width: 83.33%;
  }
  .col-md-11 {
    width: 91.66%;
  }
  .col-md-12 {
    width: 100%;
  }
}

</style>
</head>
<body>
<h1 style="text-align: center;">Our Menu</h1>

<div class="row">
  <div class="col-lg-4 col-md-6">
  <section>
    <article id="chicken">Chicken</article>
    <article>This mouth watering dish is a perfect blend of spices that take you  to another world. Its a blast of flavours. so much juicy that it melts in as soon as it is placed in your mouth. The best in the whole town.<</article>
  </section>
  </div>
  <div class="col-lg-4 col-md-6">
    <section>
    <article id="beef">Beef</article>
    <article>This a exclusive dish made here. Many tourist visit this town only for this dish. It's a tourist attraction. The chief  chef takes personal care to make this dish. The dish is ancient hence special protocols are taken in consideration.
    </article>
  </section>
</div>
  <div class="col-lg-4 col-md-6">
    <section>
      <article id="sushi">Sushi</article>
      <article>OMG!. Its the perfect dish that you can order. This continental is favourite. It's a perfect dish to enchance the working of your taste buds. we serve this dish to all our customers in a special way. to know what it is you need to take out time to visit us.</article>
    </section>
  </div>
  
</div>

</body>
</html>
