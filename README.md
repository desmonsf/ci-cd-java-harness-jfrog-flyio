# ci-cd-java-harness-jfrog-flyio
Mini-lab CI/CD avec Maven, Docker, Harness, JFrog et Fly.io

Projetc Architecture
               GitHub
                 |
                 v
       [ Harness CI/CD Pipeline ]
                 |
     -------------------------------
     |        |         |         |
   Build    Test     Docker    Push
  (Maven)   (JUnit)  Build     to JFrog
                 |
                 v
        [ Fly.io / Railway App ]
            (Docker Deploy)
