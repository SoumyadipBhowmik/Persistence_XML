# Persistence_XML

<persistence-unit name="dev">
	<provider>org.hibernate.jpa.HibernatePersistenceProvider</provider>
	<shared-cache-mode>ENABLE_SELECTIVE</shared-cache-mode>
	<properties>
		<property name="javax.persistence.jdbc.driver" value="com.mysql.cj.jdbc.Driver" />
		<property name="javax.persistence.jdbc.url" value="jdbc:mysql://localhost:3306/hdbc" />
		<property name="javax.persistence.jdbc.user" value="root" />
		<property name="javax.persistence.jdbc.password" value="root" />
		<property name="hibernate.show_sql" value="true" />
		<property name="hibernate.hbm2ddl.auto" value="update" />
		<property name="hibernate.dialect" value="org.hibernate.dialect.MySQL8Dialect"/>
	</properties>
</persistence-unit>
