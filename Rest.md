# Collect REST API

The Collect REST API lets you create, manipulate and retrieve data related to your activities, collectors, members and transactions. It also gives you access to different types of statistics data. You can use the API to build your own services or integrate it with your existing systems or services. The API can be used as an alternative to, or in combination with, the existing Intelecom Collect web pages.

The API uses [Auth0](https://auth0.com/) for authentication and you will need to set up an [account](Authentication.md).

The Collect API supports the [Open API Initiative](https://openapis.org) and implements the [Swagger 2.0 specification](http://swagger.io/). You can access the swagger definitions as [JSON here](https://collectapi.intele.com/collect-api/rs/swagger.json) or as [YAML here](https://collectapi.intele.com/collect-api/rs/swagger.yaml). There are many [integration tools available](http://swagger.io/open-source-integrations/) that support this specification.

You check out the documentation for all [the API operations here](https://intelecom.github.io/collect/swagger-ui) or read on for an overview.

### Definitions
<table>
<tr><th>Term</th><th>Description</th></tr>	
<tr><td>Service</td><td>The service ID identifies your account with the Intelecom platform. A service can have one or several activities.</td></tr>	
<tr><td>Activity</td><td>An activity might be a SMS service for donations, a web donation form or a SMS service for recruiting, billing and communicating with a member network.</td></tr>	
<tr><td>Donator</td><td>An end user donating money to an activity.</td></tr>	
<tr><td>Collector</td><td>A collector is a person that collects money on your behalf. A collector can be part of one or more activities.</td></tr>	
<tr><td>Member</td><td>A user joining an activity as a member. For example for recurring donations or starting a NGO membership</td></tr>
</table>


## REST Operations
Check out the [swagger-ui documentation](https://intelecom.github.io/collect/swagger-ui) or import the swagger [JSON](https://collectapi.intele.com/collect-api/rs/swagger.json) or [YAML](https://collectapi.intele.com/collect-api/rs/swagger.yaml) definitions into [an integration tool](http://swagger.io/open-source-integrations/) or directly into [Postman](https://www.getpostman.com/).

### Activity Resource
[The Activity Resource](http://intelecom.github.io/collect/swagger-ui/#/Activity) has several operations for manipulating activities.

### Collector Resource
[The Collector resource](http://intelecom.github.io/collect/swagger-ui/#/Collector) has operations for manipulating collectors. 

### Member Resource
[The Collector resource](http://intelecom.github.io/collect/swagger-ui/#/Member) has operations for manipulating members.

### Transaction Resource
[The Transaction Resource](http://intelecom.github.io/collect/swagger-ui/#/Transaction) gives access to transaction data.

### Statistics Resource
[The Statistics Resource](http://intelecom.github.io/collect/swagger-ui/#/Statistics) has operations to access several types of statistics data for transactions and turnover (revenues).
