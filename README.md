# OSN-515

The OSN-515 dataset is a dataset designed for open-world attribute extraction from sparse corpora. It contains 515 samples from APR News, and each sample includes raw text, preprocessed typed text, and corresponding attribute triplet labels. The dataset can be used in text analysis, information extraction, and semantic understanding. The corpora is **sparse** for attribute extraction while a large number of instances do not include valuable attribute triplets. The dataset aims to boost the study of attribute extraction with noises in the real world.

## Example

```json
{
    "id": 6,
    "text": "Paul spokesman Sergio Gor indicated as much when asked for a comment on the book .",
    "typed_text": "<PERSON.POLITICIAN.SENATOR>Paul</PERSON.POLITICIAN.SENATOR> spokesman <PERSON.POLITICIAN.SPOKESPERSON>Sergio Gor</PERSON.POLITICIAN.SPOKESPERSON> indicated as much when asked for a comment on the book .",
    "attribute triplets": [
      "Paul spokesman Sergio Gor",
      "Sergio Gor occupation spokesman"
    ]
}
```
