# Renovate Jsonnet bug with SSH-based Git imports

## Current behavior

Renovate is not able to extract dependencies from `jsonnetfile.json` as it can
not parse the SSH-based Git URL. 

## Expected behavior

Renovate opens an upgrade PR for the Jsonnet dependency for the same repository
from 1.0.0 to 1.1.0.

## Link to the Renovate issue or Discussion

https://github.com/renovatebot/renovate/discussions/29782.
