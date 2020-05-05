# Business Process Optimize

<h2>Problem Statement</h2>

<p>As a process owner, I want to see statistics of process, So that I can Optimize it. We need to build a web application, which consumes API available in Camunda to show the below statistics.</p>

<ul>
  <li>How many process instances have been executed in the last 30 days, and how has this number changed over time? (bar chart or line chart)</li>
  <li>Most and lease frequently executed task</li>
  <li>The average time is taken for a process instance to finish</li>
  <li>The average time spent on a specific task</li>
</ul> 

<h2>UI Screens</h2>
<img src="URL">


<h2>BPM Overview</h2>
<p> Please go through below links to gain understanding of BPM </p>
<ul>
  <li>https://en.wikipedia.org/wiki/Business_process_management</li>
  <li>https://kissflow.com/bpm/business-process-management-overview/</li>
</ul>

<h2>Camunda overview</h2>
<p> Please go through below links to gain understanding of Camunda </p>
<ul>
  <li>https://www.youtube.com/watch?v=j6nkaAnxp5k</li>
  <li>https://docs.camunda.org/manual/7.8/introduction/</li>
</ul>


<h2>API’s/Middleware</h2>
<ul>
  <li>Get a list of processes: https://docs.camunda.org/manual/7.8/reference/rest/process-definition/get-query/</li>
  <li>Get process (XML): https://docs.camunda.org/manual/7.8/reference/rest/process-definition/get-xml/</li>
  <li>Get task statistic: https://docs.camunda.org/manual/7.8/reference/rest/history/</li>
</ul>

<h2>Backend/DB Model</h2>
<p>No need to create DB, Camunda provides in-memory DB implementation (H2). In case standalone DB is needed, then refer below link. It's also helpful to understand DB structure of Camunda.</p>
<ul>
  <li>BD structure overview: https://docs.camunda.org/manual/7.5/user-guide/process-engine/database/</li>
</ul>

<h2>UI</h2>
<p>Below links will be helpful to understand how Camunda JS SDK can be use to display process in web application</p>
<ul>
  <li>View and edit BPMN 2.0 diagrams in the browser: https://github.com/bpmn-io/bpmn-js</li>
  <li>This example shows how to add colors to BPMN diagrams: https://github.com/bpmn-io/bpmn-js-examples/tree/master/colors</li>
</ul>

<h2>Automation Scipts</h2>
<p>To generate appropriate reports, we need sufficient data in DB. For that, students need to come up with the approach</p>
