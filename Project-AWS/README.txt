!!!!!!!!ATTENTION!!!!!!!!

Les ACCESS_KEY et SECRET_KEY de votre compte AWS sont � saisir dans les variables d�clar�es
La Key pair est �galement � cr�er et � renseigner dans les variables d�clar�es.

!!!!!!!!!!!!!!!!!!!!!!!!!


1. rendez-vous d'abord dans le dossier "Pre-Configuration"
2. lancez l'�xecution du code avec Terraform, le VPC, les Subnets, le stockage EFS et les groupes de s�curit� seront cr��s.
3. Rendez-vous dans le dossier "Instance0_installation"
4. Lancez l'�xecution du code avec Terraform, l'instance originale sera cr��e, les fichiers WordPress seront install�s sur le stockage EFS (lui-m�me mont� sur /var/www/html)
5. ALlez ensuite dans le dossier "HAConfiguration" et lancez l'�xecution du code. Une Launch Configuration, un groupe AUto-Scaling ainsi qu'un ELB seront cr��s.
6. Lancez l'installation de Wordpress en vous connectant directement en http � l'adresse DNS de l'ELB (environs 2 minutes)
7. l'application est maintenant op�rationnelle