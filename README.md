# Gradle build cache performance benchmarks

What it says on the tin. Run it like this:

```command-line
gradle-profiler \
  --profile buildscan \
  --scenario-file performance.scenario \
  --project-dir spring-security \
  --gradle-version 4.5 \
  --gradle-version ~/dev/gradle/local-install
```
