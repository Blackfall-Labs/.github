# Blackfall Labs

Blackfall Labs builds software people own: offline-first formats, the Noderalis engine, and open machine intelligence research.

## A word on the mess

Most of what lives here is research first. Old attempts sit next to new ones, names reflect what we needed that week, and plenty of repos never got a proper README. We publish the real work rather than a tidied-up version of it. Every repo carries a status so you know what you are looking at:

- **Stable**: released and versioned. Safe to depend on.
- **Active**: being built now. Expect breaking changes.
- **Research**: experiments, published as-is.
- **Prototype**: proved an idea, not maintained yet.
- **Archived**: read-only, kept for history.

## Data Preservation and Migration: formats

Long-lived, offline-first file formats. **Stable**.

- [engram-rs](https://github.com/Blackfall-Labs/engram-rs): signed, compressed archives with SQLite inside.
- [cartridge-rs](https://github.com/Blackfall-Labs/cartridge-rs): mutable archives with snapshots and a SQLite VFS.
- [dataspool-rs](https://github.com/Blackfall-Labs/dataspool-rs): single-file bundles with an index and vector search.

## Machine Intelligence: Astromind

Astromind is our cellular machine intelligence research: small, CPU-native, integer-first brains built from biological substrates. Everything below is **Research**.

- [ant-mnist](https://github.com/Blackfall-Labs/ant-mnist): Atomic neural transistors applied to MNIST digits.
- [astromind-final](https://github.com/Blackfall-Labs/astromind-final): Final consolidated Astromind release.
- [atomic-neural-transistors](https://github.com/Blackfall-Labs/atomic-neural-transistors): Atomic neural transistors, the small learned units Astromind builds on.
- [cochlea-rs](https://github.com/Blackfall-Labs/cochlea-rs): Cochlea model: sound into neural signal.
- [elegans-rs](https://github.com/Blackfall-Labs/elegans-rs): 302-neuron C. elegans brain that develops into a working worm brain.
- [fibertract-rs](https://github.com/Blackfall-Labs/fibertract-rs): Peripheral nerve fiber tracts for sensing and motor signals.
- [neuropool-rs](https://github.com/Blackfall-Labs/neuropool-rs): Biological neuron pool: LIF neurons, synapses, three-factor plasticity.
- [organpool-rs](https://github.com/Blackfall-Labs/organpool-rs): Organ physics: cardiac pacemaker with autonomic control.
- [signal-oscillator](https://github.com/Blackfall-Labs/signal-oscillator): Ternary waveform synthesis with temporal smoothing.
- [strategos-brain](https://github.com/Blackfall-Labs/strategos-brain): Strategos brain, an Astromind version.
- [temporal-field-rs](https://github.com/Blackfall-Labs/temporal-field-rs): Decaying ring-buffer field with pub/sub; event-driven, no polling.
- [ternary-signal](https://github.com/Blackfall-Labs/ternary-signal): Ternary signal primitives the Astromind substrates share.
- [ternsig-audio-experiment](https://github.com/Blackfall-Labs/ternsig-audio-experiment): Audio experiment on the ternary signal.
- [thermogram-rs](https://github.com/Blackfall-Labs/thermogram-rs): Four-temperature plastic memory with an auditable hash chain.
- [tiny-recursive-rs](https://github.com/Blackfall-Labs/tiny-recursive-rs): Rust port of Tiny Recursive Models for puzzle solving.
- [whitematter-rs](https://github.com/Blackfall-Labs/whitematter-rs): White matter tracts between brain regions.

## Divisions

### Data Preservation and Migration

Keeping knowledge readable for decades, offline, and moving it out of old and fragile formats into ones we control. This division builds the formats (Engram, Cartridge, DataSpool, CML), the tools that bring data in (PDF and DOCX into CML, conversion pipelines into Engrams), and the collections we publish as Engrams you download overnight, starting with a public-domain library.

### Machine Intelligence

Astromind, our cellular machine intelligence research: small, CPU-native, integer-first brains built from biological substrates, now in its 26th version. Alongside it: research into fast knowledge retrieval, and agents that work through the engine.

### Computational Engineering and Research

Where most of our engineering happens. The Noderalis engine (runtime, supervisor daemon, capability model, embedded Databank), the developer platform around it (the Nod CLI, JS and Rust SDKs, WASM modules packaged as Engrams), shared services such as sync and communications, and the personal and business software built on top.

### Manifest Humanity

Civic infrastructure. Laws, bills, constitutions and regulations, gathered and published as Engrams people download once and use offline, linked down to the exact clause, with plain-language summaries tied to the source text.

### Astrolyptic Entertainment & Media

One storyverse: the game, the books and stories, the characters and the art that carries across all of it.

Browse by topic: [machine-intelligence](https://github.com/orgs/Blackfall-Labs/repositories?q=topic%3Amachine-intelligence), [data-preservation](https://github.com/orgs/Blackfall-Labs/repositories?q=topic%3Adata-preservation), [astromind](https://github.com/orgs/Blackfall-Labs/repositories?q=topic%3Aastromind).

More at [blackfall.dev](https://blackfall.dev).