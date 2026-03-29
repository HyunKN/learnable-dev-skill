# Risk Checklist

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
- Should this become a decision record?
