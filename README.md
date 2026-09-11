# Abhishek Dadwal

`platform · systems · firecracker`

I build the infrastructure that runs untrusted code safely: microVMs, schedulers, and the networking and storage underneath them.

Currently building **[RenderOps](https://github.com/renderops-ai/renderops-sandbox)**, a Firecracker microVM sandbox platform (the category [E2B](https://e2b.dev) and [Modal](https://modal.com) operate in). An in-memory best-of-K scheduler, host-level egress control, disk-backed copy-on-write storage, snapshot-based pause/resume, and signed tunnel URLs into untrusted guests.

### Writing

I write about the hard parts of building sandbox infrastructure.

- [How we tunnel a public URL into an untrusted sandbox](https://abhid.me/writings/tunnel-public-url-into-untrusted-sandbox)
- [How to schedule thousands of sandboxes without melting your database](https://abhid.me/writings/schedule-sandboxes-without-melting-your-database)
- [The real storage architecture behind AI agent sandboxes](https://abhid.me/writings/storage-architecture-ai-agent-sandboxes)
- [Firecracker networking notes](https://abhid.me/writings/firecracker-networking-notes)

More at **[abhid.me/writings](https://abhid.me/writings)**

### Open source

- [hashicorp/vault#31740](https://github.com/hashicorp/vault/pull/31740): fixed AWS ALB mTLS client-certificate header decoding on the core HTTP path
- [hashicorp/vault#31733](https://github.com/hashicorp/vault/pull/31733): fixed a nil-pointer panic in the Transit secrets engine
- [temporalio/cli#926](https://github.com/temporalio/cli/pull/926): improved console output for `TestWorkflowEnvironment`

### Elsewhere

[abhid.me](https://abhid.me) · [Writing](https://abhid.me/writings) · [X](https://x.com/AbhishekDadwa16) · [LinkedIn](https://www.linkedin.com/in/abhishek-dadwal-5565781b6/)

<sub>the sandbox is untrusted by construction, so every control lives one level outside it.</sub>
 
