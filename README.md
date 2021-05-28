# k8s-workshop-exercices

  This Repository contain exercise to follow the workshop about kubernetes fundamentals.
  
## Exercises

 - All exercises have the same statement "I have a POD and I would like in logs a specific phrase"
 - If you are solving the simple-pod exercices folder you´ll need to do the follow things:

         * Open simple-pod.yml file
         * Add the name simple-pod-<your-name> to deploy this pod
         * Add the correct namespace to deploy this POD
         * Deploy POD in your kubernetes cluster
         * See the Pod logs and memorize the phrase
         * Open file simple-pod-enviroment.yml
         * Change the name of POD and change nameSpace to correct namespace to deploy.
         * Deploy POD and show error in log.
         * Add env variables until pod show to you the same phrase that you memorized.

- If you are solving the config-map exercises folder you´ll need to do the follow things.

         * Remember the phrase of simple-pod
         * Open file config-map-names.yml and change the namespace and name of configmap
         * Store this configmap in kubernetes
         * Open file simple-pod-configmap.yml and change the name of pod and put correct namespace
         * Change the configmap reference to use the configmap stored (you could change the las of name where you see <your-name> put your name the start of reference is not modificable)
         * Deploy POD describe in simple-pod-configmap.yml and show logs
         * Modify simple-pod-configmap.yml to add prperties if is necesary and store it.
         * Create new configmap with reference configmap-time-<your-name>
         * Add SURNAME key in  simple-pod-configmap.yml
         * Deploy POD until you can see the memorized phrase in Log
   
- If you are solving secrets exercises folder you´ll need to do the follow things:

         * Open file simple-pod-secrets.yml
         * Create an env variable into a POD with key TIME_TO_COMPLETED and value 3600
         * Create a configmap file with keys NAME and SURNAME
         * Create a secret file with key SECRET
         * Store in Kubernetes this files
         * Modify simple-pod-secrets.yml to use the secret file and configmap
         * Deploy simple-pod-secrets.yml and show logs.
         * Execute the process until you can see in the logs the phrase that you memorized.
         

