<template>
  <div>
   <header></header>
  <section>
     <main>
    <div>
      <ul>
        <li>computer</li>
        <li>laptop</li>
        <li>cpu</li>
      </ul>
    </div>
    <div>
      <ol>
        <li>Location</li>
      </ol>
    </div>
   </main>
   <aside>
    <h1>Heading</h1>
    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Deleniti voluptatem quos fuga eaque esse voluptas quod doloribus praesentium quis maiores, ab laborum dolore voluptatum error, beatae saepe id tempore alias?</p>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nemo culpa possimus porro, odit quam quis quas ducimus nulla officiis nam temporibus quos ea fugit mollitia perspiciatis, necessitatibus maiores perferendis rem.</p>
    <p class="pad">Lorem ipsum dolor sit amet consectetur adipisicing elit. Eaque mollitia eius eos! Assumenda, minima eligendi quam ut commodi non inventore quia qui eos facilis cumque vel mollitia eius corporis vitae.</p>
    <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quibusdam, dicta. Consequuntur temporibus sunt numquam soluta accusamus odit, fugit sequi ducimus placeat libero quis aut corporis amet praesentium veniam quos alias.</p>
   </aside>
  </section>
  <div class="btm"></div>
  </div>
</template>
<style>
header{
  background-color: black;
  height: 100px;
  flex-wrap: wrap;
  margin: 1px;
}
section{
  height: auto;
 
  display: flex;
  flex-wrap: wrap;
}
main{
  flex: 0.4;
  flex-wrap: wrap;
  height: 74vh;

 
}
main div{
  background-color: rgb(148, 108, 185);
  flex: 0.4;
  height: 37vh;
  margin: 1px;
}
aside{
  background-color: rgb(199, 195, 189);
  flex: 0.6;
  flex-wrap: wrap;
  height: 74vh;
  margin: 1px;
}
 .pad{
  padding: 20px;
  margin: 10px;
}
.btm{
  background-color: rgb(100, 100, 98);
  flex-wrap: wrap;
  height: 40vh;
  margin: 1px;
}
aside h1{
  padding: 24px;
  margin: 4px;
  box-sizing: border-box;
}
@media (max-width:800px){
  header{
    flex: 100%;
    min-width: 600;
  }
   section{
    flex: 100%;
    min-width: 600;
  }
   main{
    flex: 100%;
    min-width: 600;
  }
   main div{
    flex: 100%;
    min-width: 600;
  }
  aside{
    flex: 100%;
    min-width: 600;
  }
   .btm{
    flex: 100%;
    min-width: 600;
  }
}
</style>