node {
  checkout scm
  withEnv(["PATH+NODE=${tool 'node'}/bin"]) {
    sh 'npm install && npm test'
  }
}
