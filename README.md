# French Product Reviews Sentiment Dataset

## Description
1,214 French product reviews labeled with:
- Original codes (OR=Positive, CG=Negative)
- Clear sentiment labels (positive/negative)
- Diverse product categories

## Structure
| Column | Description |
|--------|-------------|
| text_  | Review text in French |
| label  | Original code (OR/CG) |
| review | Clean sentiment (positive/negative) |

## Usage
```python
import pandas as pd
reviews = pd.read_excel('data/french_reviews_with_sentiment.xlsx')
Statistics
Positive: 58% (OR)

Negative: 42% (CG)

Contact
marwanhamdaoui2020@gmail.com
