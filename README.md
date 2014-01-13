SFSBClusteringDemo
==================

Jboss as supporte le clustering des EJB Session Beans, de sorte que les demandes des bean soit équilibrées à travers 
le cluster. Dans le cas d’un Stateful Session Bean, une copie de backup de l’état du bean est maintenue par un ou 
plusieurs nœuds pour assurer la haute disponibilité dans le cas où le nœud qui est entrain de gérer une session en 
particulier crashe ou s’arrête. Cet exemple met en œuvre le clustering à travers un exemple de Stateful Session Bean. 
