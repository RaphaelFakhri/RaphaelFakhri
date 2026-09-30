Forward deployed engineer in Beirut. I build LLM agents and durable workflows, mostly in Python and C#, and I spend a fair amount of time in other people's codebases fixing what I run into.

MSc in Computer Science, AUB.

### Working on

- Customer-facing LLM agents and the integration work around them
- Durable workflows: [Temporal](https://github.com/RaphaelFakhri/shipment-triage), retries, human approval steps, evaluation gates in CI
- Small fixes to the libraries I depend on

### Open source

Merged contributions, newest first.

**[versatica/mediasoup](https://github.com/versatica/mediasoup)** and **[mediasoup-client](https://github.com/versatica/mediasoup-client)**
- [mediasoup#1955](https://github.com/versatica/mediasoup/pull/1955) Worker: fix `RtxEncode()` writing 2 bytes beyond the end of the packet
- [mediasoup#1952](https://github.com/versatica/mediasoup/pull/1952) Node: fix `pipeToRouter()` failing forever after a failed pair creation
- [mediasoup#1950](https://github.com/versatica/mediasoup/pull/1950) Rust: fix `ScalabilityMode::ksvc()` for `L2T1_KEY`
- [mediasoup-client#389](https://github.com/versatica/mediasoup-client/pull/389) Stop the track if `produce()` is called on a closed Transport
- [mediasoup-client#388](https://github.com/versatica/mediasoup-client/pull/388) Treat `maxRetransmits: 0` and `maxPacketLifeTime: 0` as given in `produceData()`
- [mediasoup-client#386](https://github.com/versatica/mediasoup-client/pull/386) Close the DataChannel if `produceData()` fails
- [mediasoup-client#385](https://github.com/versatica/mediasoup-client/pull/385) Reject `setMaxSpatialLayer()` if the handler fails

**[livekit](https://github.com/livekit)**
- [livekit#4922](https://github.com/livekit/livekit/pull/4922) SFU: fix data stats bitrate and duration units
- [livekit#4923](https://github.com/livekit/livekit/pull/4923) Measure data blob keys by their content
- [agents#7523](https://github.com/livekit/agents/pull/7523) Gladia STT: store region in `update_options`

**[domaindrivendev/Swashbuckle.AspNetCore](https://github.com/domaindrivendev/Swashbuckle.AspNetCore)**, 7 merged, including
- [#4130](https://github.com/domaindrivendev/Swashbuckle.AspNetCore/pull/4130) Drop the regex route constraint from the default Swagger route
- [#4129](https://github.com/domaindrivendev/Swashbuckle.AspNetCore/pull/4129) Keep a property's own summary when comments come from several XML files
- [#4128](https://github.com/domaindrivendev/Swashbuckle.AspNetCore/pull/4128) Emit form encoding for properties of a complex form parameter

**[nodejs/undici](https://github.com/nodejs/undici)**
- [#5721](https://github.com/nodejs/undici/pull/5721) Expose `PendingInterceptor` types on the MockAgent namespace
- [#5723](https://github.com/nodejs/undici/pull/5723) Restore /xhr to the WPT filter

**Also merged in** [Braintrust Python SDK](https://github.com/braintrustdata/braintrust-sdk-python/pulls?q=is%3Apr+author%3ARaphaelFakhri+is%3Amerged) (3), [Braintrust JS SDK](https://github.com/braintrustdata/braintrust-sdk-javascript/pull/2538), [supabase-flutter](https://github.com/supabase/supabase-flutter/pull/1898), [media-chrome](https://github.com/muxinc/media-chrome/pull/1321) and [Cloudflare RealtimeKit UI](https://github.com/cloudflare/realtimekit-ui/pull/177).

[All merged pull requests](https://github.com/pulls?q=is%3Apr+author%3ARaphaelFakhri+is%3Amerged+-user%3ARaphaelFakhri+-user%3Arivergtm)

### Contact

[fakhriraphael@gmail.com](mailto:fakhriraphael@gmail.com) · [raphaelfakhri.com](https://raphaelfakhri.com)
