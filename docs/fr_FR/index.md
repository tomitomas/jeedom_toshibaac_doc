# Plugin Toshiba AC Control


Ce plugin permet de gérer vos climatiseurs Toshiba, connectés via un Adaptateur Wi-Fi (`RB-101S-G`, `RB-102S-G`, ...).  

<img src="..\img\widget_brut.png" width="30%" />

<br/><br/>

# Configuration du Plugin

La configuration des équipements Toshiba AC est accessible à partir du menu `Plugins`, sous la catégorie `Confort`, et se fait en 3 étapes :  
1. installez les dépendances  
2. indiquez le nom d'utilisateur et le mot de passe que vous avez paramétré sur votre application Toshiba. Il est recommandé de ne pas modifier le port par défaut. 
3. démarrez le démon ! 

Si tout est vert, alors tout va bien ! :)  
  
<img src="..\img\settings_page.png" width="50%" />    
<br/><br/>


# Ajout des Climatiseurs

Les climatiseurs doivent être ajoutés sur votre compte Toshiba, depuis l'application Toshiba dédiée.  
Le plugin récupère les appareils déjà enregistrés sur l'application et créé les équipements correspondant sur Jeedom.  

Pour se faire, il vous suffit de cliquer sur le bouton `Scan` sur la page principale du plugin.     
<br/>
<img src="..\img\main_page.png" width="50%" />  

<br/>
Les équipements seront automatiquement remontés :    

<br/>
<img src="..\img\clim_added.png" width="30%" />  

<br/><br/>
