<template>
    <div class="container">
        <div class="jesus" style="display: flex; justify-content: center;">
            <img src="../assets/images/jesus.gif" width="350px" />
        </div>
        <div class="despertador">
            <div class="despetador" style="justify-content: flex-start;">
                <img src="../assets/images/reloj.gif" width="70" />
            </div>
            <div class="gusano1">
                <img src="../assets/images/worm.gif" width="140px" />
            </div>
        </div>
        <div class="sanduchera" style="display: flex; align-items: center;">
            <img src="../assets/images/toaster.gif" width="120px" />
        </div>
        <div class="Tostadora" style="display: flex; align-items: flex-end;margin-bottom: -30px;">
            <img src="../assets/images/toaster.gif" width="160" />
        </div>
        <div class="Boca" style="display: flex; align-items: flex-start;margin-top: -30px;">
            <img src="../assets/images/mouth.gif" width="220px" style="margin-left: -30px;" />
        </div>
        <div class="despetador2" style="display: flex;justify-content: flex-end;align-items: flex-start;">

            <img src="../assets/images/reloj.gif" width="85" />
        </div>
        <div class="campana" style="display: flex;justify-content: flex-end; align-items: flex-end;">
            <img src="../assets/images/ring.gif" width="120" />
        </div>
        <div class="gusano2">
            <img src="../assets/images/worm.gif" width="140" />
        </div>
        <div class="sanduchera2">
            <img src="../assets/images/toaster.gif" width="120" />
        </div>
        <div class="campana2">
            <img src="../assets/images/ring.gif" width="140" />
        </div>
        <div class="boca2">
            <img src="../assets/images/mouth.gif" width="190px" />
        </div>
        <div class="despertador3">
            <img src="../assets/images/reloj.gif" width="80" />
        </div>
        <div class="gusano3">
            <img src="../assets/images/worm.gif" width="180" />
        </div>
        <div class="gusano4">
            <img src="../assets/images/worm.gif" width="180" />
        </div>
        <div class="sanduchera4">
            <img src="../assets/images/toaster.gif" width="190" />
        </div>
        <div class="Titulo">
            <h1>
                Homer's Web Page
            </h1>
        </div>
    </div>
</template>
<style scoped>
.container {
    background-color: #78BBCB;
    width: 100%;
    height: 800px;
    max-width: 1200px;
    display: grid;
    grid-template-columns: 1fr 1fr 1fr 1fr 1fr;
    grid-template-rows: 1fr 1fr 1fr 1fr 1fr;
    gap: 0px 0px;
    grid-auto-flow: row;
    grid-template-areas:
        "Titulo Titulo Titulo Titulo Titulo"
        "despertador sanduchera jesus gusano2 sanduchera2"
        "Tostadora Boca jesus campana2 boca2"
        "campana despetador2 jesus sanduchera4 despertador3"
        "gusano3 gusano4 . sanduchera4 .";
}

.jesus {
    grid-area: jesus;
}

.despertador {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    grid-template-rows: 1fr 1fr 1fr;
    gap: 0px 0px;
    grid-auto-flow: row;
    grid-template-areas:
        ". despetador ."
        "gusano1 gusano1 ."
        ". . .";
    grid-area: despertador;
}

.despetador {
    grid-area: despetador;
}

.gusano1 {
    grid-area: gusano1;
}

.sanduchera {
    grid-area: sanduchera;
}

.Tostadora {
    grid-area: Tostadora;
}

.Boca {
    grid-area: Boca;
}

.despetador2 {
    grid-area: despetador2;
}

.campana {
    grid-area: campana;
}

.gusano2 {
    grid-area: gusano2;
}

.sanduchera2 {
    grid-area: sanduchera2;
}

.campana2 {
    grid-area: campana2;
}

.boca2 {
    grid-area: boca2;
}

.despertador3 {
    grid-area: despertador3;
}

.gusano3 {
    grid-area: gusano3;
}

.gusano4 {
    grid-area: gusano4;
}

.sanduchera4 {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    grid-template-rows: 1fr 1fr 1fr;
    gap: 0px 0px;
    grid-auto-flow: row;
    grid-template-areas:
        ". . ."
        ". . ."
        ". . .";
    grid-area: sanduchera4;
}

.Titulo {
    grid-area: Titulo;
}

h1 {
    font-size: 60px;
    display: flex;
    justify-content: center;
    color: black;
    font-weight: bold;
    margin-top: 20px;
}
</style>