
# WEB/Bibliographie: JBOSS / TOP 5

https://access.redhat.com/documentation/en-us/jboss_enterprise_application_platform/
https://access.redhat.com/documentation/fr-fr/jboss_enterprise_application_platform/
https://access.redhat.com/documentation/fr-fr/red_hat_jboss_enterprise_application_platform/7.2/
https://access.redhat.com/documentation/en-us/jboss_enterprise_application_platform/6.1/html
* https://developers.redhat.com/blog

Book:
http://www.itbuzzpress.com/ebooks/wildfly-performance-tuning-book.html
* http://www.mastertheboss.com/



----------------------------------------------
##  TP/Database/Driver/  Datasource

https://www.stenusys.com/how_to_setup_postgresql_datasource_with_wildfly/

##  TP  Role Base
https://dzone.com/articles/configuring-rbac-jboss-eap-and

-------------------------
##  TP  SSL
* Test 1 :
https://localhost:8443/

* Test 2 :
https://localhost:8443/ 

* Verifichier le  mot  "" dans standalone.xml

*  .keystore ?

* https://access.redhat.com/documentation/en-us/jboss_enterprise_application_platform/6.1/html/administration_and_configuration_guide/generate_a_ssl_encryption_key_and_certificate

* https://knowledge.digicert.com/solution/SO17413.html

# TP  Domain:

Domaine Jboss/Wildfly  = Instances Wildfly   + Controleur de domaine'master' + Controleur d’hote'slave' .

* Creer une nouvelle installation/zip de Wildfly pour le TP

*  dans HOMEWILDFLY/bin :

-  add-user.bat  -u  admin -p  admin

- lancer  domain.bat 

-  Verififier la création du repertoire ‘servers’ dans le répertoire ‘domain’

- Compter les process java sur la machine /

* https://developers.redhat.com/blog/2016/07/28/jboss-eap-7-domain-deployments-part-1-setup-a-simple-eap-domain/

* https://developers.redhat.com/blog/2016/08/05/jboss-eap-7-domain-deployments-part-2-domain-deployments-through-the-eap-7-0-management-console/


#TP  Docker Interface de Management
http://www.mastertheboss.com/soa-cloud/docker/deploying-applications-on-your-docker-wildfly-image

# Tuning
http://www.itbuzzpress.com/ebooks/wildfly-performance-tuning-book.html

http://www.mastertheboss.com/jboss-server/jboss-performance/jboss-as-7-performance-tuning



