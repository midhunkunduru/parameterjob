properties([
  parameters([
    string(name: 'param1', description: 'Possible options: a b c d', defaultValue: ''),
    string(name: 'param2', description: 'Possible options: e f g h', defaultValue: ''),
    string(name: 'param3', description: 'Possible options: k l m n', defaultValue: ''),
    string(name: 'param4', description: 'Possible options: 1 2 3 4', defaultValue: ''),
  ])
])
node("master")
{
    stage("Checkout")
{  
    sh 'echo $BRANCH_NAME'
}
    
    stage("Build")
    {
        echo "Sample build"
    }

}
