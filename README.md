# **[Application de Mentorat]** 

# **Besoins et conception**

## 1. Présentation du projet

*Décrire la solution proposée. Inclure le public cible et les avantages commerciaux de la solution.*

FuzeScrum est une société de 180 personnes qui propose des services en conseil agile aux entreprises aux USA, en Europe et en Asie.

FuzeScrum a le projet de développer son activité en créant une application pour organiser et gérer le Mentorat interne des entreprises.

Une étude de marché préalable a montré une forte demande de Mentorat en interne des entreprises. 

Il a donc été décidé de réaliser un POC (proof of concept) d’une application visant à faciliter les activités de mentorat sur la base du volontariat. 

Le public cible sera dans un premier temps les employés de FuzeScrum conseiller en agilité pour les entreprises, mais l’application devra étendre son champ d’activité en proposant ses services de Mentorat à des employés travaillant dans d’autres secteurs tels que la tech, le médical, la comptabilité.

Les avantages commerciaux de la solution d’application de mentorat proposé sont :

·     L’application utilisera une intelligence artificielle, ce qui sera son principal avantage concurrentiel.

·     Fort de son expérience déjà acquise de conseil en agilité pour les entreprises, cet applicatif renforcera son offre de service et permettra de s’ouvrir à de nouveaux marchés en proposant un outil performant pour une monté en compétence des salariés de l’entreprise ce qui est en parfaite adéquation avec les objectifs de la méthodologie agile.

**1.1 Objectifs du projet** 

*Décrire les objectifs du projet (en 2 à 3 phrases), avec notamment le ou les problèmes résolus.* 

L’application de Mentorat aura pour objectifs :

- Optimiser la mise en relation entre un Mentor expert dans son     domaine d’activité et un Mentoré qui a le désir de progresser, grâce à des     critères de validation réciproque et l’utilisation d’une IA 
- Établir un rythme de sessions régulier de Mentorat grâce à un outil     de programmation de sessions.
- Proposer des outils de contact et de suivi afin de clarifier au     mieux les attentes et objectifs des parties prenantes Mentor et Mentoré.

Problèmes, besoins résolus :

·     Optimiser la rencontre d’un Mentor et d’un Mentoré grâce à l’IA pour faire correspondre au mieux les besoins de chacune des parties.

·     Automatiser la prise de session régulière 

·     Compte rendu de session et objectif entre sessions 

·     Historique de sessions.

·     Outil facilitant la prise de notes grâce à l’IA.

·     Faciliter la communication Mentor Mentoré

·     Notification applicative des activités de son binôme en Mentorat

**1.2 Éléments hors périmètre**

Les objectifs envisagés mais qui ne sont pas couverts par ce projet : 

·     Dans cette première version de développement de l’application les critères de validation pour associer Mentor et Mentoré ne couvriront que le domaine d’expertise des employés présent dans la société FuzeScrum, les actions de Mentorat concernant d’autres secteurs d’activité seront reportées à une version ultérieure.

·     Les relations d’un mentoré avec plusieurs Mentors et inversement d’un Mentor avec plusieurs Mentoré ne seront pas couverts. Seule la relation One to One sera développée dans un premier temps.

·     Un outil de gestion de projet tel qu’un tableau Kanban (Workflow) ne sera pas développé dans cette version. On pourra envisager dans une version ultérieure l’intégration d'applications à forte maturité telles que Trello ou Jira. Pour cette première version, on se contentera d’une to do listes pour chaque session.

·     D’autres outils utilisés dans la tech pour la gestion de versions tel que GitHub ou Bitbucket ne seront pas intégré pour en faciliter l’accès mais pourront l’être dans des version ultérieur

·     Un transfert des horaires de sessions sur Google Agenda ne sera pas couvert.

·     Une boite mail ne sera pas ajoutée à l’application les utilisateurs correspondront avec leur boite mail personnel.

·     Avoir accès aux vidéos de Mentorat des autres mentorés, avec un système d’appréciation et de filtres.

·     Possibilité du Mentor de laisser un enregistrement vidéo sans que le Mentoré soit présent, pour répondre aux questions, fixer des objectifs dans le cas ou exceptionnellement les parties prenantes ne pourrait pas assister à une des sessions.

**1.3 Métriques du projet** 

*Comment mesurez-vous la réussite ?* 

Les métriques utilisées pour mesurer la réussite du projet application de mentorat :

- Le respect du budget de développement de l’application soit 5     personnes à plein temps, sur 6 mois.
- La qualité de l’application sera évaluée suivant :

​      \- Le nombre de nouveaux inscrits.

​      \- Le pourcentage de contrat rompu avant la date prévue.

​      \- Le pourcentage et la durée de Mentor sans Mentoré et inversement.

​      \- Le pourcentage de réussite au contrat de Mentorat.

​      \- Le nombre de contrats en cours.

​      \- Le pourcentage d’avancement de chaque contrat.

​      \- Des formulaire qui mesure la satisfaction Mentore Mentoré à la fin de chaque session et en fin de contrat.

​      \- Un formulaire pour mesurer la satisfaction des utilisateurs de l’application.

 

\2. Fonctionnalités 

 

**2.1 Fonctionnalités du projet** 

 

*Incluez une liste de fonctionnalités.*

La liste des fonctionnalités du projet :

·     Gestion de compte utilisateur :

\- Inscription des utilisateurs dans l’application.

\- Connexion des utilisateurs déjà inscrits.

\- Possibilité de récupérer par E-mail ses identifiants en cas d'oubli.

\- Possibilité d’éditer ses informations de compte.

·     Gestion du choix de devenir Mentor ou Mentoré :

\- Choisir une ou des expertises au sujet du Mentorat.

\- Activation de L’IA pour proposer un Mentor aux Mentorés.

\- Possibilité d’édition des critères de choix.

·     Gestion de Contrats :

\- Fonctionnalité de demande d'être Mentoré ou Mentor.

\- Fonctionnalité d’acceptation d’un Mentor.

\- Fonctionnalité de rupture de contrat.

·     Gestion de la programmation de session (géré par le Mentor) :

​            \- Ajouter choix de la récurrence de la session auto programmé ;

​            \- Éditer.

​            \- Supprimer.

​            \- Rappel de session.

·     Gestion des objectifs de session (géré par le Mentor) :

​            \- Ajouter dans une to do liste.

​            \- Éditer.

​            \- Supprimer.

·     Gestion en cours de session

​            \- Accès visioconférence de la session (paramétrage son, caméra).

​            \- fonctionnalité de partage d’écran.

\- Fonctionnalité d’enregistrement / arrêt enregistrement de la visioconférence.

\- Stockage / suppression des vidéos de session enregistré dans l’application.

\- IA qui établit le transcrit de la vidéo enregistrée.

\- Outil bloc note.

**2.1 User stories et critères d’acceptation**

*Incluez les user stories et critères d'acceptation ici.*

**[Accès] Inscription des nouveaux utilisateurs de l’application**

Description

En tant que visiteur je souhaite m’inscrire à l’application de Mentorat.

·     Un formulaire d’inscription apparaît avec les champs requis suivants :

​            \- “Prénom“.

​            \- “Nom“.

​            \- “Adresse E-mail “ (message d'alerte en cas de non-conformité).

​            \- “Password“ (caractère alphanumérique et spéciaux requis).

​            \- “Confirm your password“.

​            \- Bouton Switch On/Off => “Devenir Mentoré “.

​        Une Modale s’ouvre => “Vos motivations“ avec un champ texte.

​            \- Bouton Switch On/Off => “Devenir Mentor “.

​        Une Modale s’ouvre => “Vos motivations“ avec un champ texte ;

​            \- Case à Cocher, accepter les conditions générales d’utilisation RGPD.

·     Un bouton => “CONNEXION“.

·     Au clic du bouton CONNEXION

\-     Je suis redirigé vers une page pour finaliser mon inscription.

 

**[Gestion contrat Mentorat] Choix des l’utilisateurs étape 2 de l’inscription**

Description

En tant que visiteur je souhaite poursuivre mon inscription et renseigner mon choix de sujet de Mentorat et mes disponibilités.

\-     Titre => “Finaliser votre inscription“

\-     Une liste déroulante Multi sélections (case à coché), label => “Expertises du Mentorat » =

Consultant Agile

Chef de projet

Product Owner

…

​            Les expertises choisies apparaissent sous forme de label décochable en dessous.

\-     Une liste déroulante Multi sélections (case à cocher) => "MES DISPONIBILITÈS" pour indiquer un jour de la semaine ou je suis disponible pour être Mentoré 

Lundi

Mardi

Mercredi

…

​            Les jours choisis apparaissent sous forme de label décochable en dessous.

\-     Une liste déroulante Multi sélections (case à cocher) devant chaque label jour choisi permettant de choisir l’heure disponible pour être Mentoré.

8 AM

12 PM

… 

On va limiter à 2 ou 3 heures pour le même jour pour ne pas surcharger l’écran

\-     Une liste déroulante choix unique => "MA FRÈQUENCE", permet de déterminer combien de fois par semaine je suis prêt à être Mentoré :

1 fois / semaine

2 fois / semaine

…

Ce champ n’est pas requis.

\-     Un date-picker => "DATE DE FIN", me permet de spécifier jusqu’à quelle date je pense être disponible pour mes séances de Mentorat.

Ce champ n’est pas requis.

·     Un Bouton => "VALIDER " me permet d’enregistrer mes attentes en termes de Mentorat.

·     Un Bouton en haut de page me permet de revenir à la page précédente pour pouvoir apporter des modifications le cas échéant.

Si je suis Mentor, j’ai finalisé mon inscription et je suis redirigé vers la page mes sessions pour une prise en main de la programmation d’une session.

Si je suis Mentoré j’ai une étape supplémentaire dans mon processus d’inscription afin de choisir mon Mentor.

**[Accès] choix du Mentor étape 3 de l’inscription pour le Mentoré**

Description

En tant que visiteur ayant fait le choix de Mentoré je souhaite choisir mon Mentor et ainsi finaliser mon inscription.

·     Un titre => "Suggestions de Mentor" apparaît en dessous.

·     L’IA calcule et affiche en dessous la liste des Mentor disponibles pouvant correspondre à mes choix 

·     Des containers (languettes) sélectionnable apparaissent en asynchrone (au fur et à mesure des calculs de L’IA), elles contiennent chacune des informations d’un Mentor pouvant correspondre à mes attentes :

\-     "Nom / Prénom".

\-     Jour et heure compatible avec mes choix.

\-     Domaines d’expertise compatibles avec mes choix.

\-     Pourcentage de match entre Mentor /Mentoré.

Les languettes de Mentor son ordonnées par % de Match décroissant.

On n’affiche pas les Mentor sous les 50% de concordance.

·     J’ai la possibilité d’avoir plus d’information sur les Mentor proposés me permettant d’affiner mon choix, sur chaque languette de Mentor un chevron est placé à droite et qui une foi cliquée fait apparaître une Modal avec les informations concernant le Mentor choisit :

\-     Une photo du Mentor si disponible.

\-     "Nom".

\-     "Poste".

\-     "Durée du Mentorat" (calculé si le Mentor à définit une fin)

\-     "Disponibilités" (Affiche les jour et heure de disponibilité que l’on a avec le Mentor)

\-     "Fréquence des sessions".

\-     "Les expertises du Mentor" (au moins une correspond à nos attentes)

·     Cette page n’affiche que 5 suggestions de Mentor à la fois pour ne pas surcharger la page, un menu de page 1/2/3 permettra d’afficher les autres choix possibles 3 par 3 le cas échéant et sera placé à côté du titre "Suggestions de Mentor".

- Je clique sur 1 Mentor pour valider mon choix la     languette s’allume en vert, si je clique sur un autre Mentor la languette     précédente perd sa couleur verte au bénéfice de cette nouvelle languette     sélectionnée.
- À tout moment je peux revenir sur mes critères de     recherche de Mentorat en haut de page et relancer L’IA en cliquant sur le bouton     VALIDER pour qu’elle m’affiche d’autres Mentor pouvant correspondre.

·     Un Bouton en haut de page me permet de revenir à la page précédente pour pouvoir apporter des modifications le cas échéant.

- Un Bouton se dégrise quand une languette désignant un     Mentor est sélectionnée => "ENREGISTRER " me permet     d’enregistrer mon choix de Mentor.
- Je suis redirigé vers la page mes sessions.
- Un E-mail est envoyé au Mentor et Mentoré pour leur     signaler qu’un partenariat Mentor / Mentoré les associe.

·     Une notification est également envoyée au Mentor et Mentoré dans l’application.

Le Mentor choisit, avec un contrat de Mentorat en cours n'apparaît plus dans la liste des propositions de l’IA à d’autres utilisateurs désirant être Mentoré.

Une fois validé sont enregistrement le Mentoré est redirigé vers la page sessions afin d’avoir accès directement à l’outil qui lui permet de savoir si une prochaine session (Visio) a déjà été programmée le cas échéant par son Mentor.

**[Accès] Affichage profil utilisateur**

Description

En tant qu’utilisateur, je veux avoir accès à mon profil.

·     Quand je clique en haut à droite de l’application j’affiche ma page de profil qui contient 3 modules au centre de la page :

\-     1ère languette accordéon => “Informations générales“.

\-     2eme languette accordéon => “Mon profil Mentor/ Mentoré“.

\-     3em languette accordéon => “Mon Mentor /Mentoré“.

Chaque languette accordéon dispose d’un chevron qui permet d’ouvrir et dévoile des informations provenant de mon inscription rangée suivant ces 3 catégories.

**[Accès] Modification de son profil utilisateur 1/4** 

Description

En tant qu'utilisateur, je veux un rappel de mes informations de profil enregistré dans la première partie de mon inscription.

·     Sur la page profil je clique la 1ére languette accordéon => “Information générales“, l’accordéon s’ouvre et affiche les informations éditables suivante :

\-     Photo

\-     E-mail

\-     Nom

\-     Mot de passe

\-     Poste

\-     Bouton Switch On/Off => “Devenir Mentoré “.

\-     Bouton Switch On/Off => “Devenir Mentor “.

\-     Une Modale => “Vos motivations“ avec un champ texte.

·     L’édition des champs devient possible quand je clique sur un Icon ayant la forme d’un crayon il devient vert placé à côté du titre “Information générales“

**[Accès] Modification de son profil utilisateur 2/4**

Description

En tant qu'utilisateur, je veux pouvoir modifier mes informations concernant mes choix pour devenir Mentor ou Mentoré.

·     Sur la page profil je clique la 2em languette accordéon => “Mon profil Mentor/ Mentoré“, l’accordéon s’ouvre et affiche les informations éditables suivante :

\-     Expériences -> Listes déroulantes multi section.

\-     Mes disponibilités -> Listes déroulantes multi section.

\-     Ma fréquence -> liste déroulante

\-     Date de fin (de mon contrat de Mentorat, non requis) => date-picker

\-     Mettre en pause -> date-picker

\-     Arrêter mon contrat de mentorat -> bouton switch On / Off :

Si activé une Modal s’ouvre pour demander confirmation.

·     L’édition des champs devient possible quand je clique sur un Icon ayant la forme d’un crayon il devient vert placé à côté du titre “Mon profil Mentor/ Mentoré“. 

**[Accès] Modification de son profil utilisateur 3/4**

Description

En tant qu'utilisateur, je veux pouvoir avoir accès aux informations concernant mon Mentor ou Mentoré.

·     Sur la page profil je clique la 3em languette accordéon => “Mon Mentor /Mentoré“, l’accordéon s’ouvre et affiche les informations éditables suivante :

\-     Nom

\-     E-mail

\-     Poste

\-     Sujet du Mentorat

**[Accès] Affichage des menus de l’utilisateurs**

Description

En tant qu'utilisateur je veux pouvoir accéder facilement aux fonctionnalités dont j’ai besoin.

·     En haut à Gauche un burger Menu me permet d’accéder à différentes pages de l’application :

\1.   Mes sessions

\2.   Dernière session

\3.   Mes notes

\-     Label 1

Note 1

Note 2

\-     Label 2

\-     Ajouter une note +

\4.   Logout

Un raccourci Mes sessions est également présent en bas à gauche sur tous les écrans de l’application.

**[Accès] Connexion d’un utilisateur déjà inscrit**

Description

En tant qu’utilisateur déjà inscrit à l’application si je me déconnecte je souhaite me reconnecter.

·     Un formulaire de connexion s’affiche avec les champs requis suivant :

\- Adresse E-mail.

\- Password.

·     Un bouton => “CONNEXION“ :

\-     Si E-mail ou mot de passe son incorrect un message d’erreur apparaît.

\-     Si E-mail et mot de passe sont corrects, je suis redirigé vers la page mes sessions.

·     Un lien “Mot de passe oublié“ ouvre une Modal ayant pour titre => “Réinitialiser votre mot de passe“ avec un champs :

\-     Adresse E-mail.

\-     Un bouton => “RÈINITIALISER“ -> un email pour réinitialiser le mot de passe utilisateur est envoyé

·     Un bouton connexion Google me permet de me connecter directement.

**[Accès] Réinitialisation de mot de passe**

Description

En tant qu’utilisateur je souhaite réinitialiser mon mot de passe

Une fois avoir cliqué sur le lien mot de passe oublié et renseigné mon E-mail sur la page de connexion, je reçois un message sur ma boite mail avec un lien qui me redirige vers une page avec un formulaire pour réinitialiser mon mot de passe avec les champs suivant :

- Nouveau mot de passe (caractères alphanumériques et     spéciaux requis)
- Confirmation de mot de passe         

 **[Accès] Authentification SSO Google**

Description

En tant qu'utilisateur je veux m'authentifier via mon compte google afin d'accéder au portail sans saisir de compte/mot de passe applicatif.

·     Si l'utilisateur n'est pas déjà en session, il doit d'abord s'authentifier via son compte google

(Mécanismes standards gérés par les apis google)

·     Une fois que la session de l’utilisateur est validée, on bascule sur la Home page.

·     Lorsque la session de l’utilisateur est expirée, il doit de nouveau passer par cette phase d’identification. 

**[Gestion Session Mentorat] Programmer une session de Mentorat**

Description

En tant que Mentor, je veux programmer une session de Mentorat.

Sur la page sessions du Mentor. 

Part 1

En haut de la page sessions je dispose d’un espace formulaire titré => “PROGRAMMER UNE SESSION” qui contient les champs suivants :

·     “Programmer une session“ -> date-picker pour programmer le jour de la prochaine session.

- “Choisir une heure“ -> liste déroulante me permet de     sélectionner une heure de rendez-vous.
- “Autoprogrammer cet horaire récurrent“ -> Bouton     Switch On / Off me permet de conserver si je le souhaite automatiquement     les réglages de jour et l’heure choisie pour les prochaines sessions, sans     besoin de le paramétrer à chaque fois.
- Un bouton => “VALIDER” me permet de valider la     programmation de la prochaine session.
- Un E-mail est envoyé aux parties prenantes pour leur     signifier la date et l’heure de leur future réunion.
- Une Alerte s’affiche dans l’application du Mentoré.

Part 2

Une languette apparaît juste en dessous du formulaire donnant la date de la Visio et le moyen d’y accéder avec pour titre => “Prochaine session“ et contient les éléments suivants :

- Une petite icône distinctif attribuée à une session à venir,     placée en haut à gauche de la languette.
- Le sous-titre => “Mentorat“ placé en haut à gauche     de la languette.
- La date et l’heure effective de la session programmée     précédemment et VALIDÈ placé sous le sous-titre “Mentorat“.
- Un Icon de poubelle permet de déprogrammer une session,     placée en haut à droite de la languette, sur la même ligne que la date et     l’heure de cette session que l’on souhaite supprimer. Si je clic cet Icon     poubelle une Modal s’ouvre me demandant de confirmer la suppression de     session.
- Un bouton me donnant l’accès à l’outil Visio=> "REJOINDRE     LA VISIO" apparaît après enregistrement d’une date de session.
- Un Icon caméra est juxtaposé au bouton "REJOINDRE     LA VISIO" pour marquer son rôle. 
- Un rappel de session est envoyé automatiquement par E-mail     envoyé 1 heure avant le début de chaque session, et une notification apparaît dans l’application.

Il n’est possible de programmer qu’une seule session et tant qu’elle n’est pas passée ou supprimée aucune programmation n’est possible, donc sous le titre “Prochaine session“ ne peut apparaître d’1 à 0 languette, afin de garder l’espace le plus simple et compréhensible possible.

Part 3

L’historique des sessions passé est conservé et apparaît en dessous :

·     Une icône distinctive avec un code couleur indique que c’est un historique de session.

- Le sous-titre     => “Mentorat“ placé en haut à gauche de la languette.
- La date et     l’heure effective de la session programmée précédemment et VALIDÈ placé     sous le sous-titre “Mentorat“.

·     Un chevron est placé à droite de la languette permettant l’accès aux informations conservées durant cette session passée.

·     Une icône distinctive avec un code couleur indique que c’est un historique de session qui a été avorté.

**[Gestion session Mentorat] Accéder aux sessions de Mentorat**

Description

En tant que Mentoré je souhaite accéder à mes sessions de Mentorat présente ou passé.

Sur la page mes sessions le Mentoré idem que pour le Mentor Part 2 (sans la possibilité d’annuler une session, il devra contacter son Mentor pour cela), et Part 3.

Part 2

Une languette apparaît juste en dessous du formulaire donnant la date de la Visio et le moyen d’y accéder avec pour titre => “Prochaine session“ et contient les éléments suivants :

- Une petite icône distinctif attribuée à une session à     venir, placée en haut à gauche de la languette.
- Le sous-titre => “Mentorat“ placé en haut à gauche     de la languette.
- La date et l’heure effective de la session programmée.
- Un bouton me donnant l’accès à l’outil Visio=> "REJOINDRE     LA VISIO" apparaît après enregistrement d’une date de session.
- Un Icon caméra est juxtaposé au bouton "REJOINDRE     LA VISIO" pour marquer son rôle. 

 

Part 3

L’historique des sessions passé est conservé et apparaît en dessous :

·     Une icône distinctive avec un code couleur indique que c’est un historique de session.

- Le sous-titre     => “Mentorat“ placé en haut à gauche de la languette.
- La date et     l’heure effective de la session programmée précédemment et VALIDÈ placé     sous le sous-titre “Mentorat“.

·     Un chevron est placé à droite de la languette permettant l’accès aux informations conservées durant cette session passée.

·     Une icône distinctive avec un code couleur indique que c’est un historique de session qui a été avorté.

**[Gestion session Mentorat] Outil Visio**

Description

En tant qu’utilisateur je veux pouvoir communiquer en Visio avec mon Mentor ou Mentoré à la date et l’heure des sessions programmés.

 

J’ai reçu 1 heure avant la session un E-mail m’indiquant que la session va commencer.

Je dispose 2 points d’accès à la Visio pour effectuer ma session programmée :

·     Sur ma page session dans la languette ayant pour titre => “Prochaine session“ je clique sur le bouton "REJOINDRE LA VISIO".

·     Un raccourci applicatif est placé en bas à droite de chaque écran me donne également accès à cette Visio.

A l’heure dite je me suis connecté à la session. 

·     Au centre de l’écran en grand apparaît mon interlocuteur

·     Sur le côté droit en plus petit mon image filmé par ma caméra apparaît

·     En bas d’écran différent boutons sont affichés :

\-     Activer / Désactiver le son.

\-     Activer / Désactiver la caméra.

\-     Activer / Désactiver l’enregistrement de la Visio.

\-     Activer / Désactiver le partage d’écran.

·     Raccrocher la Visio se fait en bas à droite de chaque écran une icône en forme de téléphone devient rouge en cours de communication et redevient blanc quand je raccroche la Visio.

·     Une fois que l’un des utilisateurs a cliqué sur raccrocher la Visio ils sont redirigés :

\-     Le Mentor est redirigé vers la page compte rendu de session.

\-     Le Mentoré est redirigé vers la page historique de la session.

**[Gestion prise de note] Outil chat**

Description

En tant qu’utilisateur je souhaite pouvoir envoyer et recevoir un message directement depuis l’application.

Sur chaque écran de l’application je dispose d’un raccourci pour lancer l’outil chat.

·     En bas à droite une icône de chat est placée à côté du raccourci de Visio, il devient rouge quand je l’ouvre et blanc quand je le ferme.

Une fois l’outil ouvert une slidebar venant de la gauche vers la droite apparaît et ce compose :

- Un onglet => “Chat“.

Un chat classique proche de celui de messager est constitué, les messages s’affichent dans une bulle ayant un code couleur pour chaque interlocuteur. Un champ texte et un bouton envoyer le message.

L’outil Chat peut s’activer à tout moment même en cours de Visio il passe par-dessus la fenêtre de Visio, on peut faire disparaître cette fenêtre par différent moyen : 

·     Par un Slide du doigt de gauche à droite.

·     En cliquant la croix en haut à droite de l’outil.

·     En cliquant l’icône Chat en bas de chaque écran.

L’historique des conversations est conservé dans l’outil.

**[Gestion prise de note] Outil Prise de note**

Description

En tant qu’utilisateur je souhaite pouvoir prendre des notes depuis l’application à tout moment.

·     En bas de chaque écran de l’application je dispose d’un raccourci pour lancer prise de note, il devient rouge quand je l’ouvre et blanc quand je le ferme.

Une fois l’outil ouvert une slidebar venant de la gauche vers la droite apparaît et ce compose :

- Un onglet => “Prise de Note“.

·     Un champ texte me permet de prendre des notes.

·     Un bouton avec une icône en forme de micro me permet de dicter du texte dans mon outil prise de note.

·     Un bouton avec une icône représentant un enregistrement me permet d’enregistrer ma note qui se fait via l’ouverture d’une Modal qui contient les éléments suivants :

- Un champs texte me permettant de donner un titre à ma note.
- Un champ de recherche d’étiquettes déjà existantes.
- Un bouton avec une icône poubelle pour supprimer la note, placée sur la même ligne que le champ de recherche sur la droite.
- L’affichage des étiquettes déjà créé avec le nom de l’étiquette et sa couleur choisie lors de sa création. 
- Un crayon permet d’éditer chaque étiquette pour changer son nom ou sa couleur.
- Un bouton me permet de créer une nouvelle étiquette qui sera ajoutée à celle déjà existante.
- Un bouton EXIT me permet d’abandonner la sauvegarde.
- Un bouton SAVE me permet d’enregistrer cette note. Le titre et le choix d’une étiquette sont requis pour que l’enregistrement soit possible sinon un message d’erreur apparaîtra.
- Le choix de l’étiquette se fait juste en appuyant sur une étiquette existante, un rond au couleur de l’étiquette choisie apparaît alors en haut à droite de la modal d’enregistrement.
- A noter que la modale ne peut pas afficher plus de 5 étiquettes en même temps on peut faire défiler les suivantes par un slide du doigt de bas vers le haut, un Spider (Barre de défilement) sera placé sur la droite de la Modal pour marquer qu’il est possible de le faire.

L’outil prise de note peut s’activer à tout moment même en cours de Visio il passe par-dessus la fenêtre de Visio, on peut faire disparaître cette fenêtre par différent moyen : 

·     Par un Slide du doigt de gauche à droite.

·     En cliquant la croix en haut à droite de l’outil.

·     En cliquant l’icône Chat en bas de chaque écran.

Si la Visio est enregistrée et qu’une note a été tapée pendant le cours de la Visio, son enregistrement apparaîtra en haut de la page historique de session automatiquement même si la note n’a pas fait l’objet d’un enregistrement manuel.

Si une note est enregistrée quel que soit le moment elle est accessible depuis le Burger menu en haut à gauche présent sur tous les pages de l’application, dans l’onglet mes notes.

**[Gestion Session Mentorat] Compte rendu de session**

Description

En tant que Mentor je veux établir un compte rendu de session et fixer les objectifs de la prochaine session.

A la fermeture d’une Vision (session de Mentorat) je suis redirigé automatiquement vers une page qui me permet d’établir un compte rendu de session, cette page contient 3 champs texte intitulés :

=> "1. Avancées de l’étudiant sur son projet depuis la dernière session"

=> "2. Principaux sujets abordés pendant la session"

=> "3. Objectifs fixés par l'étudiant et le mentor pour la prochaine session"

·     Un bouton => “ENREGISTRER” me permet d’enregistrer le compte rendu.

·     Un compte rendu enregistré sera visible dans l’historique de la session sous le 1er onglet => "Compte rendu ».

·     Un E-mail est envoyé au Mentoré lui affichant :

\-     Le compte rendu de session rédigé par son Mentor

\-     Un lien qui ouvre un formulaire permettant d’évaluer sa relation avec son Mentor

**[Gestion Session Mentorat] Accès historique de session**

Description

En tant qu’utilisateur je veux accéder à l’historique d’une session passée.

Sur la page mes sessions dans la section "Sessions passé" je clique sur le chevron d’une languette représentant une session passée une nouvelle page s’ouvre et contient des éléments sauvegardés de cette ancienne sessions rangées de cette façon :

·     En haut de la page s’affiche une vidéo si durant une Visio un enregistrement a été démarré.

·     Au milieu de l’écran 3 onglets me permettent de faire varier le contenu de la 2em moitié de l’écran en dessous.

-  1er onglet => "Compte rendu"

Si je clique cet onglet cela affiche en dessous le compte rendu de session fait par le Mentor comprenant : 

​      La date où a eu lieu la session.

   => "1. Avancées de l’étudiant sur son projet depuis la dernière session".

​    => "2. Principaux sujets abordés pendant la session".

​    => "3. Objectifs fixés par l'étudiant et le mentor pour la prochaine session"

- 2em onglet => "Prise de note"

Si je clique cet onglet cela affiche en dessous un outil de prise de note comprenant :

Un titre.

Un champ texte.

Une pastille de couleur représentant la couleur de l’étiquette choisit

Une icône en forme de crayon permettant de lancer l’édition du titre et du choix d’étiquette (voire user story Outil prise de note)

-  3em onglet => "Transcripte"

Si je clique sur cet onglet cela affiche en dessous un outil de prise de note comprenant un champs texte non éditable qui reproduit les voix de la vidéo en texte si un enregistrement vidéo à bien eu lieu durant cette Visio. Quand je fais avancer la vidéo, le texte défile en même temps. L’objectif de cet outil est de permettre au Mentoré de faire des copiés collés de certaines parties de ce texte vers son outil prise de note afin de lui faciliter sa prise de note.

Le Mentor à également accès à cet historique de session il a uniquement un droit de lecture il ne peut en aucun cas éditer les notes de son Mentoré.

**[Gestion Session Mentorat] Rappel automatique en cas de longue inactivité**

Description

En tant qu’utilisateur en cours de contrat de Mentorat, je souhaite recevoir un rappel en cas de trop longue attente entre chaque session.

·     Un email est envoyé automatiquement au Mentor et Mentoré pour leur rappeler qu’ils n’ont pas fait de session de Mentorat depuis plus de 2 semaines.

**[Gestion Communication] Envoyer un email**

Description 

En tant qu’utilisateur, je veux envoyer un email à mon Mentor ou Mentoré.

·     Depuis mon espace profile dans l’espace Mon Mentor / Mentoré, le champs E-mail est cliquable et lance automatique ma Boîte-mail avec comme adresse de destination mon Mentor ou Mentoré suivant le cas où on se trouve 

**[Notifications] Recevoir des notifications**

Description 

En tant qu’utilisateur, je veux recevoir des notifications dans le cas où mon Mentor ou Mentoré effectue certaines actions dans l’application.

·     Un bouton en forme de sonnette est situé en haut à droite de l'écran. 

·     Le nombre de nouvelles notifications est affichée sur le bouton en rouge et correspond aux actions effectuées par son Mentor ou Mentoré depuis : 

\-     Sa page sessions. 

\-     Historique n° de session.

\-     Envoie d’un E-mail.

·     Sur clic du bouton l'utilisateur peut consulter les notifications ce qui a pour effet d'effacer le statut "nouvelle notification"

·     Afficher une Modal listant les notifications.

**[Accès] Modification de son profil utilisateur 4/4**

Description

En tant qu'utilisateur, je veux pouvoir consulter mon contrat de Mentorat.

·     Sur la page profil je clique la 3em languette accordéon => “Mon contrat“, l’accordéon s’ouvre et affiche les informations éditables suivante :

\-     Compétence(s) Mentorée(s) -> Listes déroulantes multi section.

\-     Ma fréquence -> liste déroulante

\-     Date de début (ce champ n’est pas éditable)

\-     Date de fin (de mon contrat de Mentorat, non requis) => date-picker

\-     Arrêter mon contrat de mentorat -> bouton switch On / Off :

Si je change ce réglage une Modal s’ouvre pour demander confirmation.

·     L’édition des champs devient possible quand je clique sur un Icon ayant la forme d’un crayon placé à côté du titre “Mon profil Mentor/ Mentoré“.

**1.3 Métriques du projet** 

Pour l’établissement de métriques applicative nous préconisons le logiciel **SonarQube** qui permettra de vérifier la qualité du code produit par les développeurs impliqués dans la réalisation de notre application de Mentorat. Différents critères de code seront analysés. On pourra ainsi définir une note minimale pour certains critères et les intégrer au cahier des charges. Le client pourra ainsi vérifier que le travail produit respect des gages de qualités minimum définies au préalable. SonarQube supporte la quasi-totalité des langages de programmation. 

Les fonctionnalités de SonarQube fournissent des métriques sur la qualité du code :

·     Les duplications de code.

·     Respect des règles de programmation.

·     Détection de bug.

·     Analyse architecturale. 

·     Mesure le niveau de documentation.

·     Evaluation des tests unitaires.

\3. Solution proposée 


 **3.1 Diagrammes de conception technique**

Le Diagramme de Classes est très utilisé dans la planification d’un projet applicatif qui va utiliser un code orienté objet, il permet une représentation visuelle des classes à partir desquelles créer les objets.

 

![img](E:\ImagesTypora\clip_image002-16539223167421.jpg)

**3.2 Glossaire** 

*Le vocabulaire éventuel du domaine s'insère ici.* 

·     **Visiteur** : Personne non encore inscrite à l’application et désirant le faire.

·     **Mentor :** Personne inscrite dans l’application, responsable de transmettre son expérience à un mentoré dans l’application.

·     **Mentoré :** Personne inscrite dans l’application désirant améliorer ses compétences dans un domaine auprès de quelqu’un de plus expérimenté que lui dans un domaine que l’on nomme un Mentor.

·     **Utilisateur :** Personnes pouvant être tout aussi bien un Mentor qu’un Mentoré.

·     **Expériences :** Correspond à l’ensemble des compétences que l’on souhaite transmettre ou recevoir.

·     **Contrat :** Engagement qui oblige au respect de certaines règles entre un Mentor et son Mentoré.

·     **Session :** Communication programmée entre un Mentor et son Mentoré.

·     **Historique de session :** Communication ayant déjà eu lieu entre un Mentor et son Mentoré qui conserve des informations relatives à cet échange dans l’application.

·     **Visio :** Communication en Visioconférence entre un Mentor et son mentoré, faite pendant une session.

·     **Compte rendu de session :** Bilan écrit fait par le Mentor à l’issu d’une session à l’attention de son Mentoré, et qui traite de 3 thèmes principaux, les actions entreprises par son Mentoré depuis la dernière session, des thèmes abordés durant la session et définir les objectifs de la prochaine session.

·     **Transcripte :** Les voix d’une vidéo-conférence sont transcrites dans un fichier texte.

·     **Chat :** Outil de communication par voix textuelle intégré à l’application.

·     **Prise de notes :** Fichier texte écrit par le Mentoré. 

·     **Étiquettes :** S’apparente à des dossiers pour ranger les notes du Mentoré.

·     **Languettes :** Espace délimité par un titre et des informations.

·     **Sidebar :** Contenu applicatif qui entre et qui sort l’écran par action d’un utilisateur en passant par-dessus un contenu déjà présent à l’écran.

·     **Burger Menu :** Menu applicatif qui apparaît à l’écran par-dessus un contenu par pression sur un bouton.

·     **Modal :** Bloc informatif qui apparaît par-dessus un contenu présent à l’écran**.**

·     **Date-picker :** Permet à un utilisateur de sélectionner une date facilement

·     **Liste déroulante :** Liste sélectionnable qui apparaît par suite d’un clique utilisateur.

·     **Logout :** Déconnexion utilisateur.

·     **Administrateur :** Personnes chargé de la gestion applicative.

**3.3 Spécifications techniques**

*Expliquez les technologies et langages pouvant être utilisés comme solution.*

Le choix du langage de développement pour notre projet d’application de Mentorat sera basé sur différent critères :

\1.   La capacité du langage à s’adapter au Web.

\2.   Un temps de réponse optimal.

\3.   Suivant la complexité du langage, les temps en développement peuvent varier.

\4.   Bénéficier d’une large communauté qui utilise ce langage est aussi un atout majeur pour corriger les bugs.

\5.   Plus il y a de développeurs qui utilisent un langage ou une solution plus il devient facile de recruter.

\6.   La complexité d’un langage de programmation induit également des durées de montée en compétence variable.

\7.   Une pratique architecturale commune est également un plus pour l’avancée d’une équipe. 

\8.   Un langage mature et stable permet de trouver plus facilement des réponses à ces problèmes.

\9.   De nouveau Framework moderne qui facilitera le développement sera également un plus.

***Tableau comparatif des langages de programmation :\***

|                        | ***Java\*** | ***Python\*** | ***C#\*** | ***JS\*** | ***PHP\*** | ***Ruby\*** | ***Go\*** |      |
| ---------------------- | ----------- | ------------- | --------- | --------- | ---------- | ----------- | --------- | ---- |
| ***1 Adapté au web\*** | ✔️           | ✔️             | ✔️         | ✔️         | ✔️          | ⚠️           | ⚠️         |      |
| ***2 Performance\***   | ✔️           | ⚠️             | ✔️         | ✔️         | ✔️          | ⚠️           | ✔️         |      |
| ***3 Vitesse dév.\***  | ❌           | ✔️             | ❌         | ✔️         | ✔️          | ✔️           | ⚠️         |      |
| ***4 Ecosystème\***    | ✔️           | ⚠️             | ✔️         | ⚠️         | ✔️          | ✔️           | ⚠️         |      |
| ***5 Nombre de dév\*** | ✔️           | ❌             | ✔️         | ✔️         | ✔️          | ❌           | ❌         |      |
| ***6 Difficulté\***    | ⚠️           | ✔️             | ⚠️         | ⚠️         | ✔️          | ✔️           | ⚠️         |      |
| ***7 Consistance\***   | ✔️           | ✔️             | ✔️         | ❌         | ❌          | ✔️           | ✔️         |      |
| ***8 Maturité\***      | ✔️           | ✔️             | ✔️         | ⚠️         | ✔️          | ✔️           | ⚠️         |      |
| ***9 Tendance\***      | ✔️           | ✔️             | ⚠️         | ✔️         | ⚠️          | ❌           | ⚠️         |      |
|                        |             |               |           |           |            |             |           |      |

D’après ce tableau comparatif Java et PHP se détachent et présentent plus d’avantage que les autres langages. Nous retiendrons le langage Java pour développer le backend de notre application de mentorat car il est plus tendance que le langage PHP et dispose davantage d’uniformité dans la façon d’utiliser les outils : 

·     Java est très tendance dans les grandes entreprises principalement utilisé pour leur backend applicatif car Java dispose d’excellente performance pour les gros projets.

·     Java dispose d’une très grande maturité avec de nombreuses librairies, et beaucoup d’aide en ligne qui faciliteront la tâche des développeurs. Java est très répandu pour le développement web (J2EE) mais aussi pour le développement pour mobile sur Android.

·     Java a un écosystème très important comme le Framework Spring qui facilite grandement le développement et qui est déjà très mature. Nous utiliserons donc Java Spring pour le développement Backend de notre application.

Bien que nous ne soyons qu’en phase de création d’un POC (proof of concept) nous ferons le choix d’utiliser Java en Backend car l’équipe de développeurs a une bonne expertise de ce langage de programmation et cela nous fera gagner beaucoup de temps par la suite si le projet venait à évoluer.

**3.4 Wireframes** 

*Mettez les images des wireframes ici.* 

 

![img](E:\ImagesTypora\clip_image004-16539223167432.jpg)

​          ![img](E:\ImagesTypora\clip_image006.jpg)

![Une image contenant texte  Description générée automatiquement](E:\ImagesTypora\clip_image008.jpg)

​          ![img](E:\ImagesTypora\clip_image010.jpg) ![Une image contenant texte  Description générée automatiquement](E:\ImagesTypora\clip_image012.jpg)

![img](E:\ImagesTypora\clip_image014.jpg)

 

![img](E:\ImagesTypora\clip_image016.jpg)

 

 

 

 

![Une image contenant texte  Description générée automatiquement](E:\ImagesTypora\clip_image018.jpg)

 

![Une image contenant texte  Description générée automatiquement](E:\ImagesTypora\clip_image020.jpg)

 

![img](E:\ImagesTypora\clip_image022.jpg)

![Une image contenant texte, capture d’écran, parking, machine  Description générée automatiquement](E:\ImagesTypora\clip_image024.jpg)

![Une image contenant texte  Description générée automatiquement](E:\ImagesTypora\clip_image026.jpg)

![Une image contenant texte, capture d’écran, parking, machine  Description générée automatiquement](E:\ImagesTypora\clip_image028.jpg)

 

 

![Une image contenant texte  Description générée automatiquement](E:\ImagesTypora\clip_image030.jpg)

 

 