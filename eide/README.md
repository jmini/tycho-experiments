# EIDE (custom build for Eclipse IDE)

Build:

```
mvn verify
```

Tested with:

* **Java**: openjdk version "21.0.3" 2024-04-16 LTS
* **Maven**: Apache Maven 3.8.4


## Edit: 2024-09-03

SonarLint was added to the eide product, in order to reproduce the issue discussed here:
https://community.sonarsource.com/t/cannot-run-program-sloop-jre-bin-java-caused-by-permission-denied/124054

## Edit: 2024-10-10

Attempt to update to `10.8.0.82289`, to discuss:

https://community.sonarsource.com/t/installation-of-10-8-0-via-tycho-failing-because-of-missing-sonarlint-java-client-osgi-version/127834
