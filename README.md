mvn-repo
========

Repositorio maven para proyectos personales

en la parte de repositorios:

    <repositories>
        <repository>
            <id>com.xplook.packager</id>
            <url>https://raw.github.com/christmo/mvn-repo/master/</url>
            <snapshots>
                <enabled>true</enabled>
                <updatePolicy>always</updatePolicy>
            </snapshots>
        </repository>
    </repositories>


En las dependencias:

    <dependencies>
        <dependency>
            <groupId>com.xplook</groupId>
            <artifactId>packager</artifactId>
            <version>1.0-SNAPSHOT</version>
        </dependency> 
    </dependencies>        
        
        
        
