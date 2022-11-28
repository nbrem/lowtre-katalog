---
hide:
    - toc
    - title
---

<div id="IndexBloc" class="div-cleanbody">
    <h1><b>Trouvez dans un Katalog</b> les ressources spécifiques à votre besoin.
        <img style="height:100px; float: right; margin: 25px; filter: grayscale(60%);" src="https://cdn-icons-png.flaticon.com/512/2504/2504717.png">
    </h1>
    <hr>
    <input type="search" class="search-input" placeholder="Recherche ..." data-search>
    <br>
    <br>
    <div class="card-grid" data-ressource-cards-container></div>
    <br>
    <a id="EditBtn" class="ksln-btn" href="" target="_blank" style="float: right"><i class="fa-solid fa-pencil"></i> Ajouter ou modifier un Katalog de ressources</a>
    <br>
    <hr>
</div>

<div id="DatamiBloc" class="div-cleanbody hide" style="padding: 0px 50px;">
    <br><br>
    <a class="ksln-btn" onclick="document.location.reload(true)"><i class="fa-solid fa-person-walking-arrow-loop-left"></i></a>
    <hr>
    <div id="DatamiGrid"></div>
</div>

<template data-ressource-template>
    <div> 
        <div class="card container ksln-card">
            <a onclick="" data-link>
                <div class="ksln-img"><img src="" data-img></div>
                <div class="ksln-header" data-header></div>
                <div class="ksln-overlay">
                    <p data-descr></p>
                    <p style="border-top:solid 1px grey; padding-top:5px;" data-author></p>
                </div>
            </a>
        </div>
    </div>
</template>

<head>
    <meta charset="utf-8">
    <!--<meta http-equiv="X-UA-Compatible" content="IE=edge">  Cette balise est faite pour adapter Internet Explorer, mais elle semble désuette en 2022-->
    <!--<meta name="description" content="csv to datatables to csv">-->
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <script src="https://kit.fontawesome.com/f9666d4f53.js" crossorigin="anonymous"></script>
    <!-- Personnal Konsilion CSS -->
    <link rel="stylesheet" href="https://konsilion.github.io/katalog-setup/css/clean-body.css"/>
    <link rel="stylesheet" href="https://konsilion.github.io/katalog-setup/css/personnal-datami.css"/>
    <!-- Personnal Konsilion JS -->
    <script type="text/javascript" src="https://konsilion.github.io/katalog-setup/js/katalogs.js"></script>
    <script type="text/javascript" src="https://konsilion.github.io/katalog-setup/js/datami.js"></script>
    <!-- DATAMI WIDGET'S APP.JS SCRIPT -->
    <script src="https://datami-widget.multi.coop/js/app.js" type="text/javascript" defer></script>
</head>