# alpine-groovy-newrelic
An Alpine Linux docker image based on `groovy:2.4-alpine` with the
[New Relic](https://newrelic.com/) Java agent installed into `/opt/newrelic`.


## Usage

Mount (or copy) the `newrelic.yml` configuration file into `/opt/newrelic`. At
a minimum the `license_key` and `app_name` settings must be updated.

Add `-javaagent:/opt/newrelic/newrelic.jar` as a JVM Option.


## Docker Hub

Available on Docker Hub as [rigoford/alpine-groovy-newrelic](https://hub.docker.com/r/rigoford/alpine-groovy-newrelic).


## Further details

Refer to https://docs.newrelic.com/docs/agents/java-agent for further details.
