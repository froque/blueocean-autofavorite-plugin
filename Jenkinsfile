// Builds a module using https://github.com/jenkins-infra/pipeline-library
buildPlugin(useContainerAgent: true, configurations: [
        [ platform: "linux", jdk: "8" ],
        [ platform: "windows", jdk: "8" ],
        [ platform: "linux", jdk: "11", jenkins: "2.222.3" ]
])
