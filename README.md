# virtualisation-container-et-vrf

## Comment fonctionne la virtualisation
La virtualisation  est un processus par lequel un logiciel est utilisé pour créer une couche d'abstraction sur le matériel informatique qui permet aux éléments matériels d'un seul ordinateur d'être divisés en plusieurs ordinateurs virtuels.

Le logiciel utilisé s'appelle un  hyperviseur  - une petite couche qui permet à plusieurs systèmes d'exploitation de fonctionner côte à côte, en partageant les mêmes ressources informatiques physiques. Lorsqu'un hyperviseur est utilisé sur un ordinateur physique ou un serveur (également appelé serveur bare metal) dans un  centre de données , il permet à l'ordinateur physique de séparer son système d'exploitation et ses applications de son matériel. Ensuite, il peut se diviser en plusieurs « machines virtuelles » indépendantes.

## Notion de VRF (Virtual Routing and Forwarding)

est une technologie qui permet d'avoir plus d'une table de routage sur un même routeur. Le concept des VRF sur les routeurs est similaire aux VLAN sur les commutateurs.
Les VRF ont été initialement introduits en combinaison avec MPLS (Multiprotocol Label Switching), mais la VRF s'est avéré si utile qu'il a évolué pour devenir indépendant de MPLS. C'est l'explication historique du terme VRF Lite: utilisation de VRF sans MPLS

Étant donné que les instances de routage sont indépendantes, les adresses IP identiques ou qui se chevauchent peuvent être utilisées sans conflit les unes avec les autres. La fonctionnalité réseau est améliorée car des réseaux IP peuvent être segmentés sans nécessiter plusieurs routeurs.

![image](https://user-images.githubusercontent.com/83721477/177103154-4cf1ec90-7012-4b7b-b658-207752724743.png)

### VRF Lite

![image](https://user-images.githubusercontent.com/83721477/177104283-903289fd-cecb-4f37-b2e9-a263b81625ab.png)

