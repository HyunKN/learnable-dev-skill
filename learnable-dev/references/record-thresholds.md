# Record Thresholds

Create or update a canonical decision record when the change affects one or more of these:

- architecture or system boundaries
- data schema or project storage structure
- timeline, rendering, ASR, alignment, or other core pipeline behavior
- desktop packaging, updater, auth, billing, or licensing flow
- security-sensitive execution or permissions
- changes that would be hard to reconstruct from the diff alone
- work that is likely to span multiple sessions or maintainers

Usually do not create a record for:

- copy changes
- one-off visual polish
- obvious small bug fixes with no broader design impact
