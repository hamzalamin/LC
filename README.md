/*First projet in Html*/

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />

    <title>CSS CV</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            background-color: #f5f5f5;
        }

        h1 {
            background-color: rgb(0, 0, 200);
        }

        h4 {
            color: rgb(200, 0, 0);
        }

        h2 {
            color: rgb(100, 100, 100)
        }

        .profile {
            width: 45%;
            height: 10000px;
            float: left;
            background-color: rgb(0, 180, 183);
            padding: 5px;
        }

        .top {
            width: 45%;
            height: 200px;
            float: left;
            padding: 5px;
        }

        #EP {
            color: blue;
            background-color: rgb(0, 180, 183);
        }

        #AP {
            color: blue;
            background-color: rgb(0, 180, 183);
        }

        #UP {
            color: blue;
        }
    </style>
</head>

<body>



    <h1>HAMZA LAMIN</h1>
    <header>
        <div class="top">

            <td>
                <img src="https://b.fssta.com/uploads/application/soccer/headshots/4062.vresize.350.350.medium.49.png"
                    width="290" height="180">
            </td>
        </div>
        <div class="top">

            <table>
                <td>
                    <img src="https://e7.pngegg.com/pngimages/193/250/png-clipart-blue-phone-inside-circle-icon-telephone-call-symbol-smartphone-ringing-phone-miscellaneous-blue-thumbnail.png"
                        width="19" height="18">
                    <h4 style="margin-bottom: 5px;">Telephone</h4>

                    0639621650 &nbsp;&nbsp;

                </td>
                <td>
                    <img src="https://e7.pngegg.com/pngimages/152/364/png-clipart-computer-icons-gmail-gratis-gmail-blue-angle-thumbnail.png"
                        width="19" height="18">
                    <h4 style="margin-bottom: 5px;">Gmail adresse</h4>

                    hamzalamin80@gmail.com &nbsp;&nbsp;

                </td>
                <td>
                    <img src="https://hemiole72.files.wordpress.com/2018/04/logo-adresse.png" width="19" height="18">
                    <h4 style="margin-bottom: 5px;">Adresse</h4>

                    AGADIR, tarrast &nbsp;&nbsp;

                </td>
            </table>
        </div>
    </header>

    <div class="profile">

        <h2 id="UP">

            <strong>Profile:</strong>
        </h2>
        <p id="op" style="font-size: 20px">
            Marketing axé sur les résultats et hautement <br>motivé. Solides<br> compétences analytiques combinées<br> à
            d'excellentes capacités de communication,<br> permettant une collaboration efficace<br>avec des équipes
            interfonctionnelles.<br> À la recherche d'un rôle stimulant. <br>pour apporter des connaissances
            stratégiques<br> et de la créativité à une équipe marketing <br>dynamique
        </p>

    </div>


    <div class="profile" style="background-color: white">
        <h2 id="EP">

            <strong>Objective:</strong>
        </h2>
        <p style="font-size: 15px">
            Je recherche un rôle stimulant dans une entreprise technologique dynamique où je peux pleinement utiliser
            mes compétences en développement et contribuer à la création d'applications logicielles de pointe.
        </p>
        <h2 id="EP">
            <strong>Edicational profile:</strong>
        </h2>
        <ul>
            <li>Pursuing PGDM+MBA in Marketing Management from MIT School of Telecom</li>
            <li>B.com from J.P.G College, M.G.K.V.P University in 2012 with 55.14%</li>
            <li>HSC from AIM College, UP Board Varanasi in 2009 with 70.80%</li>
            <li>HSC from AIM College, UP Board Varanasi in 2007 with 60.14%</li>
        </ul>
        <h2 id="AP">
            <strong>Summer internship programme:</strong>
        </h2>
        <p style="font-size: 12px">Soussi laib, 14 Av. Zerktouni, Agadir
            Intern, [06 & 07 ] - [2023]</p>
        <ul>
            <li>Designing, developing, and maintaining the library website.</li>
            <li>Optimizing search functionality for easy navigation.</li>
            <li>Integrating and maintaining an online catalog system for library resources.</li>
        </ul>


    </div>

</body>

</html>
