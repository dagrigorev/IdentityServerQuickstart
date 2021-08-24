# Sample Identity Server configuration and api securing

Contains 3 projects:

	1. Authorization server (so, this is main authentication server...)
	2. Api (sample web api project, that secured by authentication server)
	3. Client (sample api user)

Working flow looks like this:
	Client -> Api -> AuthorizationServer -> Api -> Client

just examples for simply configuring and securing your api by IdentityServer
... maybe also just for increasing my experience in this super strange secured cases (that i didnt get for a long time until this time)