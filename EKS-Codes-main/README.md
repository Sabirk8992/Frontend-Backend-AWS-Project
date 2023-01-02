### 

Now run below command to deploy your WordPress App with MySQL as a backend to store the database.
``kubectl create -k .``

Just by running a single command given above, Our WordPress App is launched. Also, Load balancers are launched to auto-scale the nodes which are launched using EKS. Run below command to check the running pods.

``kubectl get all``


