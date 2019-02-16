FROM google/cloud-sdk:alpine

RUN apk add gradle git
RUN gcloud components install app-engine-java
ENV APPENGINE_HOME /google-cloud-sdk/platform/google_appengine/google/appengine/tools/java