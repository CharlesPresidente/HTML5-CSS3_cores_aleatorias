# HTML5/CSS3 - Animação em troca de Cores 

Troca a cor do background altomaticamente.


## Arquivos

### .html

	<!DOCTYPE html>
    <html lang="pt">

        <head>
            <meta charset="UTF-8">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <meta http-equiv="X-UA-Compatible" content="ie=edge">
            <link rel="stylesheet" href="style.css">
            <title>Cores Aleatórias</title>
        </head>

        <body>
            <div class="container">
                <p>Mussum Ipsum, cacilds vidis litro abertis. Interessantiss quisso pudia ce receita de bolis, mais bolis eu num gostis.
                    Atirei o pau no gatis, per gatis num morreus. Mé faiz elementum girarzis, nisi eros vermeio. Quem manda na minha
                    terra sou euzis! Sapien in monti palavris qui num significa nadis i pareci latim. Suco de cevadiss deixa as pessoas
                    mais interessantis. Quem num gosta di mé, boa gentis num é. Manduma pindureta quium dia nois paga. Cevadis im
                    ampola pa arma uma pindureta. A ordem dos tratores não altera o pão duris. Si num tem leite então bota uma pinga
                    aí cumpadi! Todo mundo vê os porris que eu tomo, mas ninguém vê os tombis que eu levo! Detraxit consequat et
                    quo num tendi nada. Praesent vel viverra nisi. Mauris aliquet nunc non turpis scelerisque, eget. Si u mundo tá
                    muito paradis? Toma um mé que o mundo vai girarzis! Aenean aliquam molestie leo, vitae iaculis nisl. Paisis,
                    filhis, espiritis santis. Admodum accumsan disputationi eu sit. Vide electram sadipscing et per. Suco de cevadiss,
                    é um leite divinis, qui tem lupuliz, matis, aguis e fermentis. Mais vale um bebadis conhecidiss, que um alcoolatra
                    anonimis.
                </p>
            </div>
        </body>

    </html>

### .css
Destaque para os elementos sinalizados com as setas:

	body {
        animation: anim 8s infinite; <--
    }

    .container {
        font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
        font-size: 100%;
        width: 40%;
        text-align: justify;
        margin: 150px auto;
    }

    @keyframes anim {
        0% {
            background-color: #d50000;
        }
        10% {
            background-color: #c51162;
        }
        20% {
            background-color: #aa00ff;
        }
        30% {
            background-color: #6200ea;
        }
        40% {
            background-color: #304ffe;
        }
        50% {
            background-color: #2962ff;
        }
        60% {
            background-color: #0091ea;
        }
        70% {
            background-color: #00b8d4;
        }
        80% {
            background-color: #00bfa5;
        }
        90% {
            background-color: #00c853;
        }
        100% {
            background-color: #64dd17;
        }
    }

