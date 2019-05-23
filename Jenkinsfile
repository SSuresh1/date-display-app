node() {
    echo "Your Pipeline works!"
    sh('ls -la')
    checkout scm
    sh('ls -la')
    npm install
    npm test
}
