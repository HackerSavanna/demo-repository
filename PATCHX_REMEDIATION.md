# PatchX dependency remediation

PatchX could not edit these manifests automatically, so the required
changes are recorded here for a maintainer to apply and review.

## package.json
Rename 'technical-assignment' to the owned namespace '@swypt-io/technical-assignment'

Manifest: `package.json`

Change:

```
"name": "@swypt-io/technical-assignment"
```
- Create or confirm the 'swypt-io' organization/scope on npm.
- Rename the package to '@swypt-io/technical-assignment' in package.json and update imports/references.
- Publish it privately or with restricted access so only your org can install it, or set "private": true if it should never be published.
- Update CI and any downstream consumers to the new name, then re-run the scan to confirm.

## package.json
Rename 'technical-assignment' to the owned namespace '@swypt-io/technical-assignment'

Manifest: `package.json`

Change:

```
"name": "@swypt-io/technical-assignment"
```
- Create or confirm the 'swypt-io' organization/scope on npm.
- Rename the package to '@swypt-io/technical-assignment' in package.json and update imports/references.
- Publish it privately or with restricted access so only your org can install it, or set "private": true if it should never be published.
- Update CI and any downstream consumers to the new name, then re-run the scan to confirm.

## technical-assignment
Rename 'technical-assignment' to the owned namespace '@swypt-io/technical-assignment'

Manifest: `package.json`

Change:

```
"name": "@swypt-io/technical-assignment"
```
- Create or confirm the 'swypt-io' organization/scope on npm.
- Rename the package to '@swypt-io/technical-assignment' in package.json and update imports/references.
- Publish it privately or with restricted access so only your org can install it, or set "private": true if it should never be published.
- Update CI and any downstream consumers to the new name, then re-run the scan to confirm.

## package.json
Rename 'demo-repo' to the owned namespace '@hackersavanna/demo-repo'

Manifest: `package.json`

Change:

```
"name": "@hackersavanna/demo-repo"
```
- Create or confirm the 'hackersavanna' organization/scope on npm.
- Rename the package to '@hackersavanna/demo-repo' in package.json and update imports/references.
- Publish it privately or with restricted access so only your org can install it, or set "private": true if it should never be published.
- Update CI and any downstream consumers to the new name, then re-run the scan to confirm.

