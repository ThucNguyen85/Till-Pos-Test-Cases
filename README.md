# Till-Pos-Test-Cases
I created the test cases by using Excel. Please download TillPos.xlsx and run it by excel. 
For the details: I created 4 tabs:
  - Summary: Summarize the result of test execution 
  - Computer Database List: The list test cases to verify the Computer Database List page
  - Add Computer: The list test cases to verify the Add Computer page 
  - Edit Computer: The list test cases to verify the Edit Computer page 
  
 For each test case, it has following items:
  - ID
  - Pre Conditions: The prepare things before running the test case
  - Test Scenario: The summary of the test case 
  - Steps: Step by step to execute the test case 
  - Expected Result: The expectaction of the test case
  - Serverity: The severity of the test case
  - Note: you are able to add bug found or notes in this column
  - Platforms: Desktop and Mobile
    + Desktop: Chrome, Edge, Firfox and Safari
    + Mobile: Viewport 414x896, Viewport 375 x 812, Viewport 357 x 667, Viewport 390 x 884, Viewport 428 x 926, Viewport 360 x 800, Viewport 412 x 915. I suggested to run on these view ports because they are the most popular nowaday. The less popular viewport is on the right. 
    
Strategy to execute when perform full regression:
  - Run the Major and Critical testcases on all platforms 
  - For the Medium:
    + Should run them all on Chrome, Edge, Safari and the most 3 popular viewports 
    + Run them randomly and mixed on the remaining platforms
  - For the Minor: Run them randomly and mixed on all platforms

Strategy to execute when performing smoke test
 - Run all Major and Critical testcases on Chrome, Edge, Safari and the most 3 popular viewports 
 - Run the remaining test cases randomly and mix on other platforms
