wrappedNode(label: "docker && ubuntu" , cleanWorkspace: true) {
  withChownWorkspace {
    checkout scm
    sh("echo 'Hello World'")
  }
}
