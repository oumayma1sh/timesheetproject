pipeline {

agent any


stages {

stage('GIT') {

           steps {

               git branch: 'master',

               url: 'https://github.com/oumayma1sh/timesheetproject.git'

          }

     }

stage ('Compile Stage') {

    steps {

        sh 'mvn clean compile'

    }

}

}

}