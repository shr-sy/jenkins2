Pipeline
       {
       agent any
           stages
                {
                 stage("GIT")
                       {
                        steps
                              {
                               git "https://github.com/shr-sy/jenkins2.git"
                              }
                       }
                 stage("Run")
                            {
                             steps
                                 {
                                  sh " java Demo.java"
                                  sh "python main.py"
                                 }
                            }
                }
       }
                       
              

