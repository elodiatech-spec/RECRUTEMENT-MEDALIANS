<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MSP Medalians - Notre Projet de Santé</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            scroll-behavior: smooth;
        }
        .lucide {
            width: 24px;
            height: 24px;
            stroke-width: 2;
        }
        /* Style pour la nouvelle section Hero avec image de fond */
        .hero-with-bg {
            background-image: url('https://storage.googleapis.com/aai-web-samples/public/centre-de-sante-moderne.jpeg'); /* Image représentative d'un centre de santé */
            background-size: cover;
            background-position: center;
            background-repeat: no-repeat;
            position: relative;
            padding-top: 10rem; /* Ajustez le padding si nécessaire */
            padding-bottom: 10rem; /* Ajustez le padding si nécessaire */
        }
        .hero-overlay {
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background-image: linear-gradient(to top, rgba(6, 78, 59, 0.7), rgba(6, 78, 59, 0.5)); /* Dégradé vert foncé pour la lisibilité */
            z-index: 1;
        }
        .hero-content {
            position: relative;
            z-index: 2;
            color: white;
            text-align: center;
        }

        .section-title {
            @apply text-3xl font-bold text-gray-800 mb-6 text-center;
        }
        .card {
            @apply bg-white rounded-xl shadow-lg overflow-hidden transition-transform duration-300 hover:shadow-xl hover:-translate-y-1;
        }
        .icon-wrapper {
            @apply flex-shrink-0 w-12 h-12 rounded-full bg-emerald-100 text-emerald-700 flex items-center justify-center;
        }
    </style>
</head>
<body class="bg-gray-50">

    <!-- Header --><header class="bg-white shadow-sm sticky top-0 z-50">
        <nav class="container mx-auto px-6 py-4 flex justify-between items-center">
            <h1 class="text-2xl font-bold text-emerald-800">MSP Medalians</h1>
            <div class="space-x-4">
                <a href="#projet" class="text-gray-600 hover:text-emerald-700 font-medium">Notre Projet</a>
                <a href="#orientations" class="text-gray-600 hover:text-emerald-700 font-medium">Nos Orientations</a>
                <a href="#recrutement" class="text-gray-600 hover:text-emerald-700 font-medium">Recrutement</a>
                <a href="https://elodiatech-spec.github.io/ELORECRUIT3/" class="text-gray-600 hover:text-emerald-700 font-medium" target="_blank" rel="noopener noreferrer">Conseils Entretien</a>
            </div>
        </nav>
    </header>

    <!-- Hero Section with Background Image --><section class="hero-with-bg">
        <div class="hero-overlay"></div>
        <div class="container mx-auto px-6 hero-content">
            <h2 class="text-5xl font-bold mb-4">Bienvenue à la MSP Medalians</h2>
            <p class="text-xl text-emerald-100 max-w-3xl mx-auto">La santé augmentée centrée sur l'humain</p>
        </div>
    </section>

    <!-- Section Projet --><section id="projet" class="py-16">
        <div class="container mx-auto px-6">
            <h3 class="section-title">Notre Projet de Santé</h3>
            <div class="h-1 bg-emerald-600 w-24 mx-auto mb-4 rounded-full"></div> 

<div class="max-w-4xl mx-auto bg-white p-8 rounded-xl shadow-lg border border-gray-200">
                <p class="text-gray-700 text-lg mb-4">
                    Le projet d'implantation de la Maison de Santé Pluriprofessionnelle (MSP) Medalians au Lamentin s'inscrit dans la stratégie locale **CAP 2032**, visant à renforcer la cohésion sociale et à offrir un cadre de vie durable.
                </p>
                <p class="text-gray-700 mb-4">
                    En lien avec le **Contrat Local de Santé Intercommunal** (signé avec l'Espace Sud et l'ARS), notre mission est de **réduire les inégalités d'accès aux soins**, de développer la prévention et d'améliorer la coordination entre tous les acteurs de santé du territoire.
                </p>
                <p class="text-gray-700 mb-4">
                    Face aux enjeux sanitaires prioritaires comme la gestion des **maladies chroniques** (diabète, hypertension), la santé mentale et les inégalités dans les quartiers périphériques (QPV), la MSP Medalians apporte une réponse concrète.
                </p>
                <p class="text-gray-700 font-medium">
                    Nous structurons les soins primaires pour offrir une alternative aux soins non programmés et **désengorger les urgences du CHU**, en intégrant une approche globale santé-environnement et en utilisant des outils de coordination modernes.
                </p>
            </div>
        </div>
    </section>

    <!-- Section Orientations --><section id="orientations" class="py-16 bg-gray-100">
        <div class="container mx-auto px-6">
            <h3 class="section-title">Nos 4 Orientations Stratégiques</h3>
            <div class="h-1 bg-emerald-600 w-24 mx-auto mb-4 rounded-full"></div> 

<p class="text-center text-gray-600 max-w-3xl mx-auto mb-12">
                Notre action est guidée par un schéma stratégique clair, partagé par l'ensemble de nos professionnels et partenaires, pour répondre aux besoins spécifiques de notre territoire.
            </p>

            <!-- Schéma --><div class="mb-12 max-w-5xl mx-auto card p-4">
                <img src="https://storage.googleapis.com/aai-web-samples/public/orientatioons%20strategiques%20msp%20medalians.jpeg" alt="Schéma des Orientations Stratégiques de la MSP Medalians" class="rounded-lg object-contain w-full">
            </div>

            <!-- Grille des 4 axes --><div class="grid md:grid-cols-2 gap-8">
                
<!-- Axe 1 --><div class="card p-6">
                    <div class="flex items-center mb-4">
                        <div class="icon-wrapper">
                            <svg class="lucide" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" d="M13 10V3L4 14h7v7l9-11h-7z"></path></svg>
                        </div>
                        <h4 class="text-xl font-bold text-gray-800 ml-4">1. Continuité des Soins</h4>
                    </div>
                    <p class="text-gray-600">
                        Assurer une réponse constante et coordonnée, y compris pour les soins non programmés. Nous facilitons le partage sécurisé d'informations (MSSanté) entre les spécialistes et suivons activement les patients en renoncement aux soins.
                    </p>
                </div>

                <!-- Axe 2 --><div class="card p-6">
                    <div class="flex items-center mb-4">
                        <div class="icon-wrapper">
                            <svg class="lucide" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z"></path></svg>
                        </div>
                        <h4 class="text-xl font-bold text-gray-800 ml-4">2. Prise en Charge des Maladies Chroniques</h4>
                    </div>
                    <p class="text-gray-600">
                        Mettre en place et suivre des protocoles de soins rigoureux (diabète, HTA). Nous coordonnons les parcours avec les partenaires externes (IDEL, MK, HAD, SSIA) et gérons les alertes post-hospitalisation pour un suivi rapide.
                    </p>
                </div>

                <!-- Axe 3 --><div class="card p-6">
                    <div class="flex items-center mb-4">
                        <div class="icon-wrapper">
                            <svg class="lucide" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"></path></svg>
                        </div>
                        <h4 class="text-xl font-bold text-gray-800 ml-4">3. Prévention & Éducation à la Santé</h4>
                    </div>
                    <p class="text-gray-600">
                        Aller au-devant des besoins en gérant des listes de patients éligibles aux campagnes de prévention (dépistage, vaccination). Nous co-organisons l'éducation thérapeutique et sensibilisons aux risques environnementaux (Zika, Sargasses).
                    </p>
                </div>

                <!-- Axe 4 --><div class="card p-6">
                    <div class="flex items-center mb-4">
                        <div class="icon-wrapper">
                            <svg class="lucide" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" d="M17 20h5v-2a3 3 0 00-5.356-1.857M17 20H7m10 0v-2c0-1.657-1.343-3-3-3s-3 1.343-3 3v2m6 0H9m12-7a3 3 0 11-6 0 3 3 0 016 0zm-6 0a3 3 0 11-6 0 3 3 0 016 0zM9 9a3 3 0 11-6 0 3 3 0 016 0z"></path></svg>
                        </div>
                        <h4 class="text-xl font-bold text-gray-800 ml-4">4. Lutte contre la Précarité & Accès aux Droits</h4>
                    </div>
                    <p class="text-gray-600">
                        Identifier activement les patients en situation de précarité ou d'isolement (QPV). Nous facilitons l'accès aux droits (Mon Espace Santé) et orientons vers les partenaires sociaux (CCAS) pour une prise en charge globale.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Section Recrutement --><section id="recrutement" class="py-20">
        <div class="container mx-auto px-6">
            <h3 class="section-title">Notre Recrutement : Résultats Attendus</h3>
            <div class="h-1 bg-emerald-600 w-24 mx-auto mb-4 rounded-full"></div> 

<p class="text-center text-gray-600 max-w-3xl mx-auto mb-12">
                Pour concrétiser cette vision, nous recrutons **5 Assistant(e)s Médicaux**. Ces postes ne sont pas de simples fonctions administratives ; ce sont des rôles pivots essentiels à la réussite de nos orientations stratégiques.
            </p>

            <div class="max-w-4xl mx-auto space-y-6">
                
<!-- Résultat 1 --><div class="bg-white p-6 rounded-lg shadow-md border border-gray-200">
                    <h4 class="text-lg font-semibold text-emerald-800 mb-2">1. Libérer du Temps Médical et Assurer la Continuité</h4>
                    <p class="text-gray-700">
                        **Résultat attendu :** Une équipe opérationnelle permettant une couverture de soins de **8h à 23h**. En prenant en charge la pré-consultation, la gestion administrative et la coordination, les assistants permettront aux médecins de se concentrer sur les diagnostics et les actes complexes, tout en assurant une réponse aux soins non programmés.
                    </p>
                </div>

                <!-- Résultat 2 --><div class="bg-white p-6 rounded-lg shadow-md border border-gray-200">
                    <h4 class="text-lg font-semibold text-emerald-800 mb-2">2. Renforcer le Suivi des Parcours de Soins et la Prévention</h4>
                    <p class="text-gray-700">
                        **Résultat attendu :** Une augmentation mesurable du suivi des protocoles de maladies chroniques et des campagnes de prévention. Les assistants seront les garants de l'application de nos axes 2 et 3, en gérant activement les listes de rappel, en préparant les dossiers et en informant les patients.
                    </p>
                </div>

                <!-- Résultat 3 --><div class="bg-white p-6 rounded-lg shadow-md border border-gray-200">
                    <h4 class="text-lg font-semibold text-emerald-800 mb-2">3. Devenir un Pilote de la Coordination E-Santé</h4>
                    <p class="text-gray-700">
                        **Résultat attendu :** Une équipe experte et motrice sur les outils numériques (Doctolib MSP, MSSanté, Mon Espace Santé). Ils assureront la fluidité de l'information (Axe 1) et géreront efficacement les **20% de téléconsultations**, devenant le hub de notre coordination pluriprofessionnelle.
                    </p>
                </div>

                 <!-- Résultat 4 --><div class="bg-white p-6 rounded-lg shadow-md border border-gray-200">
                    <h4 class="text-lg font-semibold text-emerald-800 mb-2">4. Améliorer l'Accueil et l'Orientation des Publics Fragiles</h4>
                    <p class="text-gray-700">
                        **Résultat attendu :** Un point d'entrée bienveillant et efficace pour les patients de nos territoires prioritaires (QPV). Les assistants seront formés pour identifier les signes de précarité (Axe 4), rassurer et orienter vers les bons partenaires, luttant ainsi activement contre le renoncement aux soins.
                    </p>
                </div>
            </div>

            <!-- Section Planning MODIFIÉE --><div class="max-w-5xl mx-auto mt-16"> <!-- Changement: max-w-4xl -> max-w-5xl -->
                <h4 class="text-2xl font-bold text-gray-800 mb-6 text-center">Organisation : Simulateur de Planning</h4>
                <div class="bg-white p-8 rounded-lg shadow-md border border-gray-200 space-y-5">
                    <p class="text-sm text-gray-600 italic text-center">
                        <strong>Simulateur de planning :</strong> Cet outil est à titre indicatif.<br>
                        Modifiez les horaires pour calculer automatiquement le total hebdomadaire.
                    </p>

                    <!-- Simulateur interactif -->
                    <div class="overflow-x-auto">
                        <table class="w-full text-sm text-left text-gray-700" id="planningSimulator">
                            <thead class="bg-gray-100">
                                <tr>
                                    <th class="p-2 font-medium">Jour</th>
                                    <th class="p-2 font-medium">Matin Début</th>
                                    <th class="p-2 font-medium">Matin Fin</th>
                                    <th class="p-2 font-medium">AM Début</th>
                                    <th class="p-2 font-medium">AM Fin</th>
                                    <th class="p-2 font-medium text-right">Total Jour</th>
                                </tr>
                            </thead>
                            <tbody>
                                <tr class="border-b" data-day="lundi">
                                    <td class="p-2 font-semibold">Lundi</td>
                                    <td class="p-2"><select class="time-select border rounded px-1" id="lundi_matin_debut"></select></td>
                                    <td class="p-2"><select class="time-select border rounded px-1" id="lundi_matin_fin"></select></td>
                                    <td class="p-2"><select class="time-select border rounded px-1" id="lundi_am_debut"></select></td>
                                    <td class="p-2"><select class="time-select border rounded px-1" id="lundi_am_fin"></select></td>
                                    <td class="p-2 text-right font-bold" id="lundi_total">0.00h</td>
                                </tr>
                                <tr class="border-b" data-day="mardi">
                                    <td class="p-2 font-semibold">Mardi</td>
                                    <td class="p-2"><select class="time-select border rounded px-1" id="mardi_matin_debut"></select></td>
                                    <td class="p-2"><select class="time-select border rounded px-1" id="mardi_matin_fin"></select></td>
                                    <td class="p-2"><select class="time-select border rounded px-1" id="mardi_am_debut"></select></td>
                                    <td class="p-2"><select class="time-select border rounded px-1" id="mardi_am_fin"></select></td>
                                    <td class="p-2 text-right font-bold" id="mardi_total">0.00h</td>
                                </tr>
                                <tr class="border-b" data-day="mercredi">
                                    <td class="p-2 font-semibold">Mercredi</td>
                                    <td class="p-2"><select class="time-select border rounded px-1" id="mercredi_matin_debut"></select></td>
                                    <td class="p-2"><select class="time-select border rounded px-1" id="mercredi_matin_fin"></select></td>
                                    <td class="p-2"><select class="time-select border rounded px-1" id="mercredi_am_debut"></select></td>
                                    <td class="p-2"><select class="time-select border rounded px-1" id="mercredi_am_fin"></select></td>
                                    <td class="p-2 text-right font-bold" id="mercredi_total">0.00h</td>
                                </tr>
                                <tr class="border-b" data-day="jeudi">
                                    <td class="p-2 font-semibold">Jeudi</td>
                                    <td class="p-2"><select class="time-select border rounded px-1" id="jeudi_matin_debut"></select></td>
                                    <td class="p-2"><select class="time-select border rounded px-1" id="jeudi_matin_fin"></select></td>
                                    <td class="p-2"><select class="time-select border rounded px-1" id="jeudi_am_debut"></select></td>
                                    <td class="p-2"><select class="time-select border rounded px-1" id="jeudi_am_fin"></select></td>
                                    <td class="p-2 text-right font-bold" id="jeudi_total">0.00h</td>
                                </tr>
                                <tr class="border-b" data-day="vendredi">
                                    <td class="p-2 font-semibold">Vendredi</td>
                                    <td class="p-2"><select class="time-select border rounded px-1" id="vendredi_matin_debut"></select></td>
                                    <td class="p-2"><select class="time-select border rounded px-1" id="vendredi_matin_fin"></select></td>
                                    <td class="p-2"><select class="time-select border rounded px-1" id="vendredi_am_debut"></select></td>
                                    <td class="p-2"><select class="time-select border rounded px-1" id="vendredi_am_fin"></select></td>
                                    <td class="p-2 text-right font-bold" id="vendredi_total">0.00h</td>
                                </tr>
                                <tr class="border-b" data-day="samedi">
                                    <td class="p-2 font-semibold">Samedi</td>
                                    <td class="p-2"><select class="time-select border rounded px-1" id="samedi_matin_debut"></select></td>
                                    <td class="p-2"><select class="time-select border rounded px-1" id="samedi_matin_fin"></select></td>
                                    <td class="p-2"><select class="time-select border rounded px-1" id="samedi_am_debut"></select></td>
                                    <td class="p-2"><select class="time-select border rounded px-1" id="samedi_am_fin"></select></td>
                                    <td class="p-2 text-right font-bold" id="samedi_total">0.00h</td>
                                </tr>
                            </tbody>
                            <tfoot class="bg-gray-100 font-semibold text-lg">
                                <tr>
                                    <td colspan="5" class="p-3">Total Hebdomadaire</td>
                                    <td class="p-3 text-right" id="totalSemaine">0.00h</td>
                                </tr>
                                <tr>
                                    <td colspan="5" class="p-3">Heures Supplémentaires (&gt; 35h)</td>
                                    <td class="p-3 text-right text-gray-900" id="totalSupp">0.00h</td>
                                </tr>
                            </tfoot>
                        </table>
                    </div>
                </div>
            </div>

        </div>
    </section>

    <!-- Footer --><footer class="bg-gray-800 text-gray-300 py-12"> <!-- Changement: py-8 -> py-12 -->
        <div class="container mx-auto px-6 text-center">

            <!-- Encadré 3D pour logo et réseaux -->
            <div class="max-w-md mx-auto bg-gray-700 p-6 rounded-xl shadow-2xl border-t border-l border-gray-600">
                <!-- Logo Elodia Tech -->
                <img src="https://elodiatech.com/wp-content/uploads/2023/11/elodia-tech-LOGO-B.png" alt="Logo Elodia Tech" class="mx-auto h-12 w-auto mb-6">

                <!-- Liens Réseaux Sociaux -->
                <div class="flex justify-center space-x-6">
                    <!-- LinkedIn -->
                    <a href="https://www.linkedin.com/public-profile/settings?trk=d_flagship3_profile_self_view_public_profile" target="_blank" rel="noopener noreferrer" class="text-gray-400 hover:text-white" aria-label="LinkedIn">
                        <span class="sr-only">LinkedIn</span>
                        <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true"><path d="M19 0h-14c-2.761 0-5 2.239-5 5v14c0 2.761 2.239 5 5 5h14c2.762 0 5-2.239 5-5v-14c0-2.761-2.238-5-5-5zm-11 19h-3v-11h3v11zm-1.5-12.268c-.966 0-1.75-.79-1.75-1.764s.784-1.764 1.75-1.764 1.75.79 1.75 1.764-.783 1.764-1.75 1.764zm13.5 12.268h-3v-5.604c0-3.368-4-3.113-4 0v5.604h-3v-11h3v1.765c1.396-2.586 7-2.777 7 2.476v6.759z"/></svg>
                    </a>
                    <!-- Facebook -->
                    <a href="https://www.facebook.com/share/1BFWdaMJxF/?mibextid=wwXIfr" target="_blank" rel="noopener noreferrer" class="text-gray-400 hover:text-white" aria-label="Facebook">
                        <span class="sr-only">Facebook</span>
                        <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true"><path d="M9 8h-3v4h3v12h5v-12h3.642l.358-4h-4v-1.667c0-.955.192-1.333 1.115-1.333h2.885v-5h-3.808c-3.596 0-5.192 1.583-5.192 4.615v3.385z"/></svg>
                    </a>
                    <!-- Instagram -->
                    <a href="https://www.instagram.com/elodia.tech?igsh=bGRmdngxZzl4anFs" target="_blank" rel="noopener noreferrer" class="text-gray-400 hover:text-white" aria-label="Instagram">
                        <span class="sr-only">Instagram</span>
                        <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true"><path d="M12 2.163c3.204 0 3.584.012 4.85.07 3.252.148 4.771 1.691 4.919 4.919.058 1.265.07 1.646.07 4.85s-.012 3.584-.07 4.85c-.148 3.227-1.669 4.771-4.919 4.919-1.266.058-1.646.07-4.85.07s-3.584-.012-4.85-.07c-3.252-.148-4.771-1.691-4.919-4.919-.058-1.265-.07-1.646-.07-4.85s.012-3.584.07-4.85c.148-3.227 1.669-4.771 4.919-4.919 1.266-.058 1.646-.07 4.85-.07zm0-2.163c-3.259 0-3.667.014-4.947.072-4.358.2-6.78 2.618-6.98 6.98-.059 1.281-.073 1.689-.073 4.948s.014 3.667.072 4.947c.2 4.358 2.618 6.78 6.98 6.98 1.281.059 1.689.073 4.948.073s3.667-.014 4.947-.072c4.358-.2 6.78-2.618 6.98-6.98.059-1.281.073-1.689.073-4.948s-.014-3.667-.072-4.947c-.2-4.358-2.618-6.78-6.98-6.98-1.281-.059-1.689-.073-4.948-.073zm0 5.838c-3.403 0-6.162 2.759-6.162 6.162s2.759 6.162 6.162 6.162 6.162-2.759 6.162-6.162-2.759-6.162-6.162-6.162zm0 10.162c-2.209 0-4-1.791-4-4s1.791-4 4-4 4 1.791 4 4-1.791 4-4 4zm6.406-11.845c-.796 0-1.441.645-1.441 1.44s.645 1.44 1.441 1.44 1.441-.645 1.441-1.44-.645-1.44-1.441-1.44z"/></svg>
                    </a>
                    <!-- Website -->
                    <a href="https://elodiatech.com/" target="_blank" rel="noopener noreferrer" class="text-gray-400 hover:text-white" aria-label="Site Web">
                        <span class="sr-only">Site Web</span>
                        <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-1 17.93c-3.95-.49-7-3.85-7-7.93 0-.62.08-1.21.21-1.79L9 15v1c0 1.1.9 2 2 2v1.93zm6.9-2.54c-.26-.81-1-1.39-1.9-1.39h-1v-3c0-.55-.45-1-1-1h-2v-2c0-.55-.45-1-1-1h-2V7h2c.55 0 1-.45 1-1V5h2c.55 0 1-.45 1-1V3.1c1.06.45 2.03 1.1 2.84 1.89C18.28 6.4 18.7 7.8 18.7 9.3c0 1.96-.8 3.73-2.09 4.93z"/></svg>
                    </a>
                </div>
            </div>

            <p class="mt-8">&copy; 2024 MSP Medalians. Tous droits réservés.</p> <!-- Changement: margin-top ajouté -->
            <p class="text-sm text-gray-400 mt-1">Projet de Santé pour Le Lamentin, Martinique.</p>

        </div>
    </footer>

    <!-- Script pour le simulateur de planning -->
    <script>
        document.addEventListener('DOMContentLoaded', function() {
            const timeSelects = document.querySelectorAll('.time-select');
            const days = ['lundi', 'mardi', 'mercredi', 'jeudi', 'vendredi', 'samedi'];
            
            // 1. Populer les menus déroulants
            const options = ['Repos'];
            for (let h = 7; h <= 23; h++) {
                let hour = h < 10 ? '0' + h : h;
                options.push(`${hour}:00`);
                if (h < 23) {
                    options.push(`${hour}:30`);
                }
            }
            
            timeSelects.forEach(select => {
                let optionsHtml = '';
                options.forEach(option => {
                    optionsHtml += `<option value="${option}">${option}</option>`;
                });
                select.innerHTML = optionsHtml;
                select.addEventListener('change', calculateTotals);
            });

            // 2. Définir les valeurs par défaut (basé sur Planning 1)
            function setDefaultValues() {
                try {
                    // Lundi
                    document.getElementById('lundi_matin_debut').value = '08:00';
                    document.getElementById('lundi_matin_fin').value = '12:00';
                    document.getElementById('lundi_am_debut').value = '13:00';
                    document.getElementById('lundi_am_fin').value = '17:00';
                    // Mardi
                    document.getElementById('mardi_matin_debut').value = '08:00';
                    document.getElementById('mardi_matin_fin').value = '12:00';
                    document.getElementById('mardi_am_debut').value = '13:00';
                    document.getElementById('mardi_am_fin').value = '17:00';
                    // Mercredi
                    document.getElementById('mercredi_matin_debut').value = '08:00';
                    document.getElementById('mercredi_matin_fin').value = '13:00';
                    document.getElementById('mercredi_am_debut').value = 'Repos';
                    document.getElementById('mercredi_am_fin').value = 'Repos';
                    // Jeudi
                    document.getElementById('jeudi_matin_debut').value = '08:00';
                    document.getElementById('jeudi_matin_fin').value = '13:00';
                    document.getElementById('jeudi_am_debut').value = 'Repos';
                    document.getElementById('jeudi_am_fin').value = 'Repos';
                    // Vendredi
                    document.getElementById('vendredi_matin_debut').value = '08:00';
                    document.getElementById('vendredi_matin_fin').value = '13:00';
                    document.getElementById('vendredi_am_debut').value = 'Repos';
                    document.getElementById('vendredi_am_fin').value = 'Repos';
                    // Samedi
                    document.getElementById('samedi_matin_debut').value = '08:30';
                    document.getElementById('samedi_matin_fin').value = '12:30';
                    document.getElementById('samedi_am_debut').value = 'Repos';
                    document.getElementById('samedi_am_fin').value = 'Repos';
                } catch(e) {
                    console.error("Erreur lors de la définition des valeurs par défaut:", e);
                }
            }

            // 3. Fonction pour parser le temps (ex: "08:30" -> 8.5)
            function parseTime(timeStr) {
                if (timeStr === 'Repos' || !timeStr) {
                    return 0;
                }
                const [hours, minutes] = timeStr.split(':').map(Number);
                return hours + (minutes / 60);
            }

            // 4. Fonction principale de calcul
            function calculateTotals() {
                let totalSemaine = 0;
                
                days.forEach(day => {
                    const matinDebut = parseTime(document.getElementById(`${day}_matin_debut`).value);
                    const matinFin = parseTime(document.getElementById(`${day}_matin_fin`).value);
                    const amDebut = parseTime(document.getElementById(`${day}_am_debut`).value);
                    const amFin = parseTime(document.getElementById(`${day}_am_fin`).value);
                    
                    let totalMatin = Math.max(0, matinFin - matinDebut);
                    let totalAm = Math.max(0, amFin - amDebut);
                    
                    if (matinDebut === 0 || matinFin === 0) totalMatin = 0;
                    if (amDebut === 0 || amFin === 0) totalAm = 0;

                    const totalJour = totalMatin + totalAm;
                    totalSemaine += totalJour;
                    
                    document.getElementById(`${day}_total`).textContent = `${totalJour.toFixed(2)}h`;
                });

                // 5. Mettre à jour les totaux
                document.getElementById('totalSemaine').textContent = `${totalSemaine.toFixed(2)}h`;
                
                const totalSuppEl = document.getElementById('totalSupp');
                const heuresSupp = totalSemaine - 35;
                
                if (heuresSupp > 0) {
                    totalSuppEl.textContent = `${heuresSupp.toFixed(2)}h`;
                    totalSuppEl.className = 'p-3 text-right text-red-600 font-bold';
                } else {
                    totalSuppEl.textContent = '0.00h';
                    totalSuppEl.className = 'p-3 text-right text-gray-900 font-bold';
                }
            }

            // Initialisation
            setDefaultValues();
            calculateTotals();
        });
    </script>

</body>
</html>


