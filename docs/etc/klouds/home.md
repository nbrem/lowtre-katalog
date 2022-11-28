---
hide:
    - toc
---


<div class="div-cleanbody">
    <h1><b>Déposez votre ressources</b> dans un espace de stockage commun.
        <img style="height:100px; float: right; margin:25px; filter: grayscale(60%);" src="https://cdn-icons-png.flaticon.com/512/892/892311.png">
    </h1>
    <hr>
    <br>
    <div class="card-grid" data-ressource-cards-container></div>
    <br>
    <a id="EditBtn" class="ksln-btn" href="" target="_blank" style="float: right"><i class="fa-solid fa-pencil"></i> Ajouter ou modifier un espace de stockage</a>
    <br>
    <hr>
</div>

<template data-ressource-template>
    <div> 
        <div class="card container ksln-card">
            <a target="_blank" data-link>
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
    <!-- Personnal Konsilion JS -->
    <script type="text/javascript" src="https://konsilion.github.io/katalog-setup/js/klouds.js"></script>
    <script type="text/javascript" src="https://konsilion.github.io/katalog-setup/js/datami.js"></script>
    <!-- DATAMI WIDGET'S APP.JS SCRIPT -->
    <script src="https://datami-widget.multi.coop/js/app.js" type="text/javascript" defer></script>
</head>