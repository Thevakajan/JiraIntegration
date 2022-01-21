# JiraIntegration
selenium
try {

            //Avoid Creating Duplicate Issue

            Issue.SearchResult sr = Jira.searchIssues("summary ~ \""+summary+"\"");

            if(sr.total!=0) {

                System.out.println("Same Issue Already Exists on Jira");

                return;

            }
            
            
            https://www.browserstack.com/guide/how-to-integrate-jira-with-selenium
