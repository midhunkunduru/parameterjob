properties([
  parameters([
    string(name: 'param1', description: 'Possible options: a b c d', defaultValue: ''),
    string(name: 'param2', description: 'Possible options: e f g h', defaultValue: 'defvalue'),
    string(name: 'param3', description: 'Possible options: k l m n', defaultValue: ''),
    string(name: 'param4', description: 'Possible options: 1 2 3 4', defaultValue: ''),
  ])
])
node("master")
{
  def a = "localvariablevalue"
    stage("Checkout")
{
  echo "${a}"
  echo "${param1}"
  
  echo "${param2}"
  
  echo "${param3}"
  
  echo "${param4}"
  
}
    
    stage("Build")
    {
        echo "Sample build"
    }

}
