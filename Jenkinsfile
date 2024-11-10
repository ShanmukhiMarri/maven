pipeline 
{
    agent any
	    stages 
	{
		stage('Information') 
		{
            steps 
			{
                echo 'Layola Public School'
				echo 'The below information is the total number of students in School'
				echo 'What you Do Today can Improve all your tomorrows'
            }
        }
        stage('Primary') 
		{
            steps 
			{
                echo 'From first to Fifth Students we called as primary School'
				echo ''
				echo 'In Primary school there are 100 students'
            }
        }
		stage('Secondary') 
		{
            steps 
			{
                echo 'From Sixth to Tenth Students we called as Secondary School'
				echo 'In Secondary school there are 200 students'
            }
        }
		stage('Intermediate') 
		{
            steps 
			{
                echo ' In +1 Intermediate there are 130 students'
				echo 'In +2 Intermediate there are 190 students'
            }
        }
		
    }
	
	post
	{
		always
		{
			echo'The above Information is the correct information.'
			echo 'Thank You for choosing Layola Public School'
			echo 'Thankyou User !'
		}
	}
}
