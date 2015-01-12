# cydia-repo-codes
Códigos para tu repositorio de Cydia


# Detector de V. iOS
Simple Codigo para implementar en las páginas de tus tweaks osea en los Depictions con el cual podras mostrar la versión de iOS que usa tu dispositivo al visitar algun tweak de tu repo.


if (strstr($_SERVER['HTTP_USER_AGENT'], 'OS 7_0')) { echo "iOS 7.0"; }

elseif (strstr($_SERVER['HTTP_USER_AGENT'], 'OS 8_0')) { echo "iOS 8.0"; }
