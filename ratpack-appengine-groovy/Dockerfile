FROM gcr.io/google_appengine/openjdk8

ADD build/distributions/ratpack-appengine-groovy.tar /

ENV JAVA_OPTS='-Dratpack.port=8080 -Djava.security.egd=file:/dev/./urandom'

ENTRYPOINT ["/ratpack-appengine-groovy/bin/ratpack-appengine-groovy"]
