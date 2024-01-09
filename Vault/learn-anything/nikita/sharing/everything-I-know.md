# Everything I know

Page of [topics](../index.md#contents) I consider myself knowledgeable of. Similar in spirit to [Dan's post on things he doesn't know](https://overreacted.io/things-i-dont-know-as-of-2018/).

My entire workflow is outlined [here](my-workflow.md).

- [Karabiner](../macOS/apps/karabiner/index.md): I bind all most common actions I do on my mac via Karabiner and my custom modifier keys ([`a` key is control, `w` opens apps, ..](../macOS/apps/karabiner/index.md#my-personal-karabiner-setup)).
- [macOS](../macOS/index.md): How to operate it very fast. Especially with apps like [KM](../macOS/apps/keyboard-maestro/index.md), [Alfred](../macOS/apps/alfred/index.md)/[Raycast](../tools/raycast.md), [VSCode](../text-editors/vs-code/index.md).
- [Solid](../programming-languages/javascript/js-libraries/solid.md): Using it for all my web apps and static sites. Love how it takes all the best parts of [React](../programming-languages/javascript/js-libraries/react/index.md) (component tree model with one way data flow & JSX) but [does it better](https://www.youtube.com/watch?v=UhGV8yYnvQE) due to [fine grained reactivity ](https://dev.to/ryansolid/a-hands-on-introduction-to-fine-grained-reactivity-3ndf) & avoiding VDOM thus being [much faster than React](https://twitter.com/nikitavoloboev/status/1528479450828087299). I try to be conscious of [performance](../web/web-performance.md) in all my projects.
- [TS](../programming-languages/typescript/index.md): Use TS in all my [web apps](../web/index.md), [CLIs](../cli/index.md) (using [Bun](../programming-languages/javascript/bun.md)) and [serverless](../cloud-computing/serverless-computing/index.md) endpoints (using [Hono](https://hono.dev/)) until performance is actually needed.
- [Go](../programming-languages/go/index.md): Great for writing native code due to its fast compile speeds & out of the box performance.
- [Rust](../programming-languages/rust/index.md): Exploring using Rust more, mostly because [Tauri](../programming-languages/rust/rust-libraries/tauri.md) & [WASM](../web/webassembly.md) are great.
- [Grafbase](../networking/graphql/grafbase.md): Using Grafbase currently as my data store that exposes [GraphQL](../networking/graphql/index.md) and has fast response times as its built on top of [DynamoDB](../databases/dynamodb.md) and is replicated globally. [EdgeDB](../databases/edgedb.md) is interesting alternative as it builds on top of [Postgres](../databases/postgresql.md) but has [well made query language](https://www.edgedb.com/docs/edgeql/index) & [declarative schema modeling](https://www.edgedb.com/docs/datamodel/index) that is a delight to edit. Nearly all queries are easy to construct & are fast without doing any optimizations. [Planetscale](../databases/planetscale.md) is nice too.
- [SQLite](../databases/sqlite.md): Use it for whenever I need an embedded database. Local apps etc. Exploring local first architectures like [Replicache](https://replicache.dev/) & [Logux](https://logux.io/). [Turso](https://chiselstrike.com/) is exciting.
- [Cloudflare Workers](../cloud-computing/serverless-computing/cloudflare-workers.md) & [Cloudflare R2](https://developers.cloudflare.com/r2/): Looking into using it as distributed cache & small data store. [Hono](https://github.com/honojs/hono) is amazing library. Cloudflare in general has [great web services](https://github.com/cloudflare/wildebeest) I like using.
- [Swift](../programming-languages/swift/index.md) & [SwiftUI](../programming-languages/swift/swift-libraries/swiftui.md): Build [iOS](../operating-systems/ios/index.md) apps with them. [Expo](../programming-languages/javascript/js-libraries/react/expo.md) has some great tools and it's my goto for cross platform mobile apps.
- [Nix](../package-managers/nix/index.md): Use it as my main package manager.

## My Workflow

I list all the [tools](../tools/index.md) and my [approaches to life](../focusing/rules.md) & [solving problems](../research/solving-problems.md) in [here](my-workflow.md). It's constantly updating. I try to automate all the annoying things I encounter.

## Learning now

Currently track in [Height](https://height.app/) as part of [goals](../focusing/goals.md). In future this will move to [LA](../ideas/learn-anything.md).

I try to learn things in service of [ideas](../ideas/index.md) I am building.

Or I am curious about something and want to explore. Lately it's been:

- [Solid](../programming-languages/javascript/js-libraries/solid.md) / [TS](../programming-languages/typescript/index.md) / [Cloudflare Workers](../cloud-computing/serverless-computing/cloudflare-workers.md) 
- [Rust](../programming-languages/rust/index.md) / [Tauri](../programming-languages/rust/rust-libraries/tauri.md)
- [Grafbase](../networking/graphql/grafbase.md) / [GraphQL](../networking/graphql/index.md)
- [Swift](../programming-languages/swift/index.md) / [SwiftUI](../programming-languages/swift/swift-libraries/swiftui.md) / [Expo](../programming-languages/javascript/js-libraries/react/expo.md)
- [NLP](../nlp/index.md) / [Physics](../physics/index.md) / [Biology](../biology/index.md)
