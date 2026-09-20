# Social launch copy for “Token Economy”

Replace `{{ARTICLE_URL}}` with the published article URL before posting.

## X post

AI coding cost is not only a model problem.

It is a systems problem: model, harness, tools, context, cache behavior, retries, and human recovery.

I wrote a practical framework for measuring **verified engineering output per dollar**.

{{ARTICLE_URL}}

## X thread

### 1/8

The cheapest model is not always the cheapest way to finish a task.

The useful metric is closer to:

`cost per closed task = total agent cost / verified successes`

I wrote a practical field guide to the system around the model.

{{ARTICLE_URL}}

### 2/8

The model and the harness should be evaluated together.

HarnessTax reports similar success rates with materially different costs across Claude Code, Codex CLI, and Pi.

On SWE-bench Lite, Claude Code costs about 2× Pi across shared models.

### 3/8

A harness can spend tokens before the first useful tool call.

Instructions, tool schemas, and default behavior all become part of the initial context.

More context is not automatically more capability.

Sometimes it is just more billable state.

### 4/8

The cheapest token is the token that never enters context.

Use narrow interfaces, on-demand Skills, focused search, and compressed shell output.

CLI, RTK, Headroom, and similar tools attack different layers of the same problem: remove repetition before the model sees it.

### 5/8

Subagents are not only a delegation feature.

They are a context-isolation boundary.

Let exploration be noisy in a short-lived context.

Return the evidence and decision, not every command and failed attempt.

### 6/8

Prompt caching is an operating discipline.

Provider switches, model switches, system-prompt changes, and long pauses can rebuild the cached prefix.

Stable work should stay together when the cache window is valuable.

### 7/8

Watch for drift:

- rising context
- falling cache-hit ratio
- repeated tool calls
- repeated file reads
- cost rising without new evidence

Three failed attempts with the same strategy usually need a new strategy.

### 8/8

The goal is not fewer tokens at any cost.

The goal is more verified engineering output per dollar.

Choose the model and harness as a pair.

Measure the closed result.

Intervene before the loop compounds.

{{ARTICLE_URL}}

## LinkedIn post

AI coding cost is usually framed as a model-pricing problem.

That framing is incomplete.

The actual spend is produced by a system: model, harness, tools, context construction, cache behavior, retries, and human recovery.

I wrote a research-style field guide called **Token Economy: How to Spend an AI Coding Budget Like an Engineer**.

The article combines public benchmark evidence with practical observations from high-volume agent workflows.

The main ideas are:

- Choose the model and harness together.
- Measure cost per verified task, not tokens in isolation.
- Treat initial context as part of the bill.
- Prefer narrow interfaces and on-demand knowledge.
- Isolate exploration so intermediate noise does not pollute the parent context.
- Protect prompt caches through stable, closely grouped work.
- Monitor drift signals such as repeated tool calls and rising burn rate.

The goal is not to minimize tokens blindly.

It is to increase verified engineering output per dollar.

Read it here: {{ARTICLE_URL}}

#AI #CodingAgents #SoftwareEngineering #LLMOps #DeveloperTools
