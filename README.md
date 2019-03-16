# **MODAL PDF :**
*Permet de creer une modal qui aura la fonction de lire un PDF*

* [**DEMO**](https://sophikitis.github.io/ModalPdf/example.html)


## REQUIS :
- bootstrap css
- le css du modal

```
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-alpha.3/css/bootstrap.min.css" integrity="sha384-MIwDKRSSImVFAZCVLtU0LMDdON6KVCrZHyVQQj6e8wIEJkW4tvwqXrbMIya1vriY" crossorigin="anonymous" />
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.5.0/css/font-awesome.min.css" />
<link rel="stylesheet" href="assets/css/modal.css">

```

- bootstrap js
- jQuery 3.0.0
- modalpdf.js

```
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.0.0/jquery.min.js" integrity="sha384-THPy051/pYDQGanwU6poAc/hOdQxjnOEXzbT+OuUAFqNqFjL+4IGLBgCJC3ZOShY" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/tether/1.2.0/js/tether.min.js" integrity="sha384-Plbmg8JY28KFelvJVai01l8WyZzrYWG825m+cZ0eDDS1f7d/js6ikvy1+X+guPIB" crossorigin="anonymous"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-alpha.3/js/bootstrap.min.js" integrity="sha384-ux8v3A6CPtOTqOzMKiuo3d/DomGaaClxFYdCu2HPMBEkf6x2xiDyJ7gkXU0MWwaD" crossorigin="anonymous"></script>
<script type="text/javascript" src="assets/js/modalpdf.js"></script>

```

## UTILISATION :
- créer une balise avec la class voir-pdf
- ajouter en parametre title a qui on indique le titre de notre modal
- ajouter un href qui sera la localisation du PDF

```
<div class="btn btn-primary modal-pdf">
    <a class="voir-pdf" title="Lecture d'un pdf dans une modal" href="unpdf.pdf" style="color:white;">
      Voir un le pdf
    </a>
</div>

```
