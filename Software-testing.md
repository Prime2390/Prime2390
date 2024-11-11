<h1 align="center">Softwere Testing</h1>
<h3>The process of verifying the application's performance with the functional requirements.
</h3>
<h4><a href="https://github.com/Prime2390/Prime2390/blob/main/MyNote.md">Back To My Notes</a></h4>

<h2 id=0 align="center">Table of contents</h2>
<ul>
  <li><a href="#1">Objectives of testing</a></li>
  <li><a href="#2">The 7 cardinal commandments</a></li>
  <li><a href="#3">Divisions of testing</a></li>
  <li><a href="#4">Typical stages of testing</a></li>
  <li><a href="#5">Levels of abnormal results produced (ISTQB)</a></li>
</ul>

<h2 id=1 align="center">Objectives of testing</h2>
<ul>
  <li>Assessing the work products (stakeholder requirements, user stories, design and code)</li>
  <li>Checking that the requirements imposed on the project have been met</li>
  <li>Checking that the test subject is performing as expected</li>
  <li>Detecting defects and failures</li>
  <li>Ensuring test subject quality</li>
  <li>Providing stakeholders with information on work progress and detected defects</li>
</ul>

<h2 id=2 align="center">The 7 cardinal commandments</h2>
<ol type="I" >
<li><h3>Testing reveals faults, but cannot prove the absence of faults.</h3>
    <p>Software testing aims to detect defects so that they can be fixed before production implementation. At the same time, the testing process does not confirm that the software is completely free of defects.
</p></li>
<li>
  <h3>Ground testing is impossible.</h3>
  <p>It is impossible to test everything (all inputs and prerequisites in the software) due to time and budget. Therefore, it is important to plan the tests well and to direct the effort to the essential elements of the software.</p>
</li>
<li>
  <h3>Early testing saves time and money.</h3>
  <p>It will be easier and cheaper to test the assumptions of the project itself, the documentation before coding and fixing any bugs found (Agile Principle).</p>
</li>
<li>
  <h3>Accumulation of defects.</h3>
  <p>It is a rule of that informs us that certain software components or modules usually contain the most defects or are responsible for the majority of failures in the software produced.</p>
</li>
<li>
<h3>The pesticide paradox.</h3>
  <p>It is important to constantly review your test and modify it. Running the same tests over and over again will not find new defects.</p>
</li>
<li>
  <h3> Testing is context dependent.</h3>
  <p>The methods and types of tests carried out can depend entirely on the software or systems you are currently testing. The approach depends on what you are currently testing.</p>
</li>
<li>
  <h3>he belief that there are no errors is a mistake.</h3>
  <p>It doesn't matter how defect-free a system is if usability is so low that users can't even navigate the software.</p>
</li>
</ol>

<h2 id=3 align="center">Divisions of testing</h2>
<h3>Due to the objects tested</h3>
<ul>
  <li>Dynamic testing is when a module or system is run, for example a web application
</li>
  <li>Static testing is where testing can be performed without running the test object (Automatic and manual checking of code to find errors)</li>
</ul>
<h2 id=4 align="center">Typical stages of testing</h2>
<ol>
  <li>
    <h3>Test planning => Product (Test plan)</h3>
  <ul>
    <li>Definition of test objectives</li>
    <li>Defining test activities</li>
    <li>Determine appropriate test techniques and test tasks</li>
    <li>Formulation of the test schedule</li>
  </li></ul>
    
  <li>
    <h3>Test monitoring => Product (Test report</h3>
    <ul>
      <li>Checking the results and the test log </li>
      <li>Estimate the quality of the module or system based on the results</li>
      <li>Determination of whether further testing is necessary</li>
      <li>Reporting the progress of tests</li>
    </ul>
  </li>
  
  <li>
    <h3>Test analysis => Product (Test conditions</h3>
    <ul>
      <li>Familiarisation with the test requirements specification</li>
      <li>Analysis of module or code implementation and project information</li>
      <li>Analysis of risk analysis reports</li>
      <li>Definition of test conditions</li>
    </ul>
  </li>

   <li>
    <h3>Test Design => Product (Test Cases)</h3>
    <ul>
      <li>Design of test cases</li>
      <li>Collection of necessary test data</li>
    </ul>
  </li>

   <li>
    <h3>Test implementation => Product (Test data, Test execution schedule)</h3>
    <ul>
      <li>Preparation of test data</li>
      <li>Creation of automatic scripts</li>
      <li>Creation of test suites</li>
      <li>Building the environment</li>
    </ul>
  </li>

   <li>
    <h3>Testing => Product (Defect reports)</h3>
    <ul>
      <li>Testing</li>
      <li>Comparison of actual results with expected results</li>
      <li>Defect reporting</li>
      <li>Repetition of test activities (for example confirmatory or regression tests)</li>
    </ul>
  </li>

   <li>
    <h3>Test completion => Product (Test completion report)</h3>
    <ul>
      <li>Commissioning the system</li>
    </ul>
  </li>
  
</ol>


<h2 id=5 align="center">Levels of abnormal results produced (ISTQB)</h2>
<ul>
  <li>Mistake (error) - Human action produces an incorrect result.</li>
  <li>Defect - a defect in a work product, involving a failure to meet requirements.</li>
  <li>Failure - an event in which a module or system fails to perform the required functions</li>
</ul>
