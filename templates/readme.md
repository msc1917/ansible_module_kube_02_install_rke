# Basis-Ansible-Konfiguration fuer Baikonur-Netzwerk
Rollen-Definitionen zum Einrichten des Heimnetzwerkes

## Rolle "kube_01_kubernetes_install"
Einrichten des Kubernetes-Clusters (master und node) via k3s, rke, kubeadm oder minikube

## Verzeichnis "templates"
Jinja2-Templates, welche von der Rolle benötigt werden könnten

## Templates:
* **engine_k3s/k3s.service.master.j2:**
* **engine_k3s/k3s.service.node.j2:**
* **engine_rke/cluster.bak.yml.j2:**
* **engine_rke/cluster.yml.j2:**
