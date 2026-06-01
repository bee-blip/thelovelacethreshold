
# The Lovelace Threshold Diagnostic
A cross-industry diagnostic that identifies when an organization can no longer reliably see, explain, or improve the conditions that produce its outcomes.

## Why it matters
Many organizations govern outputs after the fact, but the real risks are created upstream in models, incentives, records, workflows, vendor dependencies, or classifications.

## What it helps with
- Improving accountability.
- Finding blind spots.
- Reducing preventable harm.
- Making feedback actionable.
- Identifying where governance is too downstream to be effective.

## Example settings
- Public administration: eligibility, classification, and service workflows.
- Digital infrastructure: pipeline trust, change control, and operational dependencies.

## Diagnostic question
Can the organization see enough of the process that produces the outcome to improve it before harm hardens?

## How it works
You name two things: what you are assessing, and what it produces. The diagnostic then asks seven questions about that instrument. Each question maps to one dimension:

1. How predictable the governed system is.
2. What the instrument actually reaches: only the result, or how the result is made.
3. Documentation coverage: how much of how the outcome is made is written down and checkable.
4. Response lag: how fast the instrument can react when something changes early.
5. Challenge and withdrawal: whether affected people can act before harm sets in.
6. Protection against quiet, after-the-fact narrowing of the instrument.
7. Whether records are kept by design, not only when someone asks.

As you answer, the readout updates live: a verdict, a moving threshold line, three summary readings, a dimension-by-dimension breakdown, and a list of blind spots paired with the controls that close them.

## The documentation floor
One dimension is not weighted like the others. **Documentation coverage is a precondition**. Full coverage is the floor. Below full coverage, the instrument is by definition: inside the threshold, no matter how well everything else reads. The diagnostic refuses to average this away, because treating documentation as a score to optimize rather than a floor to meet is itself the failure it is looking for.

## The moving threshold
The threshold is not a fixed score to beat. It rises as the governed system becomes harder to predict in advance. The instrument is then placed by how far its reach extends. The verdict is the relationship between the two, which is why the same instrument can be sufficient against a predictable system and insufficient against a generative one.

## Reading the verdict
- **Enough for now**: the instrument reaches further than this system currently demands. It is outside the threshold: sound and sufficient for now.
- **At the threshold**: reach sits level with demand. A small rise in unpredictability, or any drop in reach, tips it over. The organization is approaching the threshold.
- **Past the threshold**: the system produces effects the instrument cannot see coming. Formally valid, but no longer enough; harm is produced before the reviewed result is even reached.
- **Inside the threshold (floor breach)**: documentation is below the floor, so the instrument cannot reliably explain how its outcomes are produced. This overrides everything else.

## The three readings
- **Blind-spot risk**: exposure created by an unpredictable system and limited reach.
- **Governance reach**:  how far the instrument extends into how results are made.
- **Responsiveness**:  how quickly it can react and whether people can challenge it in time.

## Process being assessed
- What decision, service, or workflow is being reviewed?
- Who is affected?
- What outcome is produced?

## Run it / deploy it
This is a single, self-contained static file with no backend and no build step.
- **Locally**: open index.html in any browser.
- **On GitHub Pages**: commit index.html to the repository root, then enable Pages (Settings → Pages → deploy from the default branch). It will be live at your Pages URL with no further configuration.

## Tailored version
This is the open, generic version. A version fitted to a specific domain requires your own measures, record classes, a working dashboard. wired to real data can developed through a consultation.

_DISCLAIMER: This is a prototype. The scoring demonstrates the logic; it is not a certified audit. As a learning-and-integration concept, this is where an organization (or government, or system) starts learning from what's been broken and folding that learning into how it operates day to day, so harm can be prevented._
