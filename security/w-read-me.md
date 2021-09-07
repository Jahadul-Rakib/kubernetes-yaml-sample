## RBAC (Role Based Access Control)

* **Role - it is a permission on to a specific namespace.**
* **ClusterRole - its permission for access to whole cluster.**

* **Role Binding - Its bind role with a user.**
* **_RoleBinding_ bind the role with _user_ or _group_ or _service-account_.**

## All API Groups:

* **apps. (All except the list of deployment)**
* **extensions. (list deployments)**
* ##### star mark(*) define all apiGroups.

## All Resources:

* **pod**.
* **service**.
* **daemonset**.
* **deployment**.
* **replicaset**.
* **statefulset**.
* **namespace**
* **secret**
* **configmap**
* **persistentvolume**
* **persistentvolumeclaim**
* **storageclass**
* **job**.
* **cronjobs**.

## All Verbs;

* **create**
* **delete**
* **deletecollection**
* **get**
* **list**
* **patch**
* **update**
* **watch**
* **edit**
* **exec**