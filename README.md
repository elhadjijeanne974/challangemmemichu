# challangemmemichu
Mission : on doit depanner le PC de Madame Michu

# 1) Part 1 :Reparer le demarrage de Windows : 
On constate un probleme au demarrage "bootmgr" , je prepare mon iso et je le met dans mon Lecteur Optique: 

<img width="500" height="300" alt="Capture d'écran 2025-10-23 193935" src="https://github.com/user-attachments/assets/3f55f750-48ba-422e-8a6a-c4c10ab92267" />

je boot la machine en mode reparation grace au l'image windows 10 :


<img width="500" height="300" alt="mmm 4" src="https://github.com/user-attachments/assets/4b9e2214-4927-4385-bf89-b47befa839f8" />

Je lance une invite de commande:

<img width="500" height="300" alt="Capture d'écran 2025-10-23 150552" src="https://github.com/user-attachments/assets/1c08f2e9-a2fa-4593-a481-e0de245f6986" />


<img width="500" height="300" alt="madame michu 2 " src="https://github.com/user-attachments/assets/fd8cbf79-207c-4d64-8324-a2634155eed0" />

j ai un peu galeré a trouvé l emplacement avec DISKPART mais cette commande à fonctionné :

bootrec /fixmbr

bcdboot E:\Windows

bootrec /rebuildbcd

On relance windows 10 : 

<img width="500" height="300" alt="madame michu 4" src="https://github.com/user-attachments/assets/2f13aa79-e52a-4665-bed6-3c3c9c72cc1f" />

oups ! probleme avec winload : 
facilement reglé avec l outils de redemarge windows 

<img width="500" height="300" alt="Capture d'écran 2025-10-23 150833" src="https://github.com/user-attachments/assets/324414f9-d516-4f0b-a540-a034ccf29f6c" />

<img width="500" height="300" alt="MM 11" src="https://github.com/user-attachments/assets/55845eae-c4dd-4c84-9999-61b486a5af9f" />

L'ordinateur de Madame Michu à l air de fonctionner ... sauf que 

# Part 2: Restaurer les performances normales de la machine, verifier l état des disques , retrouver des images perdues :

*Quelque chose d'étrange se lance au demarrage 
*Madame Michu me lance un SOS via une note laissée dans les fichiers 

j ai du retrouver l emplacement du fichier qui se lancait au demarrage pour l'effacer de partout où je peux le fichiers s'apellait  " ping "
ça va mieux : 

<img width="500" height="300" alt="Pocesseur " src="https://github.com/user-attachments/assets/d659a8db-9601-45ce-9f6b-e835e4d61504" />











