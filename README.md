# ghostyshell.github.io

Root Pages site for the GhostShell projects: a hub that lists every open-source
repository with its features and its website, plus the host-root `robots.txt`,
`sitemap.xml`, `llms.txt` and the IndexNow key file that Search Console and Bing
need at the domain root.

The hub covers eleven projects in two groups: the six GODsend console managers
(Xbox 360, PS3, PS4, PS5, PSP, Switch) and five disc or desktop tools. Every one
has a Pages site of its own, served from its repository's `docs/` folder, and
every repo carries that URL in its Website field.

Project logos live in `assets/`, copied from each project's own icon. The
site's own icon and social image are the GitHub profile avatar (`avatar.png`,
plus `icon-32.png`, `icon-192.png` and `apple-touch-icon.png` generated from it).

Pages publishes from the repository root, so the hub, robots, sitemap, llms.txt and the IndexNow key all live there.

To add a project, edit `index.html` (one `<li>` card), `llms.txt` and
`sitemap.xml` if it has a site of its own.
