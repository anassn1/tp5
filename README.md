<img width="752" height="706" alt="image" src="https://github.com/user-attachments/assets/679693e8-c6fd-4126-acd0-d819b6755cd6" />
<img width="730" height="593" alt="image" src="https://github.com/user-attachments/assets/8e45da42-daa4-4a45-945c-9f169c290e41" />
extentions result

C:\Users\anass\.jdks\ms-21.0.8\bin\java.exe "-javaagent:C:\Program Files\JetBrains\IntelliJ IDEA 2025.2.3\lib\idea_rt.jar=63758" -Dfile.encoding=UTF-8 -Dsun.stdout.encoding=UTF-8 -Dsun.stderr.encoding=UTF-8 -classpath C:\Users\anass\IdeaProjects\spring-hibernate-demo\target\test-classes;C:\Users\anass\IdeaProjects\spring-hibernate-demo\target\classes;C:\Users\anass\.m2\repository\org\springframework\spring-context\5.3.22\spring-context-5.3.22.jar;C:\Users\anass\.m2\repository\org\springframework\spring-aop\5.3.22\spring-aop-5.3.22.jar;C:\Users\anass\.m2\repository\org\springframework\spring-beans\5.3.22\spring-beans-5.3.22.jar;C:\Users\anass\.m2\repository\org\springframework\spring-core\5.3.22\spring-core-5.3.22.jar;C:\Users\anass\.m2\repository\org\springframework\spring-jcl\5.3.22\spring-jcl-5.3.22.jar;C:\Users\anass\.m2\repository\org\springframework\spring-expression\5.3.22\spring-expression-5.3.22.jar;C:\Users\anass\.m2\repository\org\springframework\spring-orm\5.3.22\spring-orm-5.3.22.jar;C:\Users\anass\.m2\repository\org\springframework\spring-jdbc\5.3.22\spring-jdbc-5.3.22.jar;C:\Users\anass\.m2\repository\org\hibernate\hibernate-core\5.6.12.Final\hibernate-core-5.6.12.Final.jar;C:\Users\anass\.m2\repository\org\jboss\logging\jboss-logging\3.4.3.Final\jboss-logging-3.4.3.Final.jar;C:\Users\anass\.m2\repository\javax\persistence\javax.persistence-api\2.2\javax.persistence-api-2.2.jar;C:\Users\anass\.m2\repository\net\bytebuddy\byte-buddy\1.12.9\byte-buddy-1.12.9.jar;C:\Users\anass\.m2\repository\antlr\antlr\2.7.7\antlr-2.7.7.jar;C:\Users\anass\.m2\repository\org\jboss\spec\javax\transaction\jboss-transaction-api_1.2_spec\1.1.1.Final\jboss-transaction-api_1.2_spec-1.1.1.Final.jar;C:\Users\anass\.m2\repository\org\jboss\jandex\2.4.2.Final\jandex-2.4.2.Final.jar;C:\Users\anass\.m2\repository\com\fasterxml\classmate\1.5.1\classmate-1.5.1.jar;C:\Users\anass\.m2\repository\javax\activation\javax.activation-api\1.2.0\javax.activation-api-1.2.0.jar;C:\Users\anass\.m2\repository\org\hibernate\common\hibernate-commons-annotations\5.1.2.Final\hibernate-commons-annotations-5.1.2.Final.jar;C:\Users\anass\.m2\repository\javax\xml\bind\jaxb-api\2.3.1\jaxb-api-2.3.1.jar;C:\Users\anass\.m2\repository\org\glassfish\jaxb\jaxb-runtime\2.3.1\jaxb-runtime-2.3.1.jar;C:\Users\anass\.m2\repository\org\glassfish\jaxb\txw2\2.3.1\txw2-2.3.1.jar;C:\Users\anass\.m2\repository\com\sun\istack\istack-commons-runtime\3.0.7\istack-commons-runtime-3.0.7.jar;C:\Users\anass\.m2\repository\org\jvnet\staxex\stax-ex\1.8\stax-ex-1.8.jar;C:\Users\anass\.m2\repository\com\sun\xml\fastinfoset\FastInfoset\1.2.15\FastInfoset-1.2.15.jar;C:\Users\anass\.m2\repository\mysql\mysql-connector-java\8.0.29\mysql-connector-java-8.0.29.jar;C:\Users\anass\.m2\repository\com\google\protobuf\protobuf-java\3.19.4\protobuf-java-3.19.4.jar;C:\Users\anass\.m2\repository\org\springframework\spring-tx\5.3.22\spring-tx-5.3.22.jar;C:\Users\anass\.m2\repository\javax\validation\validation-api\2.0.1.Final\validation-api-2.0.1.Final.jar TestHibernate
oct. 16, 2025 9:49:18 PM org.hibernate.Version logVersion
INFO: HHH000412: Hibernate ORM core version 5.6.12.Final
oct. 16, 2025 9:49:19 PM org.hibernate.annotations.common.reflection.java.JavaReflectionManager <clinit>
INFO: HCANN000001: Hibernate Commons Annotations {5.1.2.Final}
oct. 16, 2025 9:49:19 PM org.hibernate.dialect.Dialect <init>
INFO: HHH000400: Using dialect: org.hibernate.dialect.MySQL8Dialect
oct. 16, 2025 9:49:19 PM org.hibernate.resource.transaction.internal.TransactionCoordinatorBuilderInitiator determineStrategySelection
WARN: HHH90000018: Found use of deprecated transaction factory setting [hibernate.transaction.factory_class]; use the new TransactionCoordinatorBuilder settings [hibernate.transaction.coordinator_class] instead
oct. 16, 2025 9:49:20 PM org.hibernate.engine.transaction.jta.platform.internal.JtaPlatformInitiator initiateService
INFO: HHH000490: Using JtaPlatform implementation: [org.hibernate.engine.transaction.jta.platform.internal.NoJtaPlatform]
=== TEST CRUD COMPLET SPRING + HIBERNATE ===
Hibernate: 
    insert 
    into
        Product
        (name, price) 
    values
        (?, ?)
Hibernate: 
    insert 
    into
        Product
        (name, price) 
    values
        (?, ?)
✅ Produits créés avec IDs: 3 et 4

✅ Liste de tous les produits:
Hibernate: 
    select
        product0_.id as id1_0_,
        product0_.name as name2_0_,
        product0_.price as price3_0_ 
    from
        Product product0_
   - 1 | Produit 1 | 100.0€
   - 2 | Produit 1 | 100.0€
   - 3 | Ordinateur Portable | 1200.99€
   - 4 | Souris Gaming | 45.5€
Hibernate: 
    select
        product0_.id as id1_0_0_,
        product0_.name as name2_0_0_,
        product0_.price as price3_0_0_ 
    from
        Product product0_ 
    where
        product0_.id=?

✅ Produit trouvé par ID 3: Ordinateur Portable
Hibernate: 
    update
        Product 
    set
        name=?,
        price=? 
    where
        id=?
✅ Produit modifié: Nouveau prix = 1100.99€
Hibernate: 
    delete 
    from
        Product 
    where
        id=?
✅ Produit supprimé: true

✅ Produits restants après suppression:
Hibernate: 
    select
        product0_.id as id1_0_,
        product0_.name as name2_0_,
        product0_.price as price3_0_ 
    from
        Product product0_
   - 1 | Produit 1 | 100.0€
   - 2 | Produit 1 | 100.0€
   - 3 | Ordinateur Portable | 1100.99€

🎉 TEST TERMINÉ AVEC SUCCÈS !

Process finished with exit code 0
  
