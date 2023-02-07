When 2 or more teams decide to share some subset of the domain model then this is called a [[Shared Kernel|shared kernel]]. The shared code has special status and should not be changed without consulting the other team that shares the code with you. Whenever changes are made to the [[Shared Kernel|shared kernel]] tests need to be run on both teams. It is crucial to limit the scope of the [[Shared Kernel|shared kernel]] in order to make it as small as possible.

Oftentimes the [[Shared Kernel|shared kernel]] would be the [[Core Domain|core domain]], some set of [[Generic Subdomain|generic subdomains]] or both.

A shared kernel is a good option when it is more cost-effective to share code than create translation layers between [[Bounded Context|bounded contexts]].