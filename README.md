# Example setup to reproduce issue 310 in maven-git-commit-id-plugin.

## Show bug is present
```
mvn -Pwith-property-filtering test
```

## Show bug is absent
```
mvn -Pwithout-property-filtering test
```

