
# ========================NEXUS==============================

<distributionManagement>
	<repository>
		<id>nexus-rps-deploy</id>
		<name>Internal Releases</name>
		<url>http://localhost:8081/nexus/content/repositories/nexus-rps-release/</url>
	</repository>
 
	<snapshotRepository>
		<id>nexus-rps-deploy</id>
		<name>Internal Releases</name>
		<url>http://localhost:8081/nexus/content/repositories/nexus-rps-snapshot/</url>
	</snapshotRepository>

</distributionManagement>

=====================SETTING.XML=================================
   <server>
		<id>nexus-rps-deploy</id>
		<username>nexus-rps-deploy</username>
		<password>srikzz@1</password>
</server>


