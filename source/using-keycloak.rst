Using Keycloak
==============

From version v0.8.0 dojot uses [keycloak](https://www.keycloak.org/) and removes the use of our old "auth" service.
Keycloak is an open source identity and access management solution.

In this tutorial we will explain some important points of setting up and using keycloak with dojot.


- Using API interface

    - Usando com com login e senha (nao recomendado)
        - para utilizar interfaces apis diretamente com usurio e  senhas  necessrio habitar o cliente 
`dev-test-cli`
        - login
        - como master http://localhost:8000/auth
        - como admin de um realm
        - clients,

    - Usando secret


- SMTP

- Painel admin

- Configuaço de conta

- Senhas fortes

- use https

- como criar usuarios






-localhost:8000/auth
-http://localhost:8000/auth/admin/admin/console
-http://localhost:8000/auth/realms/admin/account/


http://localhost:8000/auth/admin/test1234/console/

http://localhost:8000/auth/realms/test1234/account/



https://sen.dojot.com.br/auth/admin/tenant2/console/



- TODO hwo add client
- TODO This is exactly the thing OAuth was created to prevent in the first place, so you should never allow third-party apps to use this grant.
- TODO explain how enable dev-test-cli
- TODO x509 create/update only if is a admin
- TODO check what do with sslRequired
- TODO https://docs.bitnami.com/general/apps/kong/configuration/kong-production/
- TODO remove  {"resourceName":"backstage","scopes":["view","create","update","delete"]},
- TODO tracking-simulator
- TODO device-manager-template to templates
- TODO KEYCLOAK_REALM_SSL_MODE, necessario recriar keycloak