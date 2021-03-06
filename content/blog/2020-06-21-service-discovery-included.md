---
title: Service Discovery
author: Mark Wylde
authorURL: http://twitter.com/markiswylde
---

This release combines the recent work on implementing service discovery into each other servers, managers and gateways.

The responsibilities of this project are now to bring up 1 instances of each rqlite, server, manager and gateway.

Using this release, you can start bitabase:

```bash
bitabase --secret some-secret
```

Joining two instances is possible too:

```bash
bitabase --secret some-secret --rqlite-join=http://somehost:4001
```

This is by no means a stable, production ready release, so just for testing right now!

[More Information at GitHub](https://github.com/bitabase/bitabase/releases/tag/v1.5.0)
