# Social Actors of Life (SAL)


Ce site web relate la vie et les nouveautés au courant des plus populaires <br>
acteurs du monde tels que Bradd Pitt, Mark Zuckerberg, Edward Snowden...

Il devra comporter une entité Acteurs : 
* Nom
* Prénom
* Fonctionnalité au départ (FTS)
* Fonctionnalité à l'arrivé (FTE)
* Revenus de leurs boulot (RLB)
* Poste actuelle (PA)
* Métiers
    * Si acteurs :
        * Revenus films (RF)
        * Nombre de Vue (NV)
        * Producteur du film (PF)
        * Bande Annonce (BA)
        * Réalisateur du Film (RF)
    * Sinon : 
        * Nom de la boite créer (NBC)
        * Type de société (TDS)
        * Chiffres d'affaire mensuel (CAM)
        * Chiffres d'affaire annuel (CAA)
        * École étudié (EE)

## __Fonctionnalités première du site web :__

* Mettre en avant les utilisateurs lambdas.

* Faire une page dédié aux commentaires liés aux films mis en avant ou non <br>
  Avis possible : " bon ou pas bon " et si pas bon dire pourquoi dire en quoi ce <br>
  film est pas bon.
## __Relations premières du site web__
__Relations Entity Actors et Metier / Actors et Films :__
* Actors et Metier
    * oneToOne
        * Nom de la boite créer (NBC)
        * Type de société (TDS)
        * Chiffres d'affaire mensuel (CAM)
        * Chiffres d'affaire annuel (CAA)
        * École étudié (EE)
* Actors et Films
    * oneToMany
        * Revenus films (RF)
        * Nombre de Vue (NV)
        * Producteur du film (PF)
            * oneToOne
                * Producteurs
        * Bande Annonce (BA)
        * Réalisateur du Film (RF)
