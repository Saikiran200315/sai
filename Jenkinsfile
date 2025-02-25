pipeline
{
agent any
{
stages('clone')
{
steps
{
git 'https://github.com/Saikiran200315/sai.git'
}
}
stages('build')
{
steps{
sh' javac hello.java'
}
}
stages('run')
{
steps
{
sh'java.hello'
}
}
}
