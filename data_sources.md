# Data Sources

A starting point for finding data for your project, not a complete list. Before using any dataset, check its licence and terms of use, and keep in mind that many of these resources contain hateful or offensive content.

## General dataset repositories

Search these repositories with keywords such as "hate speech", "toxicity", "parliament" or a platform name.

- [Zenodo](https://zenodo.org/): open research data repository; many NLP datasets are deposited here
- [Harvard Dataverse](https://dataverse.harvard.edu/): social science data repository, including replication data for many papers
- [Hugging Face Datasets](https://huggingface.co/datasets): NLP datasets that can be loaded directly in Python with the `datasets` library
- [Kaggle Datasets](https://www.kaggle.com/datasets): user-uploaded datasets and competition data
- [R-text-data](https://github.com/EmilHvitfeldt/R-text-data): list of text datasets available as R packages or downloads

## Online harm datasets

For many more datasets, search the catalogue by Vidgen and Derczynski (reading from Session 3):

- [hatespeechdata.com](https://hatespeechdata.com/): catalogue of hate speech and abusive language datasets, searchable by language and platform

A few well-known examples:

- [Davidson et al. (2017)](https://github.com/t-davidson/hate-speech-and-offensive-language): about 25,000 English tweets labelled as hate speech, offensive or neither
- [GermEval 2018](https://github.com/uds-lsv/GermEval-2018-Data): German tweets labelled for offensive language (shared task data); data for [GermEval 2019](https://fz.h-da.de/iggsa/data) is on the organisers' site
- [Measuring Hate Speech](https://huggingface.co/datasets/ucberkeley-dlab/measuring-hate-speech): 39,565 comments annotated by 7,912 annotators, with a continuous hate speech score and target identity groups
- [Civil Comments](https://huggingface.co/datasets/google/civil_comments): English comments from news sites (2015-2017) with toxicity labels added by Jigsaw
- [EDOS](https://github.com/rewire-online/edos): English Gab and Reddit posts annotated for sexism (SemEval 2023 Task 10)

## Social media and online platforms

- [Reddit API](https://www.reddit.com/dev/api/): official API documentation; use is subject to Reddit's [Data API Terms](https://redditinc.com/policies/data-api-terms)
- [Bluesky API](https://bsky.network/docs/bluesky-api): documentation for the Bluesky API and the AT Protocol, including real-time streaming of public posts
- [YouTube Data API](https://developers.google.com/youtube/v3): access to videos, channels and comments (Google API key needed)
- [Pushshift Telegram Dataset](https://zenodo.org/records/3607497): 317M messages from 28K public Telegram channels (Baumgartner et al. 2020)
- [4chan /pol/ Dataset](https://zenodo.org/records/3606810): 3.5 years of threads from 4chan's /pol/ board (Papasavva et al. 2020)

Access to some platforms is restricted. The [TikTok Research API](https://developers.tiktok.com/products/research-api/), for example, requires an application from an academic institution and a research proposal.

## Political and legal text

- [ParlSpeech V2](https://doi.org/10.7910/DVN/L4OAKN): 6.3 million parliamentary speeches from nine democracies (Rauh and Schwalbach 2020)
- [ParlaMint 5.0](https://www.clarin.si/repository/xmlui/handle/11356/2004): comparable corpora of parliamentary debates from 29 European countries and regions
- [Deutscher Bundestag Open Data](https://www.bundestag.de/services/opendata): all plenary protocols since 1949 as XML and JSON (German)
- [Open Legal Data](https://de.openlegaldata.io/): German court decisions and laws, with API and bulk downloads (German)
- [CourtListener](https://www.courtlistener.com/): US court opinions and oral argument recordings, with API and bulk data
