This demo creates a simple replica set.

To run this demo:
* Make sure you're using the right context (probably `docker-desktop`)
    * `kubectx docker-desktop` to switch
* Create a namespace for this demo: `kubectl create namespace demo-02`
* Make the demo-02 namespace the default: `kubens demo-02`
* Create the replica set defined in `replica-set.yaml`: `kubectl apply -f replica-set.yaml`
