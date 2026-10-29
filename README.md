# S01E03: tickets split out of #4471

- Tickets: the issues in this repo, one per problem, each with its report count and ids.
- Page source: `support-kb/src/routes/kb/incidents/4471-split/+page.svx`
- Page as the desk sees it: `support-kb/build/kb/incidents/4471-split/index.html` (whole built kb in `support-kb/build/`; `support-kb/4471-split.html` is a copy of that page). Serve `support-kb/build/` to view it with its styles.

The build comes from the desk's own components (SvelteKit + mdsvex) run over the kb export with this page added, not written by hand.
