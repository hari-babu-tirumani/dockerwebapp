node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'DockerHub') {

        def customImage = docker.build("5755g6/test")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
