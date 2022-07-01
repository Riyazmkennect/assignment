<template>
  <div>
    <header></header>
    <section>
        <aside></aside>
        <header1></header1>
        <main>
            <div></div>
            <div></div>
        </main>
    </section>
    <div class="mi"></div>

  </div>
</template>

<script>
export default {

}
</script>

<style>
header{
    background-color: black;
    flex-wrap: wrap;
    height: 60px;
     margin: 2px;
}

section{
    height: auto;
    display: flex;
     margin: 2px;
   
}
aside{
    flex: 0.2;
     margin: 2px;
     flex-wrap: wrap;
    height: 80.3vh;
    background-color: rgb(90, 88, 88);
}
header1{
    background-color: blueviolet;
    flex: 0.4;
    height: 80.3vh;
    flex-wrap: wrap;
     margin: 2px;
}
main{
    height: 80.2vh;
    flex-wrap: wrap;
    flex: 0.4;
    margin: 1px;
}
main div{
    background-color: blue;
    flex: 0.4;
    flex-wrap: wrap;
    height: 40vh;
    margin: 2px;
}
.mi{
    background-color: rgb(221, 198, 65);
    flex-wrap: wrap;
    height: 60px;
    margin: 1px;
}

@media (max-width:800px){
    header{
        flex: 100%;
        max-width: 600px;
    }
    section{
        flex: 100%;
        max-width: 600px;
    }
    aside{
        flex: 100%;
        max-width: 600px;
    }
    header1{
        flex: 100%;
        max-width: 600px;
    }
    main{
        flex: 100%;
        max-width: 600px;
    }
    main div{
        flex: 100%;
        max-width: 600px;
    }
    .mi{
        flex: 100%;
        max-width: 600px;
    }
}
</style>