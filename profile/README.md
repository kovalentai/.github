<div align="center">
  <img src="https://kovalentai.com/logo-multicolor.png" alt="Kovalent AI" width="112" />

  <h1>Kovalent AI</h1>

  <p><strong>Private AI infrastructure for teams that cannot use shared black boxes.</strong></p>

  <p>
    <a href="https://kovalentai.com">Website</a> &nbsp;·&nbsp;
    <a href="https://docs.kovalentai.com">Platform Docs</a> &nbsp;·&nbsp;
    <a href="https://knaix.com">Knaix CLI</a> &nbsp;·&nbsp;
    <a href="https://github.com/kovalentai/knaix-cli">Source</a> &nbsp;·&nbsp;
    <a href="https://app.kovalentai.com">Get Access</a>
  </p>

  <p><sub>Now in Private Beta</sub></p>
</div>

## Kovalent runs the control plane. You own your nodes.

Kovalent coordinates a mesh of isolated, single-tenant AI nodes. A central **control plane** handles the parts that have to be shared, identity, billing, and node provisioning, while the model that answers your questions, the knowledge it reads, and the runtime that serves them stay inside your own network boundary. Coordination is managed. Computation is yours.

## How it works

- **The control plane, managed by us.** SSO identity, node discovery, and routing. It issues routing directives so your nodes can find each other, and never touches your raw data.
- **Your nodes, owned by you.** Every node runs on isolated hardware with a cryptographic identity and a deny-by-default firewall. On paid tiers, inference runs on the node itself: your prompts, the documents it retrieves, and the answer it writes stay on hardware dedicated to you, with no third-party inference service in the path.
- **A private mesh, by architecture.** Peers connect directly over a WireGuard mesh, and you can bring your own Tailscale. Traffic flows peer to peer, so we stay blind to your data.

## What's inside

- **Knaix CLI** ([knaix.com](https://knaix.com), [source](https://github.com/kovalentai/knaix-cli)): run the whole stack locally with `knaix local up`, no account required, or `knaix login` to join your private mesh. Written in Rust, Apache-2.0, and every release is signed so you can check the binary you are running.
- **Dashboard** ([app.kovalentai.com](https://app.kovalentai.com)): provision nodes, watch live metrics and logs, and connect a local node next to hosted ones.
- **Knowledge base with citations**: a real knowledge base on every node, where answers cite their sources down to the page and passage.
- **Tamper-evident audit trail**: a hash-chained record of control-plane activity, for the teams who evaluate us.

## Start here

| | |
| --- | --- |
| Learn the platform | [docs.kovalentai.com](https://docs.kovalentai.com) |
| Install the CLI | [knaix.com](https://knaix.com) |
| Read the CLI source | [github.com/kovalentai/knaix-cli](https://github.com/kovalentai/knaix-cli) |
| Request Beta access | [app.kovalentai.com](https://app.kovalentai.com) |
| Read our story | [kovalentai.com/about](https://kovalentai.com/about) |
| Talk to us | info@kovalentai.com |
