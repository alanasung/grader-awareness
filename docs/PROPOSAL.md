# When Models Notice the Grader During Training

## Hypothesis

Detect and intervene on signals that a training grader is present.

## Approach

Local open-weight pilot with a measured path when weights are available and an
explicit synthetic smoke path. Claims are gated when measurements are proxy-grade.

## Primary metrics

- Pilot metric with confidence interval
- `claim_ok` / honesty stamps
- Synthetic contamination rate
