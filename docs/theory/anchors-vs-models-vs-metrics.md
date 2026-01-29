# Anchors vs Models vs Metrics

Anchors define non-negotiable boundaries. Models explain behavior within those boundaries. Metrics track performance but cannot redefine the boundary.

## Anchor
A hard constraint that defines admissibility.

## Threshold
A condition that is not softened by model fidelity or metric improvements.

## Consequence of Crossing
Metrics can improve while a system still fails if it crosses the anchor.

## Why Optimization Cannot Override It
Optimization can improve metrics but cannot turn an inadmissible state into an admissible one.
