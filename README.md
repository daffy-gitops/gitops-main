# Integration from Daffy to GitOps

An initial approach to integrate Daffy to GitOps 

Take 01 - 
1. Daffy templates are built to gitops/<PRODUCT_SHORT_NAME>
2. The <PRODUCT_SHORT_NAME> is enabled from main kustomization gitops
3. The <PRODUCT_SHORT_NAME> contains 5 layers infra - catalog - subscription - instances - apps 
4. individual capabilities are enabled in the kustomization.yaml