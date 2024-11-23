# AccessGranted

J’ai imaginé un projet que j’ai nommé « AccessGranted » pour une société du type PME et qui porte le même nom.
AccessGranted permet un accès sécurisé et exclusif aux parkings des résidents d’immeubles.

Il n'est pas possible de programmer une télécommande universelle pour ouvrir les portails.
Toute la gestion se situe sur AWS mais les portails n'ont pas besoin d'être connectés à Internet pour s'ouvrir à la bonne télécommande.

Pour pouvoir établir un cadre bien architecturé qui répond aux besoin du client (imaginé), je me suis basée prioritairement sur les piliers Security et Reliability.

Les services serverless d’AWS y ont été privilégiés, ainsi réduisant les coûts opérationnels et optimisant les frais de maintenance.

L’architecture reste valide en cas d’expansion du business.
