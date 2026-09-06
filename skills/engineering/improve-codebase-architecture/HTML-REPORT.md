# HTML Report Format

The architectural review is rendered as a single self-contained HTML file in the OS temp directory. Tailwind and Mermaid both come from CDNs. Mermaid handles graph-shaped diagrams reliably; hand-built divs and inline SVG handle more editorial visuals.

## Candidate card

Each candidate is an `<article>` containing the title, recommendation strength, files, a before/after diagram, a one-sentence problem, a one-sentence solution, concise wins, and an ADR callout when applicable.

## Diagram patterns

Use Mermaid flowcharts or sequence diagrams for dependency and call flow. Use hand-built HTML/SVG for editorial visuals. Cross-sections show layered shallowness; mass diagrams show interface surface versus implementation depth; call-graph collapse shows many internal calls becoming one deep module.

## Style guidance

Keep the report lean and editorial. Use colour sparingly, keep diagrams around 320px tall, and use small uppercase labels for module names. Tailwind and Mermaid are the only external scripts.

## Tone

Use the `/codebase-design` vocabulary exactly: module, interface, implementation, depth, deep, shallow, seam, adapter, leverage, locality.
