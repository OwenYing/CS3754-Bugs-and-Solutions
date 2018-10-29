# CS3754-Bugs-and-Solutions

### Bugs and Corresponding Solutions
1. Universal Solution
```java
   Always remember to Clean the cache when meeting problems.
```

2. Clean and Build --> Run --> Failed : <br/>
```
   Click the Run button again.
```

3. Windows install mysql permission denied --> Failed :
```
   Run program as administrator.
```

4. Windows install mysql case sensitive --> Failed :
```
   1. Restart the service of MySQL
   2. Command line:  init-file = init.ini
```
   
5. Windows table not found problem :
```
   Case sensitive problem.
```

6. Error Message : Severe:   Exception while preparing the app : Could not resolve a persistence unit corresponding to the persistence-context-ref-name [edu.vt.FacadeBeans.UserFacade/em] in the scope of the module called [BevQ-Ying]. Please verify your application.
```
1. Check you persistence.xml : to see what follows the name, here mine is "BevQPU"
2. Check all your Facades under package "edu.vt.FacadeBeans" : make sure @PersistenceContext(unitName = "BevQPU") has the same name as above
```
   
   
### Calendar
#### Week 1 : Aug 13 -- Aug 20
1. A week before Class Starts.
2. Dr. Balci publishes course website: [CS 3754, Instructor : Dr. Balci](https://manta.cs.vt.edu/cs3754/)

#### Week 2 : Aug 21 -- Aug 27
1. Introduction
2. Install Netbeans + Glassfish

#### Week 3 : Aug 28 -- Aug 
1. Autoloan

---
###### Always pull the newest version before start coding. [Git cheatsheet](https://owenying.github.io/html/blog/ToBeAEngineerFromScratch/Diary.html)
###### [Github Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

