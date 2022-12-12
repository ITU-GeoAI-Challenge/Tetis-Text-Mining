[![tetis](https://www.umr-tetis.fr/images/logo-header-tetis.png)](https://www.umr-tetis.fr/index.php/fr/)

# TETIS Text Mining contribution to the GeoChallenge: Location Mention Recognition

We are pleased to share our results from our participation to the GeoAI challenge ! 

In this repository, you'll find:

+ Our presentation to the final event of this challenge: [slides](docs/presentation-tetis.pdf)
+ A jupyter notebook showing how to re-use our model: [notebook](src/usage_example.ipynb)

Our model could be easily downloaded using the HuggingFace library :huggingface:
```python
from transformers import AutoTokenizer, AutoModelForTokenClassification

tokenizer = AutoTokenizer.from_pretrained("rdecoupes/tetis-geochallenge")
model = AutoModelForTokenClassification.from_pretrained("rdecoupes/tetis-geochallenge")
```

## Authors
| Name | Github            |
|------|-------------------|
| Rémy Decoupes | [@remydecoupes](https://github.com/remydecoupes) |
| Nejat Arinik | [@arinik9](https://github.com/arinik9)      |
| Roberto Interdonato | [@interdonatos](https://github.com/interdonatos) |

For more information, you can visit our [repository](https://github.com/tetis-geochallenge-lmr-2022)
