FORMATION 'WEB DEVELOPPEUR JUNIOR' OPENCLASSROOMS

PROJET 3 "Concevez une carte interactive de location de vélos"

Programmation en JS / JQuery entièrement en POO

API Mapbox / API Openstreetmap / API Web Storage

Utilisation Canvas, compatibilité tactile sur smartphone et tablette

Slider automatique et contrôlable en POO

ENONCE

DIAPORAMA

La page d’accueil de l’application affichera un diaporama de photos et de textes expliquant le fonctionnement de l'application. Ce diaporama réagit également au clavier avec les touches gauche et droite pour reculer et avancer manuellement.

CARTE DES VELOS

En-dessous du diaporama se trouve une carte exploitant l'API Mapbox avec la localisation de toutes les stations de vélos, positionnées à l’aide de marqueurs. Un clic sur un marqueur affiche l’état de la station dans un panneau construit en HTML et CSS à côté de la carte. La localisation et l'état de chaque station (ouverte, en travaux, combien de vélos et de places sont disponibles, etc.) est fourni via une API Openstreetmap. Les données doivent provenir de cette API.

RESERVATION DES VELOS

Il doit être possible de réserver un vélo disponible à la station sélectionnée en signant dans un champ libre implémenté à l’aide de l’API HTML5 Canvas. Une fois la signature validée, un vélo est marqué comme réservé à cette station. Pour ce projet, la réservation n'aura en réalité aucun effet. Seul le navigateur du navigateur "retiendra" que le vélo a été réservé. Les données de réservation seront stockées dans le navigateur à l’aide de l’API HTML5 Web Storage et affichées dans un pied de page en-dessous du panneau. La réservation expire automatiquement au bout de 20 minutes et également lorsque le navigateur web se referme. Le pied de page affiche en permanence l’état de la réservation (s’il y en a une), avec un décompte dynamique du temps restant avant expiration de la réservation. Il ne peut y avoir qu'une réservation à la fois. Si une nouvelle réservation a lieu, elle remplace la précédente.

CONTRAINTES TECHNIQUES

Utilisation de la bibliothèque jQuery mais pas de plugins jQuery. Le diaporama doit donc être développé en entier. Le code JavaScript doit entièrement être conçu en programmation orientée objet. Le code doit exploiter les API. Il doit également utiliser les API Web Storage et Canvas.

COMPETENCES A VALIDER

Programmer en Javascript

Interagir avec la page
