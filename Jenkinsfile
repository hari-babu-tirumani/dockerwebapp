node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'DockerHub') {

        def customImage = docker.build("5755g6/nodejsapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
