pipeline{
agent any
stages{
 stage("Build and Test"){
 steps{
echo'Build and Test Successful';
}
}
stage("Generate an Artifact"){
steps{
echo "Hello"
}
}
}
post{
success{
echo "Pipeline is Successful";
}
}
}