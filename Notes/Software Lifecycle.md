<div align="center"><h1>Software Lifecycle</h1> </div>
<h4>
A software lifecycle model is a description of the activities that go into the software development process and the relationships between them. The model is used to determine how the software will be developed. It introduces phases that separate the various software development processes.
</h4>

<h4>
For each of the software development activities, a testing activity is assigned, where tests are assigned to the corresponding objectives assigned to the current phase.
</h4>

<div align="center">
<a href=https://github.com/Prime2390/Prime2390/blob/main/Notes/MyNote.md>
    <img src="https://raw.githubusercontent.com/Prime2390/Prime2390/refs/heads/main/Icons/DALL·E%202024-11-11%2022.20.53%20-%20A%20minimalistic%20and%20modern%20icon%20representing%20'Back%20to%20Menu'.%20The%20icon%20should%20feature%20an%20arrow%20pointing%20to%20a%20menu%20or%20list%20symbol%2C%20indicating%20navigation%20.webp" alt="Back to Menu" style="width:100px;height:100px;">
</a>
</div>

<h2 id=0 align="center">Table of contents</h2>
<ul>
  <li><a href="#1">Lifecycle</a></li>
  <li><a href="#2">Levels of Tests</a></li>
  <li><a href="#3">Types of Tests</a></li>
</ul>


<h2 id=1>Lifecycle</h2>
<h3>The software lifecycle can be performed in one of the systems such as:</h3>
<ul>
    <li><h4>Sequential (Linear) model</h4>
<p>Assumes that individual activities are performed one after the other. Therefore, the next phase will not start without completing the previous phase.</p>
</li>
    <li><h4>Iterative and incremental model</h4>
<p>Software is produced in short cycles, this means that functionality grows incrementally, so requirements and design, testing of the system is determined in parts.</p>
</li>
</ul>

<h3>We can divide sequential models into:</h3>
<ul>
    <li>
        <h4>Cascade model</h4>
        <p>This is a serial model, i.e. each successive design phase follows one after the other
</p>
    </li>
    <li>
        <h4>V model</h4>
        <p>TAssumes the integration of testing processes from the entire software development process and thus introduces the principle of early testing.
</p>
    </li>
</ul>
<h3>In contrast, the Iterative and Incremental Model can be divided into:
</h3>
<ul>
     <li>
        <h4>RUP Model</h4>
        <p>Is a flexible process structure within which individual processes are defined
</p>
    </li>
     <li>
        <h4>Sacrum</h4>
        <p>The software produced is divided into short iterations of the same length, and the incremental parts of the system are correspondingly small so they assume frequent changes
</p>
    </li>
     <li>
        <h4>Kanban</h4>
        <p>Ensures that one enhancement or functionality is delivered at a time or that more functionality is grouped together for simultaneous delivery to the production environment

</p>
    </li>
     <li>
        <h4>Boehm's spiral model</h4>
        <p>Experimental incremental components are created which may then be extensively rebuilt or even abandoned. Components often overlap and result in repeated levels of testing in the software lifecycle
</p>
    </li>
</ul>

<h4>
The software lifecycle model must be selected and adapted to fit the context resulting from the project and the final product.</h4>

<h2 id=2>Levels of tests</h2>
<h4>
A good time to introduce the concepts of test levels is during the software life cycle, as each of the levels presented here has a particular impact at a different stage of the software life cycle.</h4>

<h4>The main levels of testing we can include:</h4>
<ul>
    <li>
        <h5>Modular testing (Unit testing)</h5>
        <p>Focuses on modules that can be tested separately, i.e. the system code is tested</p>
    </li>
     <li>
        <h5>Integration testing</h5>
        <p>Testing focuses on interactions between modules or systems.</p>
    </li>
     <li>
        <h5>System testing</h5>
        <p>Focuses on the behaviour and capabilities of the entire integrated system 
</p>
    </li>
     <li>
        <h5>Acceptance testing</h5>
        <p>Testing assesses the readiness of the system for production deployment
</p>
</ul>
<h5>Adaptive testing may also be followed by Alpha testing performed at the premises of the software organisation. These are performed by potential or existing customers or independent testers. Beta tests are also performed by potential or existing customers but at their own locations.
</h5>

<h2 id=3>Types of Tests</h2>
<h4>Groups of dynamic test activities performed to test specific systems are called test types, and include:</h4>
<ol type="I">
<li>
    <h5>Functional testing
</h5>
    <p>hese tests evaluate the functions that the system should perform. </p>
    <p>These functions are described in:</p>
    <ul>
        <li>Requirements specification</li>
        <li>Stories</li>
        <li>User stories</li>
    </ul>
</li>

<li>
    <h5>Non-functional testing</h5>
    <p>The purpose of testing is to evaluate system characteristics such as:
</p>
    <ul>
        <li>Ustability</li>
        <li>Performance</li>
        <li>Security</li>
        <p>Non-functional testing checks how a system behaves</p>
    </ul>
</li>

<li>
    <h5>White-box testing</h5>
    <p>These are tests that are introduced based on the internal structure or implementation of a given system.</p>
</li>  

<li>
    <h5>Change-related testing</h5>
    <p>They are performed after introducing changes to the system in order to add or modify functionality and remove the detected defects. Tests should be performed to confirm the correctly implemented functionality or removal of defects.</p>
    <p>Tests can be divided into 2 categories</p>
    <ul>
        <li>
            <p>Confirmation tests</p>
            <p>They are performed in connection with defect repair. The role of the confirmation test is to check whether the defect has been removed</p>
        </li>
        <li>
            <p>Regression tests</p>
            <p>Are used to check whether changes made to one part of the code have affected the behaviour of other parts of the code in the same module, in other modules of the same system, or in other systems </p>
        </li>
    </ul>
   
</ol>



