node{
    stage("Checkout"){
        checkout scm;
    }

    stage("Install"){
       
            sh 'npm install';

        
    }

    stage("Unit Test"){
   
            sh 'npm run test:unit';
           
        
    }
}