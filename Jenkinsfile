node{
    stage("Checkout"){
        checkout scm;
    }

    stage("Install"){
       
            bat 'npm install';

        
    }

    stage("Unit Test"){
   
            bat 'npm run test';
           
        
    }
}