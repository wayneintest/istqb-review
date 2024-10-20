Fundamentals of Testing

Identify typical test objectives (K1)
-Evaluating work-products such as documents, user stories, design, and code
-Verifying that specified requirements have been fulfilled
-Building confidence in the quality of the software
-Triggering failures and finding defects
-Preventing defects with static testing by evaluating or reviewing work-products
-Providing information to stakeholders to allow them to make informed decisions
-Reduce the level of risk of inadequate software quality
-Verifying the compliance of contractual, legal, and regulatory requirements
-Ensuring required test coverage
-Validating whether the test object is complete and works as expected by stakeholders
-Objectives may vary since testing is context dependent which there is no single universal approach    

Differentiate testing from debugging (K2)
Testing / Software testing is a set of activities to discover defects and evaluate the quality of the software artifact to reduce the risk of software failure in operation.
Since testing shows the presence of defects, debugging is concerned which typically is a process of: Reproducing the failure - Diagnosing the issue to identify the root case or defect - Fixing the root cause or defect - Retesting / performing Confirmation testing to ensure the defect is resolved and probably perform Regression testing to ensure that other parts of the software isn't affected

Exemplify why testing is necessary (K2)
Testing ensures usability, reliability, security, high performance/quality software resulting in time saving, cost-effectiveness(loss of money or business reputation due to failure), and customer satisfaction
Testing provides a cost-effective means to detect defects; having a dedicated good tester cost lesser compared to organizing a Beta testing session
Testing helps inform decisions such as release decisions ensuring that the product is ready to go live
Testing provides an indirect representation of an actual end-user

Recall the relation between testing and quality assurance (K1)
Testing is a form of Quality Control(QC). QC is product-oriented, corrective approach that is focused on activities supporting the achievement of appropriate levels of quality
Quality Assurance(QA) is process-oriented, preventive approach that is focused on implementation and improvement of processes that when good processes are followed, generates a good product

Distinguish between root cause, error, defect, and failure (K2)
Error is a mistake from a human being or from natural causes that then becomes a Defect, which is the reason or cause of a Failure, and when troubleshooting is concerned, Root Cause analysis is required in order to detect the defect to resolve the failure

Explain the seven testing principles (K2)
-Testing shows the presence, not absence of defects
    testing is to discover defects and reduce the probability of undetected bugs but unable to prove that there are no defects
-Exhaustive testing is impossible
    instead of testing everything, focus on applying test techniques, test case prioritization, and risk-based testing
-Early testing saves time and money
    undetected defects are more expensive and time consuming when discovered during the later stage of the SDLC or other SDLC models
-Defects cluster together
    Pareto principle applies where a small number of system components usually contains most of the defects discovered or are responsible for most of the operational failure; predicted defect clusters and actual defect clusters observed during testing are an important input for risk-based testing
-Tests wear out
    when the same tests are repeated, the chances of detecting new defects are lowered. existing tests and test data may need to be modified and new tests may need to be written
-Testing is context dependent
    there is no single universal approach to testing
-Absence-of-defects fallacy
    a software/product with little to no defects isn't considered a great product even when all requirements are completely verified unless its has been validated to match stakeholder's or user's needs

Summarize the different test activities and tasks (K2)
Each development activity should have a corresponding testing activity to ensure quality control and to adhere to early testing principle. Each testing activity undergoes below test processes depending SDLC stage:
    -Test Planning is the activity of establishing or updating a test plan according to the project. A test plan includes the test schedule, risk register, enter and exit criteria, test team, test objectives, milestones, tools, best approaches to achieve test objectives, standards/templates of documentation
    -Test Monitoring and Control
        Test Monitoring is the activity of ongoing checking of all test activities and identifying variances between the actual progress against the planned/expected progress
        Test Control is the activity of applying corrective actions when the actual progress deviates from the planned/expected progress to get the project back on track
    -Test Analysis is the activity of analyzing the test basis to identify test conditions
    -Test Design is the activity of elaborating test conditions to derive into test cases
    -Test Implementation is the activity of preparing the testware for test execution based on test analysis and design where test cases are organized into test procedures and then assembled into test suites
    -Test Execution is the activity of running tests in accordance with the test execution schedule and comparing the actual result against expected result
    -Test Completion is an activity that usually occurs at project milestones such as release, end of iteration, or test level completion where the testware are made available for later use, test activities are analyzed to identify lessons learned and improvements, and communicate the results to relevant stakeholders

Explain the impact of context on the test process (K2)
As one of the testing principle: Testing is context dependent, there is no single universal approach to testing. The way test process is carried out should consider contextual factors like:
    -Stakeholders (needs, expectations, requirements, willingness to cooperate)
    -Team members (skills, knowledge, level of experience, availability, training needs)
    -Business domain (criticality of the test object, identified risks, market needs, specific legal regulations)
    -Technical factors (type of software, product architecture, technology used)
    -Project constraints (scope, time, budget, resources)
    -Organizational factors (organizational structure, existing policies, practices used)
    -SDLC (engineering practices, development methods)
    -Tools (availability, usability, compliance)

Differentiate the testware that supports the test acitvities (K2)
Testware is/are the work product produced during the test process for use, during:
    -Test Planning: Test plan
    -Test Monitoring and Control: Test progress report, Documentation of control directives, Risk information
    -Test Analysis: Test conditions / Test scenarios, Defect reports(in the Test basis)
    -Test Design: Test cases, Test charters, Coverage items, Test data requirements, Test environment requirements
    -Test Implementation: Test procedures, Test suites, Automated test scripts, Test data, Test execution schedule, Test environment elements(stubs, drivers, simulators, service virtualizations)
    -Test Execution: Test logs, Defect reports
    -Test Completion: Test completion report, Action items for improvements, Documented lessons learned, Change requests

Explain the value of maintaining traceability (K2)
Establishing and maintaining traceability throughout the test process between the test basis elements, testware associated with these elements (test conditions, risks, test cases), test results, and detected defects implements effective test monitoring and control. Accurate traceability supports coverage evaluation, determine the impact of changes, facilitates test audits, helps meet IT governance criteria

Compare the different roles in testing (K2)
Test Management Role (Test manager / lead) takes overall responsibility for the test process, test team, and the leadership of the test activities like Test planning, Test monitoring and control, Test completion
Tester Role (Software tester) takes overall responsibility for the engineering/technical aspect of testing activities like Test analysis, Test design, Test implementation, Test execution
Although, it is also possible for one person to take the responsibility of the test management and tester role

Give examples of the generic skills required for testing (K2)
-Testing knowledge like using test techniques
-Thoroughness, carefulness, curiosity, attention to detail, being methodical to identify defects especially the ones that are difficult to find
-Good communication skills, active listening, and being a team player to interact effectively and be understood by stakeholders
-Analytical thinking, critical thinking, and creativity to increase effectiveness of testing
-Technical knowledge like using appropriate test tools
-Domain knowledge to be able to understand and communicate to end users/business representatives

Recall the advantages of the whole team approach (K1)
-Everyone is responsible for quality since any team member with the necessary knowledge and skills can perform any task
-Team members share the same workspace which improves team dynamics, enhances communication and collaboration within the team, and creates synergy
-Testers work closely with other team members to ensure that the desired quality levels are achieved by transferring testing knowledge and influence the development of the product

Distinguish the benefits and drawbacks of independence of testing (K2)
The main benefit is that independent testers are likely to recognize different kinds of failures and defects compared to developers because of different backgrounds, technical perspectives, and biases.
The main drawback is that independent testers may be isolated from the development team which leads to lack of collaboration, communication problems, an adversarial relationship with the development team, and may be seen as bottlenecks or blamed for delays in release.
