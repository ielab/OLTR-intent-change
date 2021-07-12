# OLTR-intent-change

This is the dataset repo for our SIGIR2021 paper [How do Online Learning to Rank Methods Adapt to Changes of Intent?](http://ielab.io/publications/arvin-2021-intent-change.html).

In the `/datasets` folder, we provide the learning to rank dataset that we create for TREC Web Track 2009 to 2012 collection.

In the `/intents` folder, we provided qrels that judged for each intent (e.g. `1.txt` contains relevance judgments for the users with intent 1). Note, intent 0 (`0.txt`) is the judgment that combined for all the intents.

These dataset and qrels mentioned above follow the standard TREC style, so you should be able to directly use our provided LTR dataset and intent qrels in your OLTR experiments.

We also provide the original qrels for the TREC Web Track diversity task in folder `/trec_qrels`. If you interested in how we create intent judgments, you can run and investigate `python create_intent_qrel.py`

For our the experiments code, we refere to our OLTR codebase repo: [https://github.com/ielab/OLTR](https://github.com/ielab/OLTR) 