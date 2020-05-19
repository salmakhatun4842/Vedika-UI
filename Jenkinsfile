node{

stage('Git checkout'){
    git branch: 'vedui2', url: 'https://github.com/salmakhatun4842/Vedika-UI.git'
  }
  
stage('npm install'){
  sh label: '', script: 'npm install'
 }
  stage('build'){
    sh label: '', script: 'ng build --prod'
  }
  
  
}
