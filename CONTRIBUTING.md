# Contributing

Thank you for improving Brain Activity Atlas.

## Scientific contributions

Every proposed activity or regional mapping should include:

1. a peer-reviewed primary source, systematic review, or meta-analysis;
2. the experimental task and comparison condition;
3. the studied population and imaging modality when relevant;
4. cautious wording that distinguishes association from necessity or causation.

Do not add numerical activation strength unless it comes from a compatible quantitative dataset and the visualization clearly defines the scale.

## Interface contributions

- Preserve keyboard and touch usability.
- Test desktop and mobile layouts.
- Keep region colors distinguishable from the unselected anatomy.
- Maintain the disclaimer that the atlas is educational and not diagnostic.

## Development

```bash
python3 -m http.server 8000 --directory dist
```

Open <http://localhost:8000>, make a focused change, and verify the relevant interactions before submitting a pull request.

