

**Mesure de Distance des Mains avec OpenCV et Mediapipe**

Ce programme utilise OpenCV et Mediapipe pour détecter les mains dans un flux vidéo en direct à partir de la caméra par défaut de l'ordinateur. Il calcule ensuite la distance entre deux points spécifiques de la main détectée et affiche cette distance à l'écran.

**Installation**

Assurez-vous d'avoir Python installé sur votre système. Vous pouvez installer les dépendances requises en exécutant la commande suivante :

```bash
pip install opencv-python mediapipe
```

**Utilisation**

1. Exécutez le script `mesure_distance_main.py`.
2. Placez vos mains devant la caméra.
3. Les points caractéristiques de vos mains seront détectés et une boîte englobante ainsi que les distances correspondantes seront affichées à l'écran.

**Contrôles**

- Appuyez sur la touche 'q' pour quitter le programme.

**Remarque**

Pour obtenir des résultats précis, assurez-vous d'avoir un bon éclairage et que vos mains soient clairement visibles par la caméra.

