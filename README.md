# NECOS: NEws and COmments in Spanish


We present the NEws and COmments in Spanish (NECOS) corpus, a collection of Spanish constructive comments posted in response to news. The news are published in the *El Mundo* newspaper in a period between April 3 and April 30, 2018. The corpus is composed of a total of 10 news and 1,419 comments. Three annotators have manually labeled NECOS with an average Cohen's kappa of 78.97. Our current focus is the study of constructiveness and evaluation in the comments. In order to address this goal, we propose a benchmark testing different machine learning systems based on Natural Language Processing: a traditional system and the novel Transformer-based models. Specifically, we compare multilingual models with a monolingual one trained on Spanish in order to remark the need to create resources trained on a specific language. The monolingual model fine-tuning on NECOS obtain the best result by achieving a macro-average F1 score of 77.24%.

# Citing

If you use NECOS corpus in your research, please contact with plubeda@ujaen.es to get the correct citation since the corpus is under review. 

```

@techreport{lopez-ubeda-etal-2021-necos,
  author = "L{\'o}pez-{\'U}beda, Pilar  and
      Plaza-del-Arco, Flor Miriam  and
      D{\'\i}az-Galiano, Manuel Carlos  and
      Mart{\'\i}n-Valdivia, M. Teresa",
  title       = "NECOS: An annotated corpus to identify constructive news comments in Spanish",
  journal     = {Procesamiento del Lenguaje Natural},
  volume      = {66},
  year        = "2021"
}
