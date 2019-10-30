mvn clean compile -Pjdbc3 -DJAVA_HOME=D:\JDK\IBMJDK1.5

mvn clean install -Pjdbc3 -DJAVA_HOME=D:\JDK\IBMJDK1.5

mvn clean compile -Pjdbc4 -DJAVA_HOME=D:\JDK\jdk1.6.0_45

mvn clean compile -Pjdbc5 -DJAVA_HOME=D:\JDK\jdk1.7.0X64


mvn clean package -Pjdbc6 -DJAVA_HOME=D:\JDK\jdk1.8.0X64


mvn clean install -Pjdbc6 -DJAVA_HOME=D:\JDK\jdk1.8.0X64

mvn clean source:jar deploy  -Pjdbc4 -DJAVA_HOME=D:\JDK\jdk1.6.0_45

mvn source:jar javadoc:jar deploy  -Dmaven.compiler.fork=true -Dmaven.compiler.source=1.5 -Dmaven.compiler.target=1.5 -Dmaven.compiler.compilerVersion=1.5  -DskipTests=true -DaltDeploymentRepository=...
