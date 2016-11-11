# ga-reporting-api-v4-test
Google Analytics Reporting API v4 Test
https://developers.google.com/analytics/devguides/reporting/core/v4/

Query explorer:
https://ga-dev-tools.appspot.com/query-explorer/

The free version (calculate the probability using this data, Markov):  
– sort ga:pageviews    
– max-results 10000  
– dimensions ga:pagePath,ga:previousPagePath  
– start-date 2016-01-01  
– start-index 1  
– ids ga: (your view ID)  
– metrics ga:pageviews  
– end-date yesterday  

# Gradle dependencies
	compile 'com.google.apis:google-api-services-analyticsreporting:v4-rev12-1.22.0'
	compile group: 'com.google.api-client', name: 'google-api-client-gson', version: '1.22.0'
