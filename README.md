# editorconfig

Centrally managed EditorConfig

## Why

I don't want to keep reinventing my config per project and distribute any new changes everywhere.

## How to roll in a new repository

Docs for anttiharju - if you are not Antti, these obviously do not apply to you.

- Invite the service account [`anttiharju-bot`](https://github.com/anttiharju-bot) as collaborator
- Allow auto-merge in target repo
- Configure a branch protection rule to support automerge or mark `automerge` as false in the update step
- Remember to update repo list in `Generate commit token` step.
