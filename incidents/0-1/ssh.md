Erreur 22 SSH sur files01. Impossible de se connecter depuis la machine Windows mais ping fonctionnel. 
Apres verification du service SSH sur la machine cible (files01), celui-ci etait desactive et ne serait pas relancer au demarrage.

Il a fallu relancer le service et l'activer au redemarrage avec systemctl start et systemctl enable
