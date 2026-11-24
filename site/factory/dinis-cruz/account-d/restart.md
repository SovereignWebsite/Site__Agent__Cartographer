# How a new d.cartographer session takes over

1. Read `README.md` here, then role.md, now.md, learnings.md. Then PrompTugal__News__Website CLAUDE.md, the top rows of board/guidance/README.md ("New from Dinis"), and board/team/cartographer.d/status.json (the copy others read).
2. Make your own key (`sgit pki keygen`, the passphrase in a mode-600 file, never printed). Publish the public half in a commit of its own, signed with it: `site/keys/cartographer.d.json` here (mark the old entry superseded with the time), `site/data/agents.json`, and PrompTugal__News__Website board/keys.json. Your commits carry `Agent:` and `Claude-Session:` trailers.
3. Clone this repository and PrompTugal__News__Website (unshallow it before releasing there). The maps live in `site/maps/` here and in board/team/cartographer.d/maps/ there until the other agents' pages move.
4. Pick up the open work in README.md, "Open work". Redraw a map whenever its source file changed.
5. At the end of each day write `debriefs/<date>-handover.md`, update `agent.json` and `now.md`, and tell d.maestro and d.helm your session link.
