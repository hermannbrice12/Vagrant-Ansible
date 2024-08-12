Ce Vagrantfile configure trois machines virtuelles avec AlmaLinux 8 et le déploie sur vmware:

Un nœud master Kubernetes.
Un nœud worker Kubernetes.
Un serveur Ansible.
Chaque machine a un utilisateur ansible avec des privilèges sudo et une configuration SSH adaptée pour les opérations de gestion et de provisionnement automatisées. 
Le serveur Ansible est configuré pour pouvoir se connecter aux nœuds master et worker sans mot de passe, facilitant ainsi les tâches d'automatisation et de gestion via Ansible.


