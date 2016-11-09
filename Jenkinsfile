wrappedNode(label: "docker && ubuntu" , cleanWorkspace: true) {
  withChownWorkspace {
    checkout scm
    sh("echo $PWD")
  }
}
