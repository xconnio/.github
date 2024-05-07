# XConn project

**Ecosystem for real-time apps**

Structure:
 * wampproto-{lang}
 * xconn-{lang}

The projects that are prefixed **wampproto-\*** are implementations of the WAMP protocol in each programming language. They are supposed to be the last implementations of WAMP in each programming language. Anyone building their client library or router should depend on these and potentially save weeks of work.

The **xconn-\*** prefixed projects are full client/router implementations of the WAMP protocol and show how to use the wampproto libs. These projects aim for developer productivity as the top most priority, hence include router implementations as well so that the "getting started" becomes frictionless.

We will continuously update these libraries to make sure they are comformat to the WAMP protocol.
