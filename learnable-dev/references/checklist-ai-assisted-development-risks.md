# Checklist - AI-Assisted Development Risks

Use this checklist before or during meaningful AI-assisted development.

## Technical Choice

- Why is this dependency or pattern needed?
- Is there a simpler built-in or existing option?
- What maintenance or compatibility risk does it add?

## Execution and Permissions

- Does it widen file, shell, or network access?
- Can user input reach command execution or unsafe paths?
- Is any external tool execution constrained?

## Product and Safety

- Can the change be explained clearly?
- What could fail if this is wrong?
- Is validation strong enough for the change size?
- Does this need to be documented as a decision, note, or operating rule?

## Vibe-Coding Smells

- AI suggestions were accepted without comparison.
- The structure looks clever but is hard to explain.
- External dependencies were added without a clear need.
- The feature works, but no one wrote down why this version was chosen.
- The team keeps saying “we will clean it up later.”
