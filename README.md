# cydia-repo-codes
Códigos para tu repositorio de Cydia


# Detector de V. iOS
Simple Codigo para implementar en las páginas de tus tweaks osea en los Depictions con el cual podras mostrar la versión de iOS que usa tu dispositivo al visitar algun tweak de tu repo.

<?php
///Detector iOS by @JorgeMoralesMV

//iOS 7

if (strstr($_SERVER['HTTP_USER_AGENT'], 'OS 7_0')) { echo "iOS 7.0"; }

elseif (strstr($_SERVER['HTTP_USER_AGENT'], 'OS 7_0_1')) { echo "iOS 7.0.1"; }

elseif (strstr($_SERVER['HTTP_USER_AGENT'], 'OS 7_0_2')) { echo "iOS 7.0.2"; }

elseif (strstr($_SERVER['HTTP_USER_AGENT'], 'OS 7_0_3')) { echo "iOS 7.0.3"; }

elseif (strstr($_SERVER['HTTP_USER_AGENT'], 'OS 7_0_4')) { echo "iOS 7.0.4"; }

elseif (strstr($_SERVER['HTTP_USER_AGENT'], 'OS 7_0_5')) { echo "iOS 7.0.5"; }

elseif (strstr($_SERVER['HTTP_USER_AGENT'], 'OS 7_0_6')) { echo "iOS 7.0.6"; }

//iOS 8

elseif (strstr($_SERVER['HTTP_USER_AGENT'], 'OS 8_0')) { echo "iOS 8.0"; }

elseif (strstr($_SERVER['HTTP_USER_AGENT'], 'OS 8_0_1')) { echo "iOS 8.0.1"; }

elseif (strstr($_SERVER['HTTP_USER_AGENT'], 'OS 8_0_2')) { echo "iOS 8.0.2"; }

elseif (strstr($_SERVER['HTTP_USER_AGENT'], 'OS 8_1')) { echo "iOS 8.1"; }

elseif (strstr($_SERVER['HTTP_USER_AGENT'], 'OS 8_1_1')) { echo "iOS 8.1.1"; }

elseif (strstr($_SERVER['HTTP_USER_AGENT'], 'OS 8_1_2')) { echo "iOS 8.1.2"; }

else {

echo "N/A";

}

?>
