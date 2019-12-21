# cmrSlide.js 

  -  ajouter la class slideContainer a une Balise 
  -  ajouter la class slider a une div contenant vos images

  - exemple :
  
        <div class="slideContainer">
          <div class="slider">
            <div><img class="" src="img/image1.jpg" alt="image1"></div>
            <div><img class="" src="img/image2.jpg" alt="image2"></div>
            <div><img class="" src="img/image3.jpg" alt="image3"></div>
          </div>
        </div>

# secureForm.js

 -  charger bootstrap4
 -  ajouter la class
   * secureName = pour les champs de type nom prenom
   * mailSecure = pour les champs de tpe mail
   * passSecure pour les champs de type password
   * ageSecure = pour verifier si l'utilisateur est mineur

# slideContent.js


 -  au chargement du DOM appeler la fonction
  * slideContent("selecteur css", position de depart, delay d'execution, delay de transition)
  * exemples : slideContent("header",2000,500,2);
