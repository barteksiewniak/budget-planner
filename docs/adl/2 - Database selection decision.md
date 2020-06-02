Context.
  We have to decide what database we use for the persistance layer.

Decision.
  Choice: H2.
  Status: accepted.
  Description: for the speed of prototyping we choosed in memory db H2, at the latest development stage we switch to relational db, 
               which fit very well to that kind of system ( no big data, relational links between objects - NoSQL doesn't fit here )
  Time to make the decision: 01.06.2020
  
Consequences.
  Need to swap and configure development database in the next development steps.
  
Other options.
  Any relational.
