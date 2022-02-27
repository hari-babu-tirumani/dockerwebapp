node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'DockerHub') {

        def customImage = docker.build("5755g6/test23")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
