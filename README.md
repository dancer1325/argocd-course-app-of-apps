# How to structure ArgoCD's application definitions?
* Manual `kubectl`
* App of apps pattern
    * The goal of this repo
    * Ways to structure it?
        * root ArgoCD application / track directory of ArgoCD applications
            * Other ArgoCD applications as subdirectories of that directory
        * root ArgoCD application / track helm chart with ArgoCD applications
* How to run / execute?
    * `kubectl apply -f RootArgoCdApplicationPath`