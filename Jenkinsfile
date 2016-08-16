node(‘linux’){
  git url: 'https://github.com/timwillmann/ABItestREPO.git'
  def mvnHome = tool 'M3'
  env.PATH = "${mvnHome}/bin:${env.PATH}"
  sh 'mvn -B clean verify'
}