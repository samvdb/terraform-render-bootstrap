Custom tweaks from original project:


# resources/static-manifests/kube-apiserver.yaml

Changed flag to true to support anonymous healthchecks for haproxy.
    - --anonymous-auth=true