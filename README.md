# jnlp-slave-with-docker
Based on cloudbees/jnlp-slave-with-java-build-tools with extras like docker,sonarqube,awslci,chrome browser and chrome driver
You can also build other docker containers from host by adding the host docker socket as a volume.
e.g -volumes:
  - /var/run/docker.sock:/var/run/docker.sock
