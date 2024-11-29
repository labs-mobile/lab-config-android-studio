### Optimisation d'Android Studio : Désactivation des fonctionnalités inutiles

Pour améliorer les performances d'Android Studio, il est conseillé de désactiver les fonctionnalités non essentielles, telles que les plugins inutilisés et certaines options gourmandes en ressources. Voici les étapes détaillées :

---

#### **1. Désactiver les plugins inutiles**
Les plugins activés par défaut peuvent consommer des ressources importantes, même si vous ne les utilisez pas.

- **Étapes :**
  1. Allez dans **File > Settings > Plugins**.
  2. Recherchez les plugins que vous n'utilisez pas (par exemple, ceux liés à des fonctionnalités ou langages non nécessaires à votre projet).
  3. Décochez ou désinstallez les plugins inutiles.
     - **Exemple :** Si vous ne développez pas avec Flutter, désactivez les plugins Flutter/Dart.
  4. Cliquez sur **Apply** et redémarrez Android Studio.

- **Remarque :** Veillez à ne pas désactiver les plugins essentiels comme Gradle ou ceux liés au support Android.

---

#### **2. Activer le mode *Power Save***
Le mode *Power Save* désactive certaines fonctionnalités comme l'analyse du code en temps réel et les inspections automatiques, réduisant ainsi la consommation de ressources.

- **Étapes :**
  1. Dans Android Studio, allez dans **File > Power Save Mode**.
  2. Activez cette option en la cochant.
  3. Vous pouvez également désactiver ce mode temporairement si vous avez besoin d'inspections de code pour résoudre des erreurs critiques.

- **Quand utiliser le mode Power Save ?**
  - Lorsqu'Android Studio devient lent.
  - Pendant les phases où vous n'avez pas besoin d'un retour immédiat sur le code, comme lors de la rédaction de blocs importants ou de tests unitaires.

---

### Avantages de ces optimisations
- **Désactivation des plugins :** Moins de mémoire et de CPU consommés, ce qui améliore la fluidité globale.
- **Mode Power Save :** Libération de ressources pour d'autres processus, comme la compilation ou les émulateurs.

Ces ajustements sont particulièrement utiles si votre machine a des ressources limitées (moins de 8 Go de RAM ou un processeur ancien). Si vous souhaitez d'autres recommandations ou des astuces avancées, faites-le-moi savoir !