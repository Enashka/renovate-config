# renovate-config

Shared Renovate policy for Enashka repositories. A repository opts in with:

    { "extends": ["github>Enashka/renovate-config"] }

and adds only its own exceptions. Public on purpose: public repositories cannot extend a private preset, and this file holds no secrets.

Policy: weekly run (Monday before 6am, Paris); new releases wait 3 days; security fixes immediately, never automerged; one grouped PR for minor and patch, automerged only where GitHub checks exist; majors and 0.x minors only on request from the Dependency Dashboard.
