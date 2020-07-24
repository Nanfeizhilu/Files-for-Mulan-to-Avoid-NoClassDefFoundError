# Files-for-Mulan-to-Avoid-NoClassDefFoundError
Some Files should be created in Mulan Github project mulan\mulan folder to avoid NoClassDefFoundError
1.  create ".project" file and write following codes to it:
<?xml version="1.0" encoding="UTF-8"?>
<projectDescription>
	<name>mulan</name>
	<comment></comment>
	<projects>
	</projects>
	<buildSpec>
		<buildCommand>
			<name>org.eclipse.jdt.core.javabuilder</name>
			<arguments>
			</arguments>
		</buildCommand>
		<buildCommand>
			<name>org.eclipse.m2e.core.maven2Builder</name>
			<arguments>
			</arguments>
		</buildCommand>
	</buildSpec>
	<natures>
		<nature>org.eclipse.jdt.core.javanature</nature>
		<nature>org.eclipse.m2e.core.maven2Nature</nature>
	</natures>
</projectDescription>

2. create ".classpath" file and write following codes to it 
<?xml version="1.0" encoding="UTF-8"?>
<classpath>
	<classpathentry kind="src" output="target/classes" path="src/main/java">
		<attributes>
			<attribute name="optional" value="true"/>
			<attribute name="maven.pomderived" value="true"/>
		</attributes>
	</classpathentry>
	<classpathentry kind="src" output="target/test-classes" path="src/test/java">
		<attributes>
			<attribute name="optional" value="true"/>
			<attribute name="maven.pomderived" value="true"/>
		</attributes>
	</classpathentry>
	<classpathentry kind="con" path="org.eclipse.jdt.launching.JRE_CONTAINER/org.eclipse.jdt.internal.debug.ui.launcher.StandardVMType/JavaSE-1.8">
		<attributes>
			<attribute name="maven.pomderived" value="true"/>
		</attributes>
	</classpathentry>
	<classpathentry kind="con" path="org.eclipse.m2e.MAVEN2_CLASSPATH_CONTAINER">
		<attributes>
			<attribute name="maven.pomderived" value="true"/>
		</attributes>
	</classpathentry>
	<classpathentry kind="output" path="target/classes"/>
</classpath>
