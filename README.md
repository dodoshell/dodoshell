### Hi there

Full-stack developer working mostly with Java, TypeScript and Python. I build products end to end, and I like digging into real bugs in open source projects and sending fixes with tests.

**Portfolio:** [dodoshell.vercel.app](https://dodoshell.vercel.app), with a case study for each project below.

#### Projects

- [**Poltrona**](https://dodoshell.vercel.app/en/work/poltrona): cloud management for hair salons, where the database itself refuses double bookings (Next.js, Supabase, PostgreSQL). [Live](https://poltrona.app)
- [**Corsia**](https://dodoshell.vercel.app/en/work/corsia): exam prep for taxi and chauffeur drivers, with answers graded on the server and idempotent Stripe webhooks (Next.js, Supabase, Stripe). [Live](https://corsia-two.vercel.app)
- [**Sconti Nova**](https://dodoshell.vercel.app/en/work/sconti-nova): Amazon deals verified every hour, built with a partner (Next.js, Supabase, PostgreSQL). [Live](https://www.scontinova.com)
- [**iter**](https://github.com/dodoshell/iter): leave request management with a state-machine approval workflow (Spring Boot, React, PostgreSQL, Docker). [Live demo](https://iter-rosy.vercel.app)
- [**portfolio**](https://github.com/dodoshell/portfolio): the site above, with a three.js shader background (Next.js 16, React 19)

#### Open source contributions

- [The-PR-Agent/pr-agent#4425](https://github.com/The-PR-Agent/pr-agent/pull/4425): make the LiteLLM handler the only retry layer, honouring `Retry-After` (merged)
- [doobidoo/mcp-memory-service#1648](https://github.com/doobidoo/mcp-memory-service/pull/1648): report memory load and save status to Codex through `systemMessage` (merged)
- [doobidoo/mcp-memory-service#1676](https://github.com/doobidoo/mcp-memory-service/pull/1676): make the dashboard's Quality tab actually save its settings (merged)
- [LearningCircuit/local-deep-research#7886](https://github.com/LearningCircuit/local-deep-research/pull/7886): behaviour tests for the Zotero collection picker (merged)
- [btclib-org/btclib#2776](https://github.com/btclib-org/btclib/pull/2776): tests for the signature-operation boundaries (merged)
- [btclib-org/btclib#2821](https://github.com/btclib-org/btclib/pull/2821): `assert_p2tr` names the right witness version, with four new refusal tests (merged)
- [ludo-technologies/pyscn#865](https://github.com/ludo-technologies/pyscn/pull/865): LCOM4 no longer counts inherited method calls as instance state (merged)
- [ludo-technologies/pyscn#866](https://github.com/ludo-technologies/pyscn/pull/866): the single-responsibility rule counts sibling modules as one concern (merged)
- [Rizzo-AI-Academy/rizzo-pii#141](https://github.com/Rizzo-AI-Academy/rizzo-pii/pull/141): fix a torch thread leak on Windows
- [RailtownAI/railtracks#1734](https://github.com/RailtownAI/railtracks/pull/1734): accept local `.avif` attachments (merged)
- [LearningCircuit/local-deep-research#8124](https://github.com/LearningCircuit/local-deep-research/pull/8124): the PDF export renders a table that directly follows text as a table (merged)
- [ludo-technologies/pyscn#874](https://github.com/ludo-technologies/pyscn/pull/874): the deep-nesting suggestion points at the deepest block instead of the `def` line (merged)
- [RailtownAI/railtracks#1765](https://github.com/RailtownAI/railtracks/pull/1765): rewriting a Chroma entry no longer keeps stale chunk metadata
- [LearningCircuit/local-deep-research#8212](https://github.com/LearningCircuit/local-deep-research/pull/8212): hiding the settings JSON editor saves only the keys that were edited (merged)
- [LearningCircuit/local-deep-research#8213](https://github.com/LearningCircuit/local-deep-research/pull/8213): a failed theme save from the header puts the previous theme back (merged)
- [btclib-org/btclib#2908](https://github.com/btclib-org/btclib/pull/2908): `obfuscate` refuses a huge negative offset with btclib's own error (merged)
- [btclib-org/btclib#2909](https://github.com/btclib-org/btclib/pull/2909): the import test also keeps btclib free of `bip32_descriptors`
- [lingui/js-lingui#2766](https://github.com/lingui/js-lingui/pull/2766): plural and selectordinal no longer pick up members inherited from `Object.prototype`
- [lingui/js-lingui#2767](https://github.com/lingui/js-lingui/pull/2767): a macro placeholder named `__proto__` stays a normal value
- [spring-projects/spring-session#4150](https://github.com/spring-projects/spring-session/pull/4150): changing a session id removes the old id from the Redis expirations set
- [pmd/pmd#7280](https://github.com/pmd/pmd/pull/7280): `InternalApiUsage` no longer flags `@VisibleForTesting` members used inside their own record or enum
