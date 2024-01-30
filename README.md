### pizzaiojo
## pizzaiojo
# pizzaiojo

Le projet concerne l'historique des ventes d'une pizzeria qui vont nous permettre d'apporter des réponses basés sur des statistiques de vente à son propriétaire.
On considère qu'il y a une erreur dans l'énnoncé et que la pizzeria est bien ouverte du lundi au vendredi dans la mesure ou des ventes semblables aux autres jours sont enregistrés ce jour là.
J'ai déterminé qu'il était préférable de modifier le dataset pour faciliter les calculs qui ne prennent pas en compte l'intégralité des pizzas à cause de la colonne pizza, j'ai donc supprimé la colonne quantity et l'ait transposé sous la forme de nouvelles rows tout en pouvant retracer la quantité et l'identifiant qui permettrait de faire l'opération inverse en cas de besoin.
A noter que même sur la version originale de l'énoncé sur Kaggle, le Data Analyst qui l'a conçu s'est trompé sur certaines de ces questions ou il faut groupby par order ou autre. On peut en être sûr en vérifiant le nombre de commandes totales du dataset et en faisant une vérification du nombre de données présentes dans les df de réponses aux problématiques.
