# Implement Single Surce Of Truth for Kubernetes Based Applications with Werf

Esta POC tem a finalidade de implementar o conceito de Single Source of Truth para aplicações em microserviços que sejam executadas em ambiente Kubernetes.

Single Source of Truth: [SSOT](www.google.com)

## Index

<ul>
  <li>1.0 What is Werf?</li>
  <li>2.0 Werf is different of Helm?</li>
  <li>3.0 Build Images and make deployments with helm based charts</li>
    <ul>
        <li>3.1 Preparing the environment</li>
        <li>3.2 Install Werf</li>
        <li>3.3 Integrate with Kubernetes</li>
        <li>3.4 Prepare the application(Single source of truth)</li>
        <li>3.5 Create charts with werf generate chart</li>
        <li>3.6 Prepare all files</li>
        <li>3.7 Deploy the application to Kubernetes AShop</li>
    </ul>
  <li> Bonus: Integrate with a existing CI/CD (Jenkins????)
</ul>

Application to deploy:
https://github.com/dockersamples/atsea-sample-shop-app/tree/master/database

