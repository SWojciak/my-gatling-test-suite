## My Gatling Test Suite - performance test suite

Project uses [sbt plugin][sbtplugindoc] of [gatling][gatlingdoc].
It contains basic simulation from gatling quick start bundle.

[sbtplugindoc]: https://gatling.io/docs/current/extensions/sbt_plugin/
[gatlingdoc]: https://gatling.io/docs/current/advanced_tutorial/

Initially generated by the following command:
```
sbt new gatling/gatling.g8
```

### Run

All tests:
```
sbt "gatling:test"
```

Single test:
```
sbt "gatling:testOnly computerdatabase.BasicSimulation" -Dsbt.log.noformat=true
```

Report:
```
sbt "gatling:lastReport"
```
