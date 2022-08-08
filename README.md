# sbt-target-issue

OK (raises a compilation error):

```shell
cd anothername/seed
sbt clean compile
```

Not OK (do NOT raise a compilation error):

```shell
cd target/seed
sbt clean compile
```

Related to the scalac flag `-Wconf:src=target/.*:silent`
