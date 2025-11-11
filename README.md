# perfect-me

How good is your life?

## Questions

### Template

```json
{
  "title": "",
  "points": 0,
  "yesIsBad": false,
  "answers": [
    {
      "title": "",
      "points": 0
    }
  ],
  "id": "",
  "lockedBy": "",
  "trick": ""
}
```

- **title** : Title of the question
- **points** : Points to remove is the result is bad
- **yesIsBad** : Defaults to true if not specified, define if the answer "yes" should remove the points or not
- **answers** : List of answers to show if the question is not a closed one. This is not compatible with _points_ and _yesIsBad_ fields.
- **id** : custom id to reference the question to others.
- **lockedBy** : If this field is referenced, the question will not appear if the reference answer is not _true_.
- **trick** : If this field is referenced, points will be removed if the answer to the question and the reference is _true_.

Fields depending on a true answer is compatible with _yesIsBad_ field to expect a _false_ result.
