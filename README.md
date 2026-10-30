# FlipJev project page

Source of the project page for [*FlipJev: Fast Black-Box Red Teaming Finds Universal Adversarial Suffixes for Typed Decision Models*](https://arxiv.org/abs/2610.38895), served at <https://flipjev.github.io>.

The page is static HTML, CSS and JavaScript with no build step. To preview it locally:

```bash
python3 -m http.server 8000
```

and open <http://localhost:8000>.

`assets/js/data.js` holds every measured value that the page shows: the probabilities and scores of the examples, the success rates, the query counts of the per-document searches and the transfer matrix. All of them come from the result files of the [code repository](https://github.com/SaFo-Lab/FlipJev).
