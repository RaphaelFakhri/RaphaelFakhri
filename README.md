Forward deployed engineer in Beirut. I build LLM agents and durable workflows, mostly in Python and C#, and I spend a fair amount of time in other people's codebases fixing what I run into.

MSc in Computer Science, AUB.

### Working on

- Customer-facing LLM agents and the integration work around them
- Durable workflows: [Temporal](https://github.com/RaphaelFakhri/shipment-triage), retries, human approval steps, evaluation gates in CI
- Small fixes to the libraries I depend on

### Open source

Merged contributions, biggest projects first.

**[tailscale/tailscale](https://github.com/tailscale/tailscale)**
- [#21533](https://github.com/tailscale/tailscale/pull/21533) util/cmpver: don't panic on numbers that overflow a uint64

**[livekit](https://github.com/livekit)**
- [livekit#4922](https://github.com/livekit/livekit/pull/4922) SFU: fix data stats bitrate and duration units
- [livekit#4923](https://github.com/livekit/livekit/pull/4923) Measure data blob keys by their content
- [agents#7523](https://github.com/livekit/agents/pull/7523) Gladia STT: store region in `update_options`
- [client-sdk-flutter#1226](https://github.com/livekit/client-sdk-flutter/pull/1226) Route publisher negotiation errors to reconnect instead of leaking them
- [egress#1416](https://github.com/livekit/egress/pull/1416) Use UTC for the `{utc}` filename template

**[supabase](https://github.com/supabase)**
- [storage#1459](https://github.com/supabase/storage/pull/1459) S3: return an empty page for `max-keys=0` in list objects
- [postgres-language-server#818](https://github.com/supabase-community/postgres-language-server/pull/818) Pretty-print: separate a prefix operator from an operand that starts with an operator
- [postgres-language-server#817](https://github.com/supabase-community/postgres-language-server/pull/817) Pretty-print: keep `bpchar` and `"char"` types and quote `VALID UNTIL`
- [supabase-flutter#1898](https://github.com/supabase/supabase-flutter/pull/1898) Don't crash on a deep link with malformed percent-encoding

**[nodejs/undici](https://github.com/nodejs/undici)**
- [#5721](https://github.com/nodejs/undici/pull/5721) Expose `PendingInterceptor` types on the MockAgent namespace
- [#5723](https://github.com/nodejs/undici/pull/5723) Restore /xhr to the WPT filter

**[Temporal SDKs](https://github.com/temporalio)**, 5 merged across 4 languages
- [sdk-go#2710](https://github.com/temporalio/sdk-go/pull/2710) Don't modify the caller's retry policy in `WithLocalActivityOptions`
- [sdk-python#1900](https://github.com/temporalio/sdk-python/pull/1900) Decode enums that mix in `str` or `int`, and int enum dict keys
- [sdk-dotnet#923](https://github.com/temporalio/sdk-dotnet/pull/923) Let appended `DiagnosticSource` metric tags override existing keys
- [sdk-dotnet#924](https://github.com/temporalio/sdk-dotnet/pull/924) Interpolate the method name in the dynamic activity name error
- [sdk-typescript#2461](https://github.com/temporalio/sdk-typescript/pull/2461) Reject values without a JSON representation in `JsonPayloadConverter`

**[versatica/mediasoup](https://github.com/versatica/mediasoup)** and **[mediasoup-client](https://github.com/versatica/mediasoup-client)**
- [mediasoup#1953](https://github.com/versatica/mediasoup/pull/1953) Reject an RTX codec whose `apt` doesn't point to a media codec, instead of panicking in Rust
- [mediasoup#1955](https://github.com/versatica/mediasoup/pull/1955) Worker: fix `RtxEncode()` writing 2 bytes beyond the end of the packet
- [mediasoup#1952](https://github.com/versatica/mediasoup/pull/1952) Node: fix `pipeToRouter()` failing forever after a failed pair creation
- [mediasoup#1950](https://github.com/versatica/mediasoup/pull/1950) Rust: fix `ScalabilityMode::ksvc()` for `L2T1_KEY`
- [mediasoup-client#389](https://github.com/versatica/mediasoup-client/pull/389) Stop the track if `produce()` is called on a closed Transport
- [mediasoup-client#388](https://github.com/versatica/mediasoup-client/pull/388) Treat `maxRetransmits: 0` and `maxPacketLifeTime: 0` as given in `produceData()`
- [mediasoup-client#386](https://github.com/versatica/mediasoup-client/pull/386) Close the DataChannel if `produceData()` fails
- [mediasoup-client#385](https://github.com/versatica/mediasoup-client/pull/385) Reject `setMaxSpatialLayer()` if the handler fails

**[domaindrivendev/Swashbuckle.AspNetCore](https://github.com/domaindrivendev/Swashbuckle.AspNetCore)**, 9 merged, including
- [#4131](https://github.com/domaindrivendev/Swashbuckle.AspNetCore/pull/4131) Resolve enum contracts against the underlying type under source generation
- [#4116](https://github.com/domaindrivendev/Swashbuckle.AspNetCore/pull/4116) Use Minimal APIs JSON options when MVC isn't registered
- [#4130](https://github.com/domaindrivendev/Swashbuckle.AspNetCore/pull/4130) Drop the regex route constraint from the default Swagger route
- [#4129](https://github.com/domaindrivendev/Swashbuckle.AspNetCore/pull/4129) Keep a property's own summary when comments come from several XML files

**[fluentmigrator/fluentmigrator](https://github.com/fluentmigrator/fluentmigrator)**
- [#2405](https://github.com/fluentmigrator/fluentmigrator/pull/2405) Report the version table creation from `LoadVersionInfoIfRequired`
- [#2404](https://github.com/fluentmigrator/fluentmigrator/pull/2404) Don't carry index creation options into the reversed delete
- [#2401](https://github.com/fluentmigrator/fluentmigrator/pull/2401) Document how `$(name)` renders `DateTime` and `DateTimeOffset` values

**[Resend SDKs](https://github.com/resend)**, one fix in each of five languages
- [resend-java#150](https://github.com/resend/resend-java/pull/150) Copy list and map arguments in the `CreateEmailOptions` builder
- [resend-node#1117](https://github.com/resend/resend-node/pull/1117) Forward raw email bytes without re-decoding them as UTF-8
- [resend-python#290](https://github.com/resend/resend-python/pull/290) Raise `ValueError` for a non-ASCII signature in `Webhooks.verify`
- [resend-go#166](https://github.com/resend/resend-go/pull/166) Keep the base URL path prefix in broadcast requests
- [resend-rust#116](https://github.com/resend/resend-rust/pull/116) Keep the base URL path prefix when building request URLs

**[Deepgram SDKs](https://github.com/deepgram)**
- [deepgram-rust-sdk#186](https://github.com/deepgram/deepgram-rust-sdk/pull/186) Keep the streaming worker running when the idle timer fires without keep-alive
- [deepgram-js-sdk#563](https://github.com/deepgram/deepgram-js-sdk/pull/563) Keep reconnecting after a WebSocket connection error
- [deepgram-js-sdk#562](https://github.com/deepgram/deepgram-js-sdk/pull/562) Reset the custom transport retry count after a successful open
- [deepgram-dotnet-sdk#441](https://github.com/deepgram/deepgram-dotnet-sdk/pull/441) Allow `Connect` without a model on the v2 WebSocket client

**Also merged in** [Cloudflare RealtimeKit UI](https://github.com/cloudflare/realtimekit-ui/pulls?q=is%3Apr+author%3ARaphaelFakhri+is%3Amerged) (3), [Clerk](https://github.com/clerk/javascript/pull/10035), [Inngest Go](https://github.com/inngest/inngestgo/pull/255), [Ably Java](https://github.com/ably/ably-pubsub-java/pull/1248), [Braintrust Python SDK](https://github.com/braintrustdata/braintrust-sdk-python/pulls?q=is%3Apr+author%3ARaphaelFakhri+is%3Amerged) (3), [Braintrust JS SDK](https://github.com/braintrustdata/braintrust-sdk-javascript/pulls?q=is%3Apr+author%3ARaphaelFakhri+is%3Amerged) (2), [GetStream stream-py](https://github.com/GetStream/stream-py/pull/298) and [media-chrome](https://github.com/muxinc/media-chrome/pull/1321).

[All merged pull requests](https://github.com/pulls?q=is%3Apr+author%3ARaphaelFakhri+is%3Amerged+-user%3ARaphaelFakhri+-user%3Arivergtm)

### Contact

[fakhriraphael@gmail.com](mailto:fakhriraphael@gmail.com) · [raphaelfakhri.com](https://raphaelfakhri.com)
