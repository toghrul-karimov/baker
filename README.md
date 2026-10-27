# Baker Lean sources

Verified source archive of the completed Baker Certified development through Stage 91, exported on 26 October 2026.

[Download the Lean sources ZIP](https://github.com/toghrul-karimov/baker/raw/refs/heads/main/baker-all-lean-sources.zip) (95,638,924 bytes, approximately 96 MB).

The archive contains the current project (1,464 Lean files), pinned dependency source references, historical source variants, provenance, and a Git bundle preserving all 74 canonical branches. Historical variants include unfinished experiments; they are separate from the current development.

## Download and open

Download `baker-all-lean-sources.zip` and `SHA256SUMS` from this repository, or clone it:

```sh
git clone git@github.com:toghrul-karimov/baker.git
cd baker
```

Verify the ZIP on Linux with `sha256sum -c SHA256SUMS`, or on macOS with `shasum -a 256 -c SHA256SUMS`. Then extract it:

```sh
unzip baker-all-lean-sources.zip
```

Read `baker-lean-sources/START_HERE.txt` first. The current source tree is `baker-lean-sources/project/`. The archive also includes `tools/verify_package.py` for checking its extracted contents.

## Reproduction

- Lean: `leanprover/lean4:v4.34.1`
- mathlib: `d13f23b723b8a846827a245b89c10fc7d3f11612`
- Final canonical source commit: `6f5fd551d3d3cff699672a5ce6b289340371a306`

Keep the exact pins in the included `lake-manifest.json`. The dependency source references are not complete Git checkouts or compiled caches; follow `START_HERE.txt` to set up dependencies and recover the canonical Git history on a new machine. Read the included campaign usage and final report for the mathematical interface and scope.

The delivery was checked for source completeness and archive integrity. No fresh Lean compilation was performed for this export or upload.
