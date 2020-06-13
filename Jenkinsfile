pipeline 
{
    agent any

	   stages 
		{
        	stage ('Compile Stage') 
			{
		            steps 
				{
                		withMaven(maven : 'Maven 3.6.5') 
					{
                    				sh 'mvn clean compile'
                			}
            			}
        		}
		}
}
