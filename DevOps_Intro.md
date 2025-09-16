Day1: 
What is DevOps?
    SCM -
    Code Integration 
    CD - Jenkins
What is Azure DevOps?
    Azure Repo 
    Azure Pipelines
    Azure Board
    Azure Test Plan
    Azure Artifacts


DevOps?


    1. Traditional 
        
        a. Separate Team
            Planning
            Designing
            Coding  -   
            Testing

            Integrate
            Testing
            Deploy
            Monitor
            Feedback
        b. Manual Process
            Build
            Deployment 
            Testing 
        c. Slow Release Cycles
            Module -> Deliver -> Feedback -> 
        d. Limited Collaboration
            Dev - 
            Test - 
            Operation -


Agile.
    Speed 
    Delivery -> Interative Development (Small objects)
    1 - 4 weeks -> workable object
    Increasing customer interaction -> feedback -> fix bug 
    Respond to changes quickly
    People, Collaboration, adapt

    1. Scrum -> daily standup, backlog management
        2 weeks
        sprint
        10 developers
        10 objects
        Scrum - ensure 10 developers are on track
        sprint 
            10 developers developed 10 objects, showcase to customer - feedback - if negative push product back to backlog
            if the object is accepted, move to next sprint
            object sent to integration team

            10 object -> integration team -> integrated object -> testing team -> tested object -> deployment team -> deployed object -> customer feedback

    2. Kanban -> visualize workflow, limit work in progress, maximize efficiency



Devops = Culture + Practices + Tools

    1. Culture
        Collaboration
        Shared Responsibility
        Continuous Improvement
    2. Practices
        Continuous Integration (CI)
        Continuous Delivery (CD)
        Infrastructure as Code (IaC)
        Monitoring and Logging
    3. Tools
        Version Control - Git, Azure Repo
        CI/CD - Jenkins, Azure Pipelines
        Configuration Management - Ansible, Puppet
        Containerization - Docker, Kubernetes
        Monitoring - Prometheus, Grafana

i. Achieve collaboration between Dev and Ops team
ii. automate repetitive tasks (build, test, deploy)
iii. CI, CD , CD
iv. Monitor application and infrastructure performance

mindset + process + automation



phases in software development lifecycle
    1. Plan         - document  
    2. Develop      - file
    3. Build        - compile
    4. Test         - validate
    5. Release      - distribute
    6. Deploy       - install
    7. Operate      - monitor
    8. Monitor      - observe
    9. Feedback     - improve

DevOps Tools


SCM - Source Control Management
CVCS - Centralized Version Control System   - SVN, TFS
DVCS - Distributed Version Control System   - Git, Mercurial, Bazaar
Track the changes to code
    1. Git
        a. Local Repo
        b. Staging Area
        c. Remote Repo
        d. Branching and Merging
            i. Branching - create a copy of code to work on new feature/bug fix without affecting main codebase
            ii. Merging - integrate changes from one branch to another

    2. Azure Repo
        a. Cloud-based Git repository
        b. Integration with Azure DevOps services
        c. Collaboration features - pull requests, code reviews, branch policies