# Logstash---ELK

Logstash is a tool to convert the file(Most of log files) and to pass it to the output sector(Elastic search, json file).

## How to install and run: 

	Step 1 : Download the logstash from https://www.elastic.co/downloads/logstash 
	Step 2 : Download Java 8. 
  To run, Open the command prompt and go to the logstash’s bin folder and type,  ```logstash -f filename.conf ```
  
  ```Note : Make sure that you are running the conf file from bin folder of logstash. ```
           
## Structure of conf file:

            input  { }

            filter { }

            output { } 

## Code Explanation: 	    

	The above code will find the ip location information(Example : countryname) from the logged user IP address.

## Helpful links: 

        1.	https://www.elastic.co/products/logstash
        2.	https://www.tutorialspoint.com/logstash/
        3.	https://www.youtube.com/watch?v=rKy4sFbIZ3U
        4.	https://discuss.elastic.co/
	
## Personal Suggeation:

	Feel free to ask :)
