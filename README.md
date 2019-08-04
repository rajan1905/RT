# Assignment

<li>Import project using Maven pom.xml</li>
<li>H2 in-memory is used to perform transactions</li>

<li> Transactions entity is used to depict an actual transaction in  system </li>
<li> <i> Not much focus is given on optimizing Hibernate connections </i> </li>
<li> Two Repositories - AccountRepository and TransactionRepository are used to perform operations on tables.</li>
<li> Havn't complicated the assignment by doing cross-border transactions. Although, they can be easily integrated in the current design (by using base currency for transactions) as while  creating transaction features can be easily plugged in and out. Same goes for rules on Transactions. A new rule can be easily added to <b> TransactionRules </b> class and could be easily tested</li> 
<li> Been using Spring JPA for a long time, so code can be not up to the mark for Hibernate implementation </li>
<li> Not done so much documentation as code is divided into very small chunks which are easy to understand as they only do sinle things instead of performing multiple operations </li>
