This demo creates some pods in a namespace.

To run this demo:
* Make sure you're using the right context (probably `docker-desktop`)
    * `kubectx docker-desktop` to switch
* Create a namespace for this demo: `kubectl create namespace demo-01`
* Make the demo-01 namespace the default: `kubens demo-01`
* Take a look at `pod.yaml` and all the comments within to understand more about pods
* Create the pod defined in `pod.yaml`: `kubectl apply -f pod.yaml`
