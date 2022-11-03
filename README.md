# IT-University of Copenhagen (Course overview)

## Information
I'm currently studying for a [**Master's Degree in Software Design**](https://en.itu.dk/Programmes/MSc-Programmes/Software-Design#specialisations) at, as well as working for, the [**IT University of Copenhagen**](http://en.itu.dk). 

My research topics / specialisations at ITU are divided into two main areas: **Technical Interaction Design** and **Software Development & Technology**. 

A significant amount of the individual *course assignments, tasks and projects* I've worked on during my studies can be found in the [list of ITU courses](https://github.com/stars/sebastianromano/lists/itu) or by searching for the `IT University of Copenhagen` keyword in [repositories](https://github.com/sebastianromano?tab=repositories&q=IT+University+of+Copenhagen&type=&language=&sort=).


| **FUN**     | [[Introductory Programming\|IP]] | [[Software Engineering\|SE]]          | [[Discrete Mathematics\|DM]]          | [[Introduction to Database Systems\|IDBS]] | [[Algorithms and Data Structures\|ADS]] | [[How to make (almost) anything\|MAKE]] |
|:----------- |:-------------------------------- |:------------------------------------- |:------------------------------------- |:------------------------------------------ |:--------------------------------------- |:--------------------------------------- |
| **SPECIAL** | [[Mobile App Development\|MAD]]  | [[Applied Information Security\|AIS]] | [[Technical Interaction Design\|TID]] | [[Functional Programming\|FP]]             |                                         |                                         |
| **PROJECT** | [[Research project\|RESEARCH]]   | [[Master thesis\|MASTER]]             |                                       |                                            |                                         |                                         |

## Course overview
| Key          | Fundamentals                     | Technical Interaction Design | Software Development and Technology |
| ------------ | -------------------------------- | ---------------------------- | ----------------------------------- |
| ==IP==       | Introductory Programming         |                              |                                     |
| ==SE==       | Software Engineering             |                              |                                     |
| ==DM==       | Discrete Mathematics             |                              |                                     |
| ==FP==       |                                  |                              | Functional Programming              |
| ==IDBS==     | Introduction to Database Systems |                              |                                     |
| ==ADS==      | Algorithms and Data Structures   |                              |                                     |
| ==MAKE==     | How to make (almost) anything    |                              |                                     |
| ==MAD==      |                                  | Mobile App Development       |                                     |
| ==AIS==      |                                  | Applied Information Security |                                     |
| ==TID==      |                                  | Technical Interaction Design |                                     |
| ==RESEARCH== | Research Project                 |                              |                                     |
| ==MASTER==   | Master Thesis                    |                              |                                     |

## Visual overview
```mermaid
%%{init: { 'logLevel': 'debug', 'theme': 'base', 'gitGraph': {'showBranches': true, 'showCommitLabel':true,'mainBranchName': 'Fundamentals'}} }%%
gitGraph
  checkout Fundamentals
  commit id: "Introductory Programming"
  commit id: "Software Engineering"
  commit id: "Discrete Mathematics"
<!--ID: 1665933544674-->


  branch Software_Development_and_Technology
  commit id: "Functional Programming "

  checkout Fundamentals
  commit id: "Introduction to Database Systems"
  commit id: "Algorithms and Data Structures"

  
  branch Technical_Interaction_Design
  commit id: "Mobile App Development"
  commit id: "Applied Information Security"
  commit id: "Technical Interaction Design"

  checkout Fundamentals
  commit id: "How to make (almost) anything"
  commit id: "Research project"
  commit id: "Master thesis"

  checkout Software_Development_and_Technology
  merge Technical_Interaction_Design
  checkout Fundamentals
  merge Software_Development_and_Technology tag: "Sail to remote island ⛵️🏝🍹"
```