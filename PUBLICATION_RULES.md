# Public progress publication rules

This directory is the only source for the separate Trail Server public progress
repository. Publish it from fresh Git history; never copy the private
repository's `.git` directory or merge private branches into the public remote.

Before each publication, verify that the export contains no:

- implementation source, firmware, tests, build scripts, or deployment files;
- internal contracts or detailed engineering evidence;
- credentials, keys, tokens, private addresses, device identifiers, or captures;
- private issue, pull-request, commit, branch, or operator information;
- unsupported production, safety, field, availability, or delivery claims.

The public repository may contain milestone summaries, a high-level roadmap,
sanitized screenshots or demonstrations, and links intentionally approved for
public viewing.
