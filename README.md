# java-update

Switch java version using update-alternatives

Install java and javac version:

```
update-alternatives --install /usr/bin/java java /opt/local/jdk-current/bin/java 1
update-alternatives --install /usr/bin/javac javac /opt/local/jdk-current/bin/javac 1
```

Usage:

`source java-update`
