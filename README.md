# infodigital-clase-04
<!DOCTYPE html>
<html lang="es">
    <head>
        <meta charset="utf-8" />
        <meta name="viewport" content="width=device-width, initial-scale=1" />
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-GLhlTQ8iRABdZLl6O3oVMWSktQOp6b7In1Zl3/Jr59b6EGGoI1aFkw7cmDA6j6gD" crossorigin="anonymous" />
        <style>
            @media (min-width: 992px) {
                .container {
                    max-width: 960px;
                }
            }
            h1 {
                font-size: calc(1.75rem + 1.75vw);
            }
        </style>
        <title>TRABAJANDO CON SVG</title>
    </head>
    <body>
        <header class="container">
            <div class="row py-4">
                <div class="col-sm-11 col-md-10 col-lg-9 col-xl-8 col-xxl-7 mx-auto">
                    <h1 class="mb-3 mt-5 text-center">TRABAJANDO CON SVG</h1>

                    <h2 class="mb-5 text-center text-uppercase fs-5">Emilia Vergara & Yannling Kuo</h2>

                    <p class="lead">
                        SVG es un formato gráfico vectorial escalable para definir gráficos basados en vectores. Este logra que se reproduzcan gráficos nítidos y de alta calidad por su flexibilidad y escalabilidad. También, es reconocido por ser un archivo liviano y que presenta alta compatibilidad en muchos navegadores.
                    </p>
                </div>
            </div>
        </header>

        <main class="container">
            <section>
                <div class="row">
                    <div class="col-sm-11 col-md-10 col-lg-9 col-xl-8 col-xxl-7 mx-auto">
                        <h2 class="text-center mt-5">GRÁFICA NO FIGURATIVA</h2>
                        <h3 class="text-center my-3">svg como src de un elemento img</h3>
                        <p>
                            El siguiente gráfico no figurativo representa a la familia de "felidaes" dividida en sus distintas sub-especies y géneros.
                        </p>
                    </div>
                    <figure class="shadow-sm col-md-11 col-lg-10 col-xl-9 col-xxl-8 mx-auto">
                        <img loading="lazy" src="img/gatos.svg" class="w-100" alt="describe lo que se ve en la imagen" />
                        <figcaption class="p-3 text-center text-muted small">Gráfica no figurativa generada con <a href="https://app.rawgraphs.io/" class="link-dark">RAWGraphs</a></figcaption>
                    </figure>
                    <div class="col-sm-11 col-md-10 col-lg-9 col-xl-8 col-xxl-7 mx-auto">
                        <h3 class="text-center mt-5 mb-3">svg como data de un elemento object</h3>
                        <p>
                            Además, está graficado el riesgo de extinción que sufre cada especie. Mientras más grande es el círculo, mayor es el nivel de riesgo de desaparecer.
                        </p>
                    </div>
                    <figure class="shadow-sm col-md-11 col-lg-10 col-xl-9 col-xxl-8 mx-auto">
                        <object type="image/svg+xml" data="img/gatos.svg">Acá se vería una gráfica</object>
                        <figcaption class="p-3 text-center text-muted small">Gráfica no figurativa generada con <a href="https://app.rawgraphs.io/" class="link-dark">RAWGraphs</a></figcaption>
                    </figure>
                    <div class="col-sm-11 col-md-10 col-lg-9 col-xl-8 col-xxl-7 mx-auto">
                        <h3 class="text-center mt-5 mb-3">svg como svg</h3>
                        <p>Cada color en el gráfico representa el género de cada especie. Por ejemplo, el tigre, el león, el leopardo, el leopardo de las nieves, y el jaguar pertenecen al género Panthera.</p>
                    </div>
                    <figure class="shadow-sm col-md-11 col-lg-10 col-xl-9 col-xxl-8 mx-auto">
                        <svg xmlns="http://www.w3.org/2000/svg" viewbox="0 0 805 600">
                            <rect width="805" height="600" x="0" y="0" fill="#FFFFFF" id="backgorund" />
                            <g transform="translate(402.5,300)" id="viz">
                                <g id="links">
                                    <path d="M0,0C5.8170722959499274e-15,95,7.795041677298463,-94.67965634310879,15.590083354596926,-189.35931268621758" fill="none" stroke="#ccc" />
                                    <path d="M0,0C5.8170722959499274e-15,95,24.745115386887026,-91.72065887513918,49.49023077377405,-183.44131775027836" fill="none" stroke="#ccc" />
                                    <path d="M0,0C5.8170722959499274e-15,95,40.63040281192939,-85.87298974264469,81.26080562385879,-171.74597948528938" fill="none" stroke="#ccc" />
                                    <path d="M0,0C5.8170722959499274e-15,95,55.2257026760438,-77.29891179012294,110.4514053520876,-154.5978235802459" fill="none" stroke="#ccc" />
                                    <path d="M0,0C5.8170722959499274e-15,95,68.06762416915458,-66.27064614115908,136.13524833830917,-132.54129228231815" fill="none" stroke="#ccc" />
                                    <path d="M0,0C5.8170722959499274e-15,95,78.74844504786668,-53.1383327038318,157.49689009573336,-106.2766654076636" fill="none" stroke="#ccc" />
                                    <path d="M0,0C5.8170722959499274e-15,95,86.80361475390202,-38.60223394644617,173.60722950780405,-77.20446789289234" fill="none" stroke="#ccc" />
                                    <path d="M0,0C5.8170722959499274e-15,95,92.12728117758073,-23.185427812032724,184.25456235516145,-46.37085562406545" fill="none" stroke="#ccc" />
                                    <path d="M0,0C5.8170722959499274e-15,95,94.73541983091624,-7.085212026470415,189.47083966183249,-14.17042405294083" fill="none" stroke="#ccc" />
                                    <path d="M0,0C5.8170722959499274e-15,95,94.55115367106623,9.223846240610085,189.10230734213246,18.44769248122017" fill="none" stroke="#ccc" />
                                    <path d="M0,0C5.8170722959499274e-15,95,91.57991409541714,25.26102401479437,183.15982819083428,50.52204802958874" fill="none" stroke="#ccc" />
                                    <path d="M0,0C5.8170722959499274e-15,95,85.90928084665632,40.55361222394783,171.81856169331263,81.10722444789566" fill="none" stroke="#ccc" />
                                    <path d="M0,0C5.8170722959499274e-15,95,77.70640052745792,54.650849188885324,155.41280105491583,109.30169837777065" fill="none" stroke="#ccc" />
                                    <path d="M0,0C5.8170722959499274e-15,95,67.21305981619628,67.13720719648994,134.42611963239256,134.27441439297988" fill="none" stroke="#ccc" />
                                    <path d="M0,0C5.8170722959499274e-15,95,54.73855860472626,77.64464052255602,109.47711720945252,155.28928104511203" fill="none" stroke="#ccc" />
                                    <path d="M0,0C5.8170722959499274e-15,95,40.65059312838583,85.86343388375771,81.30118625677166,171.72686776751542" fill="none" stroke="#ccc" />
                                    <path d="M0,0C5.8170722959499274e-15,95,25.36441781550117,91.55133155165295,50.72883563100234,183.1026631033059" fill="none" stroke="#ccc" />
                                    <path d="M0,0C5.8170722959499274e-15,95,9.330605319838801,94.54067804054188,18.661210639677602,189.08135608108375" fill="none" stroke="#ccc" />
                                    <path d="M0,0C5.8170722959499274e-15,95,-6.627443475180325,94.76854432238204,-13.25488695036065,189.53708864476408" fill="none" stroke="#ccc" />
                                    <path d="M0,0C5.8170722959499274e-15,95,-22.05651503874968,92.40405913348943,-44.11303007749936,184.80811826697885" fill="none" stroke="#ccc" />
                                    <path d="M0,0C5.8170722959499274e-15,95,-36.89012902986813,87.54495062629073,-73.78025805973625,175.08990125258146" fill="none" stroke="#ccc" />
                                    <path d="M0,0C5.8170722959499274e-15,95,-50.727823827000975,80.32239967640878,-101.45564765400195,160.64479935281756" fill="none" stroke="#ccc" />
                                    <path d="M0,0C5.8170722959499274e-15,95,-63.19602454137978,70.93139278320513,-126.39204908275956,141.86278556641025" fill="none" stroke="#ccc" />
                                    <path d="M0,0C5.8170722959499274e-15,95,-73.95812838162219,59.62545803838734,-147.91625676324438,119.25091607677469" fill="none" stroke="#ccc" />
                                    <path d="M0,0C5.8170722959499274e-15,95,-82.51767778620992,47.07263379896261,-165.03535557241983,94.14526759792523" fill="none" stroke="#ccc" />
                                    <path d="M0,0C5.8170722959499274e-15,95,-88.81945263262024,33.706154245801,-177.63890526524048,67.412308491602" fill="none" stroke="#ccc" />
                                    <path d="M0,0C5.8170722959499274e-15,95,-92.97209057392583,19.524097272696963,-185.94418114785165,39.048194545393926" fill="none" stroke="#ccc" />
                                    <path d="M0,0C5.8170722959499274e-15,95,-94.8751115104562,4.869621738749518,-189.7502230209124,9.739243477499036" fill="none" stroke="#ccc" />
                                    <path d="M0,0C5.8170722959499274e-15,95,-94.48246863146598,-9.902682530710882,-188.96493726293195,-19.805365061421764" fill="none" stroke="#ccc" />
                                    <path d="M0,0C5.8170722959499274e-15,95,-91.80366259561444,-24.435374644776417,-183.60732519122888,-48.87074928955283" fill="none" stroke="#ccc" />
                                    <path d="M0,0C5.8170722959499274e-15,95,-86.90351164645767,-38.37681153397188,-173.80702329291535,-76.75362306794376" fill="none" stroke="#ccc" />
                                    <path d="M0,0C5.8170722959499274e-15,95,-79.90058322539828,-51.38965654916565,-159.80116645079656,-102.7793130983313" fill="none" stroke="#ccc" />
                                    <path d="M0,0C5.8170722959499274e-15,95,-70.96432503186915,-63.15904189244189,-141.9286500637383,-126.31808378488378" fill="none" stroke="#ccc" />
                                    <path d="M0,0C5.8170722959499274e-15,95,-60.310964949605584,-73.40018737610583,-120.62192989921117,-146.80037475221167" fill="none" stroke="#ccc" />
                                    <path d="M0,0C5.8170722959499274e-15,95,-48.19827904722229,-81.86529116106588,-96.39655809444459,-163.73058232213177" fill="none" stroke="#ccc" />
                                    <path d="M0,0C5.8170722959499274e-15,95,-34.91935425017515,-88.34952574151588,-69.8387085003503,-176.69905148303175" fill="none" stroke="#ccc" />
                                    <path d="M0,0C5.8170722959499274e-15,95,-21.325639607651738,-92.57546702730997,-42.651279215303475,-185.15093405461994" fill="none" stroke="#ccc" />
                                    <path d="M0,0C5.8170722959499274e-15,95,-7.795041677298496,-94.67965634310879,-15.590083354596992,-189.35931268621758" fill="none" stroke="#ccc" />
                                </g>
                                <g>
                                    <circle transform="&#10;&#9;        rotate(90)&#10;&#9;        translate(0,0)&#10;&#9;      " fill="#ccc" r="5" />
                                    <circle transform="&#10;&#9;        rotate(-85.29341392308228)&#10;&#9;        translate(190,0)&#10;&#9;      " fill="#cccccc" r="10" />
                                    <circle transform="&#10;&#9;        rotate(-74.9017571823452)&#10;&#9;        translate(190,0)&#10;&#9;      " fill="#ff7f0e" r="9.12870929175277" />
                                    <circle transform="&#10;&#9;        rotate(-64.67904738598371)&#10;&#9;        translate(190,0)&#10;&#9;      " fill="#d62728" r="9.12870929175277" />
                                    <circle transform="&#10;&#9;        rotate(-54.456337589622215)&#10;&#9;        translate(190,0)&#10;&#9;      " fill="#8c564b" r="9.12870929175277" />
                                    <circle transform="&#10;&#9;        rotate(-44.23362779326074)&#10;&#9;        translate(190,0)&#10;&#9;      " fill="#cccccc" r="9.12870929175277" />
                                    <circle transform="&#10;&#9;        rotate(-34.010917996899224)&#10;&#9;        translate(190,0)&#10;&#9;      " fill="#bcbd22" r="9.12870929175277" />
                                    <circle transform="&#10;&#9;        rotate(-23.975082127902)&#10;&#9;        translate(190,0)&#10;&#9;      " fill="#1f77b4" r="8.16496580927726" />
                                    <circle transform="&#10;&#9;        rotate(-14.126120186269077)&#10;&#9;        translate(190,0)&#10;&#9;      " fill="#2ca02c" r="8.16496580927726" />
                                    <circle transform="&#10;&#9;        rotate(-4.2771582446361265)&#10;&#9;        translate(190,0)&#10;&#9;      " fill="#d62728" r="8.16496580927726" />
                                    <circle transform="&#10;&#9;        rotate(5.57180369699681)&#10;&#9;        translate(190,0)&#10;&#9;      " fill="#d62728" r="8.16496580927726" />
                                    <circle transform="&#10;&#9;        rotate(15.420765638629774)&#10;&#9;        translate(190,0)&#10;&#9;      " fill="#d62728" r="8.16496580927726" />
                                    <circle transform="&#10;&#9;        rotate(25.26972758026271)&#10;&#9;        translate(190,0)&#10;&#9;      " fill="#cccccc" r="8.16496580927726" />
                                    <circle transform="&#10;&#9;        rotate(35.11868952189565)&#10;&#9;        translate(190,0)&#10;&#9;      " fill="#cccccc" r="8.16496580927726" />
                                    <circle transform="&#10;&#9;        rotate(44.9676514635286)&#10;&#9;        translate(190,0)&#10;&#9;      " fill="#e377c2" r="8.16496580927726" />
                                    <circle transform="&#10;&#9;        rotate(54.81661340516152)&#10;&#9;        translate(190,0)&#10;&#9;      " fill="#e377c2" r="8.16496580927726" />
                                    <circle transform="&#10;&#9;        rotate(64.66557534679444)&#10;&#9;        translate(190,0)&#10;&#9;      " fill="#bcbd22" r="8.16496580927726" />
                                    <circle transform="&#10;&#9;        rotate(74.51453728842742)&#10;&#9;        translate(190,0)&#10;&#9;      " fill="#bcbd22" r="8.16496580927726" />
                                    <circle transform="&#10;&#9;        rotate(84.36349923006031)&#10;&#9;        translate(190,0)&#10;&#9;      " fill="#bcbd22" r="8.16496580927726" />
                                    <circle transform="&#10;&#9;        rotate(94.00034973475036)&#10;&#9;        translate(190,0)&#10;&#9;      " fill="#ff7f0e" r="7.0710678118654755" />
                                    <circle transform="&#10;&#9;        rotate(103.42508880249747)&#10;&#9;        translate(190,0)&#10;&#9;      " fill="#d62728" r="7.0710678118654755" />
                                    <circle transform="&#10;&#9;        rotate(112.84982787024455)&#10;&#9;        translate(190,0)&#10;&#9;      " fill="#d62728" r="7.0710678118654755" />
                                    <circle transform="&#10;&#9;        rotate(122.27456693799172)&#10;&#9;        translate(190,0)&#10;&#9;      " fill="#cccccc" r="7.0710678118654755" />
                                    <circle transform="&#10;&#9;        rotate(131.6993060057388)&#10;&#9;        translate(190,0)&#10;&#9;      " fill="#bcbd22" r="7.0710678118654755" />
                                    <circle transform="&#10;&#9;        rotate(141.12404507348595)&#10;&#9;        translate(190,0)&#10;&#9;      " fill="#17becf" r="7.0710678118654755" />
                                    <circle transform="&#10;&#9;        rotate(150.29718078993807)&#10;&#9;        translate(190,0)&#10;&#9;      " fill="#2ca02c" r="5.773502691896258" />
                                    <circle transform="&#10;&#9;        rotate(159.21871315509517)&#10;&#9;        translate(190,0)&#10;&#9;      " fill="#2ca02c" r="5.773502691896258" />
                                    <circle transform="&#10;&#9;        rotate(168.14024552025234)&#10;&#9;        translate(190,0)&#10;&#9;      " fill="#d62728" r="5.773502691896258" />
                                    <circle transform="&#10;&#9;        rotate(177.06177788540947)&#10;&#9;        translate(190,0)&#10;&#9;      " fill="#d62728" r="5.773502691896258" />
                                    <circle transform="&#10;&#9;        rotate(185.9833102505666)&#10;&#9;        translate(190,0)&#10;&#9;      " fill="#9467bd" r="5.773502691896258" />
                                    <circle transform="&#10;&#9;        rotate(194.90484261572368)&#10;&#9;        translate(190,0)&#10;&#9;      " fill="#8c564b" r="5.773502691896258" />
                                    <circle transform="&#10;&#9;        rotate(203.82637498088087)&#10;&#9;        translate(190,0)&#10;&#9;      " fill="#8c564b" r="5.773502691896258" />
                                    <circle transform="&#10;&#9;        rotate(212.74790734603795)&#10;&#9;        translate(190,0)&#10;&#9;      " fill="#8c564b" r="5.773502691896258" />
                                    <circle transform="&#10;&#9;        rotate(221.66943971119514)&#10;&#9;        translate(190,0)&#10;&#9;      " fill="#7f7f7f" r="5.773502691896258" />
                                    <circle transform="&#10;&#9;        rotate(230.59097207635222)&#10;&#9;        translate(190,0)&#10;&#9;      " fill="#cccccc" r="5.773502691896258" />
                                    <circle transform="&#10;&#9;        rotate(239.51250444150935)&#10;&#9;        translate(190,0)&#10;&#9;      " fill="#cccccc" r="5.773502691896258" />
                                    <circle transform="&#10;&#9;        rotate(248.43403680666648)&#10;&#9;        translate(190,0)&#10;&#9;      " fill="#cccccc" r="5.773502691896258" />
                                    <circle transform="&#10;&#9;        rotate(257.02767330052416)&#10;&#9;        translate(190,0)&#10;&#9;      " fill="#2ca02c" r="4.08248290463863" />
                                    <circle transform="&#10;&#9;        rotate(265.29341392308226)&#10;&#9;        translate(190,0)&#10;&#9;      " fill="#2ca02c" r="4.08248290463863" />
                                </g>
                                <g id="labels">
                                    <g transform="&#10;&#9;        rotate(90)&#10;&#9;        translate(0,0)&#10;&#9;        rotate(180)&#10;&#9;      ">
                                        <text x="0" y="0" text-anchor="middle" dominant-baseline="text-before-edge" transform="translate(0,0)">
                                            <tspan x="6" y="0" dy="0" text-anchor="start" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal;" />
                                        </text>
                                    </g>
                                    <g transform="&#10;&#9;        rotate(-85.29341392308228)&#10;&#9;        translate(190,0)&#10;&#9;        rotate(0)&#10;&#9;      ">
                                        <text x="0" y="0" text-anchor="middle" dominant-baseline="text-before-edge" transform="translate(0,-5.5)">
                                            <tspan x="15" y="0" dy="0" text-anchor="start" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">Iriomote cat</tspan>
                                        </text>
                                    </g>
                                    <g transform="&#10;&#9;        rotate(-74.9017571823452)&#10;&#9;        translate(190,0)&#10;&#9;        rotate(0)&#10;&#9;      ">
                                        <text x="0" y="0" text-anchor="middle" dominant-baseline="text-before-edge" transform="translate(0,-5.55224609375)">
                                            <tspan x="14.12870929175277" y="0" dy="0" text-anchor="start" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">bay cat</tspan>
                                        </text>
                                    </g>
                                    <g transform="&#10;&#9;        rotate(-64.67904738598371)&#10;&#9;        translate(190,0)&#10;&#9;        rotate(0)&#10;&#9;      ">
                                        <text x="0" y="0" text-anchor="middle" dominant-baseline="text-before-edge" transform="translate(0,-5.5)">
                                            <tspan x="14.12870929175277" y="0" dy="0" text-anchor="start" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">Andean mountain cat</tspan>
                                        </text>
                                    </g>
                                    <g transform="&#10;&#9;        rotate(-54.456337589622215)&#10;&#9;        translate(190,0)&#10;&#9;        rotate(0)&#10;&#9;      ">
                                        <text x="0" y="0" text-anchor="middle" dominant-baseline="text-before-edge" transform="translate(0,-5.55224609375)">
                                            <tspan x="14.12870929175277" y="0" dy="0" text-anchor="start" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">Spanish lynx</tspan>
                                        </text>
                                    </g>
                                    <g transform="&#10;&#9;        rotate(-44.23362779326074)&#10;&#9;        translate(190,0)&#10;&#9;        rotate(0)&#10;&#9;      ">
                                        <text x="0" y="0" text-anchor="middle" dominant-baseline="text-before-edge" transform="translate(0,-5.5)">
                                            <tspan x="14.12870929175277" y="0" dy="0" text-anchor="start" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">flat-headed cat</tspan>
                                        </text>
                                    </g>
                                    <g transform="&#10;&#9;        rotate(-34.010917996899224)&#10;&#9;        translate(190,0)&#10;&#9;        rotate(0)&#10;&#9;      ">
                                        <text x="0" y="0" text-anchor="middle" dominant-baseline="text-before-edge" transform="translate(0,-5.55224609375)">
                                            <tspan x="14.12870929175277" y="0" dy="0" text-anchor="start" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">tiger</tspan>
                                        </text>
                                    </g>
                                    <g transform="&#10;&#9;        rotate(-23.975082127902)&#10;&#9;        translate(190,0)&#10;&#9;        rotate(0)&#10;&#9;      ">
                                        <text x="0" y="0" text-anchor="middle" dominant-baseline="text-before-edge" transform="translate(0,-5.5)">
                                            <tspan x="13.16496580927726" y="0" dy="0" text-anchor="start" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">cheetah</tspan>
                                        </text>
                                    </g>
                                    <g transform="&#10;&#9;        rotate(-14.126120186269077)&#10;&#9;        translate(190,0)&#10;&#9;        rotate(0)&#10;&#9;      ">
                                        <text x="0" y="0" text-anchor="middle" dominant-baseline="text-before-edge" transform="translate(0,-5.5)">
                                            <tspan x="13.16496580927726" y="0" dy="0" text-anchor="start" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">black-footed cat</tspan>
                                        </text>
                                    </g>
                                    <g transform="&#10;&#9;        rotate(-4.2771582446361265)&#10;&#9;        translate(190,0)&#10;&#9;        rotate(0)&#10;&#9;      ">
                                        <text x="0" y="0" text-anchor="middle" dominant-baseline="text-before-edge" transform="translate(0,-5.5)">
                                            <tspan x="13.16496580927726" y="0" dy="0" text-anchor="start" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">Kodkod</tspan>
                                        </text>
                                    </g>
                                    <g transform="&#10;&#9;        rotate(5.57180369699681)&#10;&#9;        translate(190,0)&#10;&#9;        rotate(0)&#10;&#9;      ">
                                        <text x="0" y="0" text-anchor="middle" dominant-baseline="text-before-edge" transform="translate(0,-5.5)">
                                            <tspan x="13.16496580927726" y="0" dy="0" text-anchor="start" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">Southern oncilla</tspan>
                                        </text>
                                    </g>
                                    <g transform="&#10;&#9;        rotate(15.420765638629774)&#10;&#9;        translate(190,0)&#10;&#9;        rotate(0)&#10;&#9;      ">
                                        <text x="0" y="0" text-anchor="middle" dominant-baseline="text-before-edge" transform="translate(0,-5.5)">
                                            <tspan x="13.16496580927726" y="0" dy="0" text-anchor="start" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">little spotted cat</tspan>
                                        </text>
                                    </g>
                                    <g transform="&#10;&#9;        rotate(25.26972758026271)&#10;&#9;        translate(190,0)&#10;&#9;        rotate(0)&#10;&#9;      ">
                                        <text x="0" y="0" text-anchor="middle" dominant-baseline="text-before-edge" transform="translate(0,-5.55224609375)">
                                            <tspan x="13.16496580927726" y="0" dy="0" text-anchor="start" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">fishing cat</tspan>
                                        </text>
                                    </g>
                                    <g transform="&#10;&#9;        rotate(35.11868952189565)&#10;&#9;        translate(190,0)&#10;&#9;        rotate(0)&#10;&#9;      ">
                                        <text x="0" y="0" text-anchor="middle" dominant-baseline="text-before-edge" transform="translate(0,-5.55224609375)">
                                            <tspan x="13.16496580927726" y="0" dy="0" text-anchor="start" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">African golden cat</tspan>
                                        </text>
                                    </g>
                                    <g transform="&#10;&#9;        rotate(44.9676514635286)&#10;&#9;        translate(190,0)&#10;&#9;        rotate(0)&#10;&#9;      ">
                                        <text x="0" y="0" text-anchor="middle" dominant-baseline="text-before-edge" transform="translate(0,-5.5)">
                                            <tspan x="13.16496580927726" y="0" dy="0" text-anchor="start" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">Sunda clouded leopard</tspan>
                                        </text>
                                    </g>
                                    <g transform="&#10;&#9;        rotate(54.81661340516152)&#10;&#9;        translate(190,0)&#10;&#9;        rotate(0)&#10;&#9;      ">
                                        <text x="0" y="0" text-anchor="middle" dominant-baseline="text-before-edge" transform="translate(0,-5.5)">
                                            <tspan x="13.16496580927726" y="0" dy="0" text-anchor="start" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">Clouded leopard</tspan>
                                        </text>
                                    </g>
                                    <g transform="&#10;&#9;        rotate(64.66557534679444)&#10;&#9;        translate(190,0)&#10;&#9;        rotate(0)&#10;&#9;      ">
                                        <text x="0" y="0" text-anchor="middle" dominant-baseline="text-before-edge" transform="translate(0,-5.5)">
                                            <tspan x="13.16496580927726" y="0" dy="0" text-anchor="start" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">lion</tspan>
                                        </text>
                                    </g>
                                    <g transform="&#10;&#9;        rotate(74.51453728842742)&#10;&#9;        translate(190,0)&#10;&#9;        rotate(0)&#10;&#9;      ">
                                        <text x="0" y="0" text-anchor="middle" dominant-baseline="text-before-edge" transform="translate(0,-5.5)">
                                            <tspan x="13.16496580927726" y="0" dy="0" text-anchor="start" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">leopard</tspan>
                                        </text>
                                    </g>
                                    <g transform="&#10;&#9;        rotate(84.36349923006031)&#10;&#9;        translate(190,0)&#10;&#9;        rotate(0)&#10;&#9;      ">
                                        <text x="0" y="0" text-anchor="middle" dominant-baseline="text-before-edge" transform="translate(0,-5.5)">
                                            <tspan x="13.16496580927726" y="0" dy="0" text-anchor="start" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">snow leopard</tspan>
                                        </text>
                                    </g>
                                    <g transform="&#10;&#9;        rotate(94.00034973475036)&#10;&#9;        translate(190,0)&#10;&#9;        rotate(180)&#10;&#9;      ">
                                        <text x="0" y="0" text-anchor="middle" dominant-baseline="text-before-edge" transform="translate(0,-5.55224609375)">
                                            <tspan x="-12.071067811865476" y="0" dy="0" text-anchor="end" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">Asiatic golden cat</tspan>
                                        </text>
                                    </g>
                                    <g transform="&#10;&#9;        rotate(103.42508880249747)&#10;&#9;        translate(190,0)&#10;&#9;        rotate(180)&#10;&#9;      ">
                                        <text x="0" y="0" text-anchor="middle" dominant-baseline="text-before-edge" transform="translate(0,-5.5)">
                                            <tspan x="-12.071067811865476" y="0" dy="0" text-anchor="end" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">Colocolo</tspan>
                                        </text>
                                    </g>
                                    <g transform="&#10;&#9;        rotate(112.84982787024455)&#10;&#9;        translate(190,0)&#10;&#9;        rotate(180)&#10;&#9;      ">
                                        <text x="0" y="0" text-anchor="middle" dominant-baseline="text-before-edge" transform="translate(0,-5.55224609375)">
                                            <tspan x="-12.071067811865476" y="0" dy="0" text-anchor="end" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">margay</tspan>
                                        </text>
                                    </g>
                                    <g transform="&#10;&#9;        rotate(122.27456693799172)&#10;&#9;        translate(190,0)&#10;&#9;        rotate(180)&#10;&#9;      ">
                                        <text x="0" y="0" text-anchor="middle" dominant-baseline="text-before-edge" transform="translate(0,-5.55224609375)">
                                            <tspan x="-12.071067811865476" y="0" dy="0" text-anchor="end" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">rusty-spotted cat</tspan>
                                        </text>
                                    </g>
                                    <g transform="&#10;&#9;        rotate(131.6993060057388)&#10;&#9;        translate(190,0)&#10;&#9;        rotate(180)&#10;&#9;      ">
                                        <text x="0" y="0" text-anchor="middle" dominant-baseline="text-before-edge" transform="translate(0,-5.55224609375)">
                                            <tspan x="-12.071067811865476" y="0" dy="0" text-anchor="end" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">jaguar</tspan>
                                        </text>
                                    </g>
                                    <g transform="&#10;&#9;        rotate(141.12404507348595)&#10;&#9;        translate(190,0)&#10;&#9;        rotate(180)&#10;&#9;      ">
                                        <text x="0" y="0" text-anchor="middle" dominant-baseline="text-before-edge" transform="translate(0,-5.5)">
                                            <tspan x="-12.071067811865476" y="0" dy="0" text-anchor="end" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">marbled cat</tspan>
                                        </text>
                                    </g>
                                    <g transform="&#10;&#9;        rotate(150.29718078993807)&#10;&#9;        translate(190,0)&#10;&#9;        rotate(180)&#10;&#9;      ">
                                        <text x="0" y="0" text-anchor="middle" dominant-baseline="text-before-edge" transform="translate(0,-5.55224609375)">
                                            <tspan x="-10.773502691896258" y="0" dy="0" text-anchor="end" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">jungle cat</tspan>
                                        </text>
                                    </g>
                                    <g transform="&#10;&#9;        rotate(159.21871315509517)&#10;&#9;        translate(190,0)&#10;&#9;        rotate(180)&#10;&#9;      ">
                                        <text x="0" y="0" text-anchor="middle" dominant-baseline="text-before-edge" transform="translate(0,-5.5)">
                                            <tspan x="-10.773502691896258" y="0" dy="0" text-anchor="end" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">sand cat</tspan>
                                        </text>
                                    </g>
                                    <g transform="&#10;&#9;        rotate(168.14024552025234)&#10;&#9;        translate(190,0)&#10;&#9;        rotate(180)&#10;&#9;      ">
                                        <text x="0" y="0" text-anchor="middle" dominant-baseline="text-before-edge" transform="translate(0,-5.55224609375)">
                                            <tspan x="-10.773502691896258" y="0" dy="0" text-anchor="end" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">Geoffroy's cat</tspan>
                                        </text>
                                    </g>
                                    <g transform="&#10;&#9;        rotate(177.06177788540947)&#10;&#9;        translate(190,0)&#10;&#9;        rotate(180)&#10;&#9;      ">
                                        <text x="0" y="0" text-anchor="middle" dominant-baseline="text-before-edge" transform="translate(0,-5.5)">
                                            <tspan x="-10.773502691896258" y="0" dy="0" text-anchor="end" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">ocelot</tspan>
                                        </text>
                                    </g>
                                    <g transform="&#10;&#9;        rotate(185.9833102505666)&#10;&#9;        translate(190,0)&#10;&#9;        rotate(180)&#10;&#9;      ">
                                        <text x="0" y="0" text-anchor="middle" dominant-baseline="text-before-edge" transform="translate(0,-5.5)">
                                            <tspan x="-10.773502691896258" y="0" dy="0" text-anchor="end" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">serval</tspan>
                                        </text>
                                    </g>
                                    <g transform="&#10;&#9;        rotate(194.90484261572368)&#10;&#9;        translate(190,0)&#10;&#9;        rotate(180)&#10;&#9;      ">
                                        <text x="0" y="0" text-anchor="middle" dominant-baseline="text-before-edge" transform="translate(0,-5.55224609375)">
                                            <tspan x="-10.773502691896258" y="0" dy="0" text-anchor="end" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">Canada lynx</tspan>
                                        </text>
                                    </g>
                                    <g transform="&#10;&#9;        rotate(203.82637498088087)&#10;&#9;        translate(190,0)&#10;&#9;        rotate(180)&#10;&#9;      ">
                                        <text x="0" y="0" text-anchor="middle" dominant-baseline="text-before-edge" transform="translate(0,-5.55224609375)">
                                            <tspan x="-10.773502691896258" y="0" dy="0" text-anchor="end" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">Eurasian lynx</tspan>
                                        </text>
                                    </g>
                                    <g transform="&#10;&#9;        rotate(212.74790734603795)&#10;&#9;        translate(190,0)&#10;&#9;        rotate(180)&#10;&#9;      ">
                                        <text x="0" y="0" text-anchor="middle" dominant-baseline="text-before-edge" transform="translate(0,-5.5)">
                                            <tspan x="-10.773502691896258" y="0" dy="0" text-anchor="end" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">bobcat</tspan>
                                        </text>
                                    </g>
                                    <g transform="&#10;&#9;        rotate(221.66943971119514)&#10;&#9;        translate(190,0)&#10;&#9;        rotate(180)&#10;&#9;      ">
                                        <text x="0" y="0" text-anchor="middle" dominant-baseline="text-before-edge" transform="translate(0,-5.5)">
                                            <tspan x="-10.773502691896258" y="0" dy="0" text-anchor="end" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">Pallas's cat</tspan>
                                        </text>
                                    </g>
                                    <g transform="&#10;&#9;        rotate(230.59097207635222)&#10;&#9;        translate(190,0)&#10;&#9;        rotate(180)&#10;&#9;      ">
                                        <text x="0" y="0" text-anchor="middle" dominant-baseline="text-before-edge" transform="translate(0,-5.5)">
                                            <tspan x="-10.773502691896258" y="0" dy="0" text-anchor="end" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">leopard cat</tspan>
                                        </text>
                                    </g>
                                    <g transform="&#10;&#9;        rotate(239.51250444150935)&#10;&#9;        translate(190,0)&#10;&#9;        rotate(180)&#10;&#9;      ">
                                        <text x="0" y="0" text-anchor="middle" dominant-baseline="text-before-edge" transform="translate(0,-5.5)">
                                            <tspan x="-10.773502691896258" y="0" dy="0" text-anchor="end" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">puma</tspan>
                                        </text>
                                    </g>
                                    <g transform="&#10;&#9;        rotate(248.43403680666648)&#10;&#9;        translate(190,0)&#10;&#9;        rotate(180)&#10;&#9;      ">
                                        <text x="0" y="0" text-anchor="middle" dominant-baseline="text-before-edge" transform="translate(0,-5.55224609375)">
                                            <tspan x="-10.773502691896258" y="0" dy="0" text-anchor="end" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">jaguarundi</tspan>
                                        </text>
                                    </g>
                                    <g transform="&#10;&#9;        rotate(257.02767330052416)&#10;&#9;        translate(190,0)&#10;&#9;        rotate(180)&#10;&#9;      ">
                                        <text x="0" y="0" text-anchor="middle" dominant-baseline="text-before-edge" transform="translate(0,-5.5)">
                                            <tspan x="-9.082482904638631" y="0" dy="0" text-anchor="end" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">domestic cat</tspan>
                                        </text>
                                    </g>
                                    <g transform="&#10;&#9;        rotate(265.29341392308226)&#10;&#9;        translate(190,0)&#10;&#9;        rotate(180)&#10;&#9;      ">
                                        <text x="0" y="0" text-anchor="middle" dominant-baseline="text-before-edge" transform="translate(0,-5.5)">
                                            <tspan x="-9.082482904638631" y="0" dy="0" text-anchor="end" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">wild cat</tspan>
                                        </text>
                                    </g>
                                </g>
                            </g>
                        </svg>

                        <figcaption class="p-3 text-center text-muted small">Gráfica no figurativa generada con <a href="https://app.rawgraphs.io/" class="link-dark">RAWGraphs</a></figcaption>
                    </figure>
                </div>
            </section>

            <section>
                <div class="row">
                    <div class="col-sm-11 col-md-10 col-lg-9 col-xl-8 col-xxl-7 mx-auto">
                        <h2 class="text-center mt-5">GRÁFICA FIGURATIVA</h2>
                        <h3 class="text-center my-3">svg como data de un elemento object</h3>
                        <p> Esta selección de íconos nos ayudan a visualizar mejor algunas de las especies mencionadas en la gráfica anterior.</p>
                    </div>
                    <div class="col-md-11 col-lg-10 col-xl-9 col-xxl-8 mx-auto">
                        <div class="row shadow-sm mb-4">
                            <figure class="col-md-6 col-lg-4">
                                <object type="image/svg+xml" data="img/fig1.svg">Acá se vería un icon</object>
                            </figure>
                            <figure class="col-md-6 col-lg-4">
                                <object type="image/svg+xml" data="img/fig2.svg">Acá se vería un icon</object>
                            </figure>
                            <figure class="col-md-6 col-lg-4">
                                <object type="image/svg+xml" data="img/fig3.svg">Acá se vería un icon</object>
                            </figure>
                            <figure class="col-md-6 col-lg-4">
                                <object type="image/svg+xml" data="img/fig4.svg">Acá se vería un icon</object>
                            </figure>
                            <figure class="col-md-6 col-lg-4">
                                <object type="image/svg+xml" data="img/fig5.svg">Acá se vería un icon</object>
                            </figure>
                            <figure class="col-md-6 col-lg-4">
                                <object type="image/svg+xml" data="img/fig6.svg">Acá se vería un icon</object>
                            </figure>
                        </div>
                    </div>
                    <div class="col-sm-11 col-md-10 col-lg-9 col-xl-8 col-xxl-7 mx-auto mb-5">
                        <p>
                            Los SVG son una gran ayuda visual que presenta muchas ventajas tales como, su formato liviano que no daña la calidad y resolución del recurso. Es necesario destacar que este tipo de archivo permite seleccionar texto incrustado en la imagen, facilitando interacciones como copiar y pegar, o buscar en un navegador.
                        </p>
                    </div>
                </div>
            </section>
        </main>

        <footer class="bg-light">
            <div class="container">
                <div class="row py-3">
                    <div class="col-12">
                        <p class="d-flex justify-content-between small p-1 m-0">
                            <a href="https://github.com/profesorfaco/dno075-2023-1/" class="link-dark">Infografía Digital</a>
                            <a href="https://github.com/profesorfaco/dno075-2023-1/tree/main/clase-04" class="link-dark">Martes 28 de marzo, 2023</a>
                        </p>
                    </div>
                </div>
            </div>
        </footer>
    </body>
</html>
