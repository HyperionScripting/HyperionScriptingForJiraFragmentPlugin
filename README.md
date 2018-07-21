# Hyperion Scripting for Jira Fragment Plugin
This is an OSGi fragment bundle that is capable of attaching to Hyperion host bundle with a purpose of asking Hyperion host add-on to import additional Java classes. Read more [here](http://hyperionscripting.com/doc/jira/scripting/latest/#importing-unknown-classes).

1. First clone the repo.
2. Edit pom.xml and add Java packages where your classes resided under Import-Package.
3. Build the plugin: mvn org.apache.felix:maven-bundle-plugin:bundle.
4. Upload the plugin to JIRA.
5. Re-install or re-enable Hyperion Scripting for JIRA add-on. Otherwise changes won't take effect.
