Ma démarche:
J'ai commencé à faire mon html en premier, puis ensuite j'ai fais mon css. De temps en temps il arrive que je dois corriger 
des erreurs dans mon html avant de continuer à finir mon css.

Mes choix tecniques:
J'ai donné des classes à presque tout les balises html (normenclature BEM). Aussi, j'ai joué beaucoup avec le << display: flex >> 
dans le css, surtout pour les classes << card >>.

Les défis rencontrés:
J'avais beaucoup de misère avec le << display: flex >> et la dimension des images. Ça ne fonctionnait pas toujours comme je
voulais.

Section sur l'utilisation de l'IA:
- Google gemini
- Version Gemini 3 Flash
- Dates: 2026-03-21 et 2026-03-22
- Prompt utilisé: 
"Tu peux m'aider pour la navbar?", "Indique moi les erreurs dans mon code pour que mon site ressmeble à la maquette", "J'ai de la misère a ajuster mes cards comme je veux dans la section "Témoignage". Au début mon code marchait, mais aussitôt que j'ai un peut modifié le text dans les cards, les cards se place vers la gauche de ma page et pourtant j'était sur et certain de ne pas avoir touché mes class dans mon html", "Pourrais-tu m'aider à corriger des erreurs dans mon code html et/ou css pour que mon site ressemble à la maquette"
- Parties du code validée / améliorée avec l'IA: 
    html: nav (header), body, footer
    css: classes card (et tout les autres classes avec card dans le nom), navbar (et tout les autres classes avec navbar dans le nom), acceuil (et tout les autres classes avec acceuil dans le nom), footer__btn

Système de tokens (variable):
    /*Palette de couleurs*/
    --color-primary: #6A994E;
    --color-secondary: #A7C957;
    --color-accent: #386641;
    --color-bg: #F2E8CF;
    --color-dark-bg: #386641;
    --color-black-bg: #000000e0;
    --color-surface: #FFFFFF;
    --color-text: #1A2E1A;
    --color-text-lighter: #386641;
    --color-text-over-dark-bg: #FFFFFF;
    --color-text-hover: #FBEC5D;
    --color-transparent: #00000000;
    /*Espacements*/
    --space-1: 4px;
    --space-2: 8px;
    --space-4: 16px;
    --space-6: 24px;
    --space-8: 32px;
    /*Typographie*/
    --font-size-sm: 14px;
    --font-size-base: 16px;
    --font-size-lg: 20px;
    --font-size-xl: 24px;
    /*Bordures*/
    --radius-sm: 4px;
    --radius-md: 8px;
    --radius-lg: 16px;