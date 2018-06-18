 
# Galore    [![Gitter Join the chat](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/kognifai/Lobby)

Welcome to Galore documentation!

In this section, we talk about:

[Galore_Overview](#Overview)

[Galore Asset Model](https://github.com/kognifai/Galore/blob/master/SDK-documentation/TQL.md)

[Streams](https://github.com/kognifai/Galore/blob/master/SDK-documentation/streams.md)

[TQL Syntax](https://github.com/kognifai/Galore/blob/master/SDK-documentation/TQL%20Syntax.md)

[Node Selector](https://github.com/kognifai/Galore/blob/master/SDK-documentation/Node%20Selector.md)
 
[Pipeline Operations](https://github.com/kognifai/Galore/blob/master/SDK-documentation/Pipeline%20Operations.md)

[Case Study](https://github.com/kognifai/Galore/blob/master/SDK-documentation/casestudy.md)


### Overview

Many Kognifai applications leverage Galore capabilities for storage because it is one of the storage system. The major Components of the Galore system are:

  - [Asset modelling](https://github.com/kognifai/Galore/blob/master/SDK-documentation/TQL.md)
  
  - Vector streams and time series.

    -   StateEvent streams and Alarms&Events.

    -   Sample set streams. See [Sample set event stream](https://github.com/kognifai/Galore/blob/master/SDK-documentation/streams.md)           for more details.
    
-   A query service that allows simple and complex (historical and real-time combined) queries using the TQL functional query language.

-   A calculation service that allows simple and complex creation of new streams (with  history stored) using the TQL functional query language.

    These services are accessible by end user applications and other services through REST APIs, Signal R and WCF services.

-   Client libraries (C\# and javascript/typescript) can be leveraged by end user applications.

-   General Tools for configuring the system.

-   General Tools for exploring data, stored by the system.


### Components of Galore system
Here are the quick links to access the compoents of Galore system.

| Topic | Link | Description | 
|------|----------|----------|
 Galore Asset Model | [Galore Asset Model](https://github.com/kognifai/Galore/blob/master/SDK-documentation/TQL.md)|The Galore Asset Model is a Directed Acyclic Graph (DAG).|
Streams|[Streams](https://github.com/kognifai/Galore/blob/master/SDK-documentation/streams.md)|Galore uses a stream abstraction to allow access to both real-time and historical data.|
 TQL Syntax| [TQL Syntax](https://github.com/kognifai/Galore/blob/master/SDK-documentation/TQL%20Syntax.md)|TQL defines a functional pipeline. |
 Node Selector | [Node Selector](https://github.com/kognifai/Galore/blob/master/SDK-documentation/Node%20Selector.md)|The node selector is an expression for selecting one or more nodes from the Galore. |
 Pipeline Operations | [Pipeline Operations](https://github.com/kognifai/Galore/blob/master/SDK-documentation/Pipeline%20Operations.md)| Operations that can be performed in pipeline are described in this topic.

### Case Study
In order to get a better overview of the Galore capabilities in a simplified case study, click [here](https://github.com/kognifai/Galore/blob/master/SDK-documentation/casestudy.md).

### License
Read the copyright information and terms and conditions for Usage and Development of the software [here](https://github.com/kognifai/Kognifai/blob/master/License.md#copyright--year-kongsberg-digital-as).

