# Final Review

Review slides, notes, and workshop materials. This is a comprehensive exam over the entire semester.
Exam will be closed book. However, as a good study practice, it is suggested you prepare a one page summary of key definitions and terms in order to help you learn and practice the material.

The following is an example exam.

### Multiple Choice

1) Which of the following is a component of the Blackboard pattern?  (3 points)

- A) routine
- B) sink
- C) knowledge source
- D) repository
- E) None of the above

2) Which of the following is *NOT* a package manager?  (3 points)

- A) maven
- B) grunt
- C) choco
- D) npm
- E) bower

3) Which best describes an issue *not* related to configuration management? (3 points)

- A) Estimate risk of allowing a customer to configure a feature.
- B) Audits: Discovery request on changes made to system.
- C) A customer wants a bug fix to software version, which was released 2 years ago.
- D) Works on my machine, not the customers.
- E) None of the above

4) Which of the following is *not* a motivation for agile processes?  (3 points)

- A) Individuals and interactions over processes and tools.
- B) Comprehensive documentation over working software.
- C) Customer collaboration over contract negotiation.
- D) Responding to change over following a plan.
- E) None of the above.

5) What HTTP verb would be most appropriate for editing an entity in a RESTful service?

* A) PUSH.
* B) PATCH.
* C) PUT.
* D) B or C
* E) None of the Above

6) Which of the following best describes encapsulation?

* A) Measure of interdependence between two objects
* B) When methods declared in one class use methods or attributes of the other class 
* C) Number of direct descendants (subclasses) for each class
* D) Measure of the proportion of attributes that are “invisible” from other classes or objects
* E) Degree to which the tasks performed by a single module are functionally related

7) Which deployment practice definition best describes a dark launch?

* A) Release software without any user-facing elements exposed, use flags to turn on in production.
* B) Start with two identical instances of infrastructure. Deploy beta version on one, stable on other. Switch when ready.
* C) Stop traffic to node, upgrade node, reroute traffic back, upgrade next node.
* D) Sample a small amount of traffic, eventually route more traffic if stable.
* E) B or D


### Short Answer

1. Describe the principle of "Cost of Change is Dead" 
<br/>
<br/>
<br/>

2. Explain the difference between docker and ansible.
<br/>
<br/>
<br/>

3. Describe the principle of "Rule of 3".
<br/>
<br/>
<br/>

### Scenarios

1. A company wants to increase the responsibility of their development team to include handling testing, staging, and production. They want to reduce communication barriers and team silos separate groups imposes. What team model might be appropriate? 
<br/>
<br/>

2. A company has recently adopted continuous deployment of their product, but has started receiving complaints from their customer that new features are coming too fast and running too slow. What practice would you recommend they adopt to prevent these problems while allowing continuous deployment?
<br/>
<br/>

<p style="page-break-after:always;"></p>
### Implementation

1) Measure the branch coverage of a code snippet. (10 points)

**Test suite**:

* `weird(0, 0, 0, "strictly", [0,0])`
* `weird(88, 42, 42, "stricter", [0,0])`

```Javascript
function weird(x,y,z, mode, results)
{
      if( x > 100 || y > 70 )
      {
          z = 33;
          results[0] = getData().data.server().first.name;
      }    
      else if( z == 0 && y < 0)
      {
          if( mode == "strictly" )
          {
              return 0;
          }
      }
      else if( z < 42 )
      {
          if( mode != "stricter" )
          {
              results[1] = getData().cachedResults.first.name;
              return y = z / x;
          }
      }
      return 1;
  }
```
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>


2) Write a parser using a simple visitor pattern. 

*You can assume a basic visitor function already exists and provide your own tokens and AST structure you assume exist (feasibly parsed).*

A) Count the number of branches in a function. (10 points)

- What is number of branches in the above weird function?
- Parser implementation.

<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>

B) Count the number of conditions in a function. (10 points)

- What is number of conditions in the above weird function?
- Parser implementation.

<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>

### Analyze

1) Two developers are debating about what type of configuration management to use in their organization: traditional or modern. Provide one advantage of traditional CM and one limitation. Provide one advantage of modern CM and one limitation.
br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>


2) Compare and contrast using mocking versus canary releasing. Describe their impact on testing.

<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>

### Design and Architecture

1) How might you create a microservice architecture for your bot, running in the cloud? *Focus on creating a well annotated diagram that illustrates essential components, paragraphs of just text will not be given credit.*

<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
