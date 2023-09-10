# Recognition of Counterfactual Statements in Turkish

We have studied counterfactual statement recognition as a sentence-level binary classification problem in the Turkish language. 

In this repository, we publish, 
1. The first-ever Turkish counterfactual recognition dataset (TRCD),
2. Turkish counterfactual clue phrases (CP),
3. TRCD annotation guidelines,
4. Classifier model fine-tuning scripts of our experiments in _the paper_.

---

## TRCD Statistics

### Class Distribution in TRCD
| **Dataset** | **Positive** | **Negative** | **Total** | **CF %** |
| :---------- | :----------: | :----------: | :-------: | :------: |
| TRCD        | 640          | 4360         | 5000      | 12\.8    |
| TRCD w/ CP  | 615          | 1885         | 2500      | 24\.6    |
| TRCD w/o CP | 25           | 2475         | 2500      | 1\.0     |

---

### Class Distribution of Clue Phrases
| **Clue phrase** | **\# in Pos.** | **\# in Neg.** | **% in Pos.** | **% in Neg.** | **% in TRCD** |
| :-------------- | :------------: | :------------: | :-----------: | :-----------: | :-----------: |
| -sA             | 22             | 571            | 3\.44         | 13\.1         | 11\.86        |
| -AmAzdI         | 28             | 330            | 4\.38         | 7\.57         | 7\.16         |
| -ArdI           | 32             | 321            | 5\.0          | 7\.36         | 7\.06         |
| -mAzDI          | 42             | 254            | 6\.56         | 5\.83         | 5\.92         |
| -mAlIydI        | 112            | 173            | 17\.5         | 3\.97         | 5\.7          |
| -AbilArdI       | 83             | 192            | 12\.97        | 4\.4          | 5\.5          |
| -AydI           | 194            | 23             | 30\.31        | 0\.53         | 4\.34         |
| -sAlArDI        | 83             | 6              | 12\.97        | 0\.14         | 1\.78         |
| -AymIş          | 16             | 2              | 2\.5          | 0\.05         | 0\.36         |
| -AcAkDI         | 3              | 13             | 0\.47         | 0\.3          | 0\.32         |
| **Total**       | 615            | 1885           | 96\.1         | 43\.2         | 50\.0         |
