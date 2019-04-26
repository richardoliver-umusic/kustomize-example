# Kustomize example for rws kubenetes env management

Kustomize configurations are deployed using e.g. `kubectl apply -k ./overlay/dev`

- dev overlay would be used for local testing
- octopus overlay is used by octopus (first transform files to add in octopus configs, then applyed to cluster)
