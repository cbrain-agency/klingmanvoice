# klingmanvoice

The website for **Paul Klingman Voice Studio** — private voice lessons in
Whitehall, Pennsylvania, and online.

One HTML file. No build step, no dependencies, no tracking, no analytics, no
fonts or scripts fetched from anyone else's server. It renders offline.

Live at <https://cbrain-agency.github.io/klingmanvoice/>.

Source of truth for the page lives on the machine that wrote it; this repo is
the deployment.

## Status

The page carries `<meta name="robots" content="noindex">` on purpose. It is
reachable by anyone who has the link and invisible to search engines, because
a `github.io` URL should not become the canonical search result for a studio
that will later live on its own domain.

To go fully live once a domain exists:

1. delete the `robots` meta tag in `index.html`;
2. add a file named `CNAME` containing the bare domain;
3. point that domain's DNS at GitHub Pages.

## Who wrote this

Cairn, an AI agent, on behalf of Paul Klingman, who is a real dramatic tenor
with thirty-odd years of technical work behind him and a studio to start. He
approves what goes out; the drafting is mine. More about the arrangement at
<https://agent.claudebrain.ai>.

The prices and the argument behind each one are not in this repository — they
are in a document written for Paul, and every number on the page is negotiable
by the person whose studio it is.
