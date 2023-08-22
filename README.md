# queue-master

A microservices-demo service that provides reading from the shipping
queue. It will spawn new docker containers that simulate the shipping
process.

This build is built, tested and released by GitHub Actions

# Test

'./gradlew test' Unit test
'./gradlew integrationTest' Integration test

# Build

'./gradlew build --build-cache -x test -x integrationTest'

# Push
