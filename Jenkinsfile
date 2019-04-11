node{
    stage("Checkout"){
        checkout scm;
    }

    stage("Install"){
        dir('app'){
            sh 'npm install';

        }
    }

    stage("Unit Test"){
        dir('app'){
            sh 'npm run test:unit';
           
        }
    }
}