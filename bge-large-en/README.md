---
tags:
- mteb
- sentence-transfomres
- transformers
model-index:
- name: bge-large-en
  results:
  - task:
      type: Classification
    dataset:
      type: mteb/amazon_counterfactual
      name: MTEB AmazonCounterfactualClassification (en)
      config: en
      split: test
      revision: e8379541af4e31359cca9fbcf4b00f2671dba205
    metrics:
    - type: accuracy
      value: 76.94029850746269
    - type: ap
      value: 40.00228964744091
    - type: f1
      value: 70.86088267934595
  - task:
      type: Classification
    dataset:
      type: mteb/amazon_polarity
      name: MTEB AmazonPolarityClassification
      config: default
      split: test
      revision: e2d317d38cd51312af73b3d32a06d1a08b442046
    metrics:
    - type: accuracy
      value: 91.93745
    - type: ap
      value: 88.24758534667426
    - type: f1
      value: 91.91033034217591
  - task:
      type: Classification
    dataset:
      type: mteb/amazon_reviews_multi
      name: MTEB AmazonReviewsClassification (en)
      config: en
      split: test
      revision: 1399c76144fd37290681b995c656ef9b2e06e26d
    metrics:
    - type: accuracy
      value: 46.158
    - type: f1
      value: 45.78935185074774
  - task:
      type: Retrieval
    dataset:
      type: arguana
      name: MTEB ArguAna
      config: default
      split: test
      revision: None
    metrics:
    - type: map_at_1
      value: 39.972
    - type: map_at_10
      value: 54.874
    - type: map_at_100
      value: 55.53399999999999
    - type: map_at_1000
      value: 55.539
    - type: map_at_3
      value: 51.031000000000006
    - type: map_at_5
      value: 53.342999999999996
    - type: mrr_at_1
      value: 40.541
    - type: mrr_at_10
      value: 55.096000000000004
    - type: mrr_at_100
      value: 55.75599999999999
    - type: mrr_at_1000
      value: 55.761
    - type: mrr_at_3
      value: 51.221000000000004
    - type: mrr_at_5
      value: 53.568000000000005
    - type: ndcg_at_1
      value: 39.972
    - type: ndcg_at_10
      value: 62.456999999999994
    - type: ndcg_at_100
      value: 65.262
    - type: ndcg_at_1000
      value: 65.389
    - type: ndcg_at_3
      value: 54.673
    - type: ndcg_at_5
      value: 58.80499999999999
    - type: precision_at_1
      value: 39.972
    - type: precision_at_10
      value: 8.634
    - type: precision_at_100
      value: 0.9860000000000001
    - type: precision_at_1000
      value: 0.1
    - type: precision_at_3
      value: 21.740000000000002
    - type: precision_at_5
      value: 15.036
    - type: recall_at_1
      value: 39.972
    - type: recall_at_10
      value: 86.344
    - type: recall_at_100
      value: 98.578
    - type: recall_at_1000
      value: 99.57300000000001
    - type: recall_at_3
      value: 65.22
    - type: recall_at_5
      value: 75.178
  - task:
      type: Clustering
    dataset:
      type: mteb/arxiv-clustering-p2p
      name: MTEB ArxivClusteringP2P
      config: default
      split: test
      revision: a122ad7f3f0291bf49cc6f4d32aa80929df69d5d
    metrics:
    - type: v_measure
      value: 48.94652870403906
  - task:
      type: Clustering
    dataset:
      type: mteb/arxiv-clustering-s2s
      name: MTEB ArxivClusteringS2S
      config: default
      split: test
      revision: f910caf1a6075f7329cdf8c1a6135696f37dbd53
    metrics:
    - type: v_measure
      value: 43.17257160340209
  - task:
      type: Reranking
    dataset:
      type: mteb/askubuntudupquestions-reranking
      name: MTEB AskUbuntuDupQuestions
      config: default
      split: test
      revision: 2000358ca161889fa9c082cb41daa8dcfb161a54
    metrics:
    - type: map
      value: 63.97867370559182
    - type: mrr
      value: 77.00820032537484
  - task:
      type: STS
    dataset:
      type: mteb/biosses-sts
      name: MTEB BIOSSES
      config: default
      split: test
      revision: d3fb88f8f02e40887cd149695127462bbcf29b4a
    metrics:
    - type: cos_sim_pearson
      value: 80.00986015960616
    - type: cos_sim_spearman
      value: 80.36387933827882
    - type: euclidean_pearson
      value: 80.32305287257296
    - type: euclidean_spearman
      value: 82.0524720308763
    - type: manhattan_pearson
      value: 80.19847473906454
    - type: manhattan_spearman
      value: 81.87957652506985
  - task:
      type: Classification
    dataset:
      type: mteb/banking77
      name: MTEB Banking77Classification
      config: default
      split: test
      revision: 0fd18e25b25c072e09e0d92ab615fda904d66300
    metrics:
    - type: accuracy
      value: 88.00000000000001
    - type: f1
      value: 87.99039027511853
  - task:
      type: Clustering
    dataset:
      type: mteb/biorxiv-clustering-p2p
      name: MTEB BiorxivClusteringP2P
      config: default
      split: test
      revision: 65b79d1d13f80053f67aca9498d9402c2d9f1f40
    metrics:
    - type: v_measure
      value: 41.36932844640705
  - task:
      type: Clustering
    dataset:
      type: mteb/biorxiv-clustering-s2s
      name: MTEB BiorxivClusteringS2S
      config: default
      split: test
      revision: 258694dd0231531bc1fd9de6ceb52a0853c6d908
    metrics:
    - type: v_measure
      value: 38.34983239611985
  - task:
      type: Retrieval
    dataset:
      type: BeIR/cqadupstack
      name: MTEB CQADupstackAndroidRetrieval
      config: default
      split: test
      revision: None
    metrics:
    - type: map_at_1
      value: 32.257999999999996
    - type: map_at_10
      value: 42.937
    - type: map_at_100
      value: 44.406
    - type: map_at_1000
      value: 44.536
    - type: map_at_3
      value: 39.22
    - type: map_at_5
      value: 41.458
    - type: mrr_at_1
      value: 38.769999999999996
    - type: mrr_at_10
      value: 48.701
    - type: mrr_at_100
      value: 49.431000000000004
    - type: mrr_at_1000
      value: 49.476
    - type: mrr_at_3
      value: 45.875
    - type: mrr_at_5
      value: 47.67
    - type: ndcg_at_1
      value: 38.769999999999996
    - type: ndcg_at_10
      value: 49.35
    - type: ndcg_at_100
      value: 54.618
    - type: ndcg_at_1000
      value: 56.655
    - type: ndcg_at_3
      value: 43.826
    - type: ndcg_at_5
      value: 46.72
    - type: precision_at_1
      value: 38.769999999999996
    - type: precision_at_10
      value: 9.328
    - type: precision_at_100
      value: 1.484
    - type: precision_at_1000
      value: 0.196
    - type: precision_at_3
      value: 20.649
    - type: precision_at_5
      value: 15.25
    - type: recall_at_1
      value: 32.257999999999996
    - type: recall_at_10
      value: 61.849
    - type: recall_at_100
      value: 83.70400000000001
    - type: recall_at_1000
      value: 96.344
    - type: recall_at_3
      value: 46.037
    - type: recall_at_5
      value: 53.724000000000004
  - task:
      type: Retrieval
    dataset:
      type: BeIR/cqadupstack
      name: MTEB CQADupstackEnglishRetrieval
      config: default
      split: test
      revision: None
    metrics:
    - type: map_at_1
      value: 32.979
    - type: map_at_10
      value: 43.376999999999995
    - type: map_at_100
      value: 44.667
    - type: map_at_1000
      value: 44.794
    - type: map_at_3
      value: 40.461999999999996
    - type: map_at_5
      value: 42.138
    - type: mrr_at_1
      value: 41.146
    - type: mrr_at_10
      value: 49.575
    - type: mrr_at_100
      value: 50.187000000000005
    - type: mrr_at_1000
      value: 50.231
    - type: mrr_at_3
      value: 47.601
    - type: mrr_at_5
      value: 48.786
    - type: ndcg_at_1
      value: 41.146
    - type: ndcg_at_10
      value: 48.957
    - type: ndcg_at_100
      value: 53.296
    - type: ndcg_at_1000
      value: 55.254000000000005
    - type: ndcg_at_3
      value: 45.235
    - type: ndcg_at_5
      value: 47.014
    - type: precision_at_1
      value: 41.146
    - type: precision_at_10
      value: 9.107999999999999
    - type: precision_at_100
      value: 1.481
    - type: precision_at_1000
      value: 0.193
    - type: precision_at_3
      value: 21.783
    - type: precision_at_5
      value: 15.274
    - type: recall_at_1
      value: 32.979
    - type: recall_at_10
      value: 58.167
    - type: recall_at_100
      value: 76.374
    - type: recall_at_1000
      value: 88.836
    - type: recall_at_3
      value: 46.838
    - type: recall_at_5
      value: 52.006
  - task:
      type: Retrieval
    dataset:
      type: BeIR/cqadupstack
      name: MTEB CQADupstackGamingRetrieval
      config: default
      split: test
      revision: None
    metrics:
    - type: map_at_1
      value: 40.326
    - type: map_at_10
      value: 53.468
    - type: map_at_100
      value: 54.454
    - type: map_at_1000
      value: 54.508
    - type: map_at_3
      value: 50.12799999999999
    - type: map_at_5
      value: 51.991
    - type: mrr_at_1
      value: 46.394999999999996
    - type: mrr_at_10
      value: 57.016999999999996
    - type: mrr_at_100
      value: 57.67099999999999
    - type: mrr_at_1000
      value: 57.699999999999996
    - type: mrr_at_3
      value: 54.65
    - type: mrr_at_5
      value: 56.101
    - type: ndcg_at_1
      value: 46.394999999999996
    - type: ndcg_at_10
      value: 59.507
    - type: ndcg_at_100
      value: 63.31099999999999
    - type: ndcg_at_1000
      value: 64.388
    - type: ndcg_at_3
      value: 54.04600000000001
    - type: ndcg_at_5
      value: 56.723
    - type: precision_at_1
      value: 46.394999999999996
    - type: precision_at_10
      value: 9.567
    - type: precision_at_100
      value: 1.234
    - type: precision_at_1000
      value: 0.13699999999999998
    - type: precision_at_3
      value: 24.117
    - type: precision_at_5
      value: 16.426
    - type: recall_at_1
      value: 40.326
    - type: recall_at_10
      value: 73.763
    - type: recall_at_100
      value: 89.927
    - type: recall_at_1000
      value: 97.509
    - type: recall_at_3
      value: 59.34
    - type: recall_at_5
      value: 65.915
  - task:
      type: Retrieval
    dataset:
      type: BeIR/cqadupstack
      name: MTEB CQADupstackGisRetrieval
      config: default
      split: test
      revision: None
    metrics:
    - type: map_at_1
      value: 26.661
    - type: map_at_10
      value: 35.522
    - type: map_at_100
      value: 36.619
    - type: map_at_1000
      value: 36.693999999999996
    - type: map_at_3
      value: 33.154
    - type: map_at_5
      value: 34.353
    - type: mrr_at_1
      value: 28.362
    - type: mrr_at_10
      value: 37.403999999999996
    - type: mrr_at_100
      value: 38.374
    - type: mrr_at_1000
      value: 38.428000000000004
    - type: mrr_at_3
      value: 35.235
    - type: mrr_at_5
      value: 36.269
    - type: ndcg_at_1
      value: 28.362
    - type: ndcg_at_10
      value: 40.431
    - type: ndcg_at_100
      value: 45.745999999999995
    - type: ndcg_at_1000
      value: 47.493
    - type: ndcg_at_3
      value: 35.733
    - type: ndcg_at_5
      value: 37.722
    - type: precision_at_1
      value: 28.362
    - type: precision_at_10
      value: 6.101999999999999
    - type: precision_at_100
      value: 0.922
    - type: precision_at_1000
      value: 0.11100000000000002
    - type: precision_at_3
      value: 15.140999999999998
    - type: precision_at_5
      value: 10.305
    - type: recall_at_1
      value: 26.661
    - type: recall_at_10
      value: 53.675
    - type: recall_at_100
      value: 77.891
    - type: recall_at_1000
      value: 90.72
    - type: recall_at_3
      value: 40.751
    - type: recall_at_5
      value: 45.517
  - task:
      type: Retrieval
    dataset:
      type: BeIR/cqadupstack
      name: MTEB CQADupstackMathematicaRetrieval
      config: default
      split: test
      revision: None
    metrics:
    - type: map_at_1
      value: 18.886
    - type: map_at_10
      value: 27.288
    - type: map_at_100
      value: 28.327999999999996
    - type: map_at_1000
      value: 28.438999999999997
    - type: map_at_3
      value: 24.453
    - type: map_at_5
      value: 25.959
    - type: mrr_at_1
      value: 23.134
    - type: mrr_at_10
      value: 32.004
    - type: mrr_at_100
      value: 32.789
    - type: mrr_at_1000
      value: 32.857
    - type: mrr_at_3
      value: 29.084
    - type: mrr_at_5
      value: 30.614
    - type: ndcg_at_1
      value: 23.134
    - type: ndcg_at_10
      value: 32.852
    - type: ndcg_at_100
      value: 37.972
    - type: ndcg_at_1000
      value: 40.656
    - type: ndcg_at_3
      value: 27.435
    - type: ndcg_at_5
      value: 29.823
    - type: precision_at_1
      value: 23.134
    - type: precision_at_10
      value: 6.032
    - type: precision_at_100
      value: 0.9950000000000001
    - type: precision_at_1000
      value: 0.136
    - type: precision_at_3
      value: 13.017999999999999
    - type: precision_at_5
      value: 9.501999999999999
    - type: recall_at_1
      value: 18.886
    - type: recall_at_10
      value: 45.34
    - type: recall_at_100
      value: 67.947
    - type: recall_at_1000
      value: 86.924
    - type: recall_at_3
      value: 30.535
    - type: recall_at_5
      value: 36.451
  - task:
      type: Retrieval
    dataset:
      type: BeIR/cqadupstack
      name: MTEB CQADupstackPhysicsRetrieval
      config: default
      split: test
      revision: None
    metrics:
    - type: map_at_1
      value: 28.994999999999997
    - type: map_at_10
      value: 40.04
    - type: map_at_100
      value: 41.435
    - type: map_at_1000
      value: 41.537
    - type: map_at_3
      value: 37.091
    - type: map_at_5
      value: 38.802
    - type: mrr_at_1
      value: 35.034
    - type: mrr_at_10
      value: 45.411
    - type: mrr_at_100
      value: 46.226
    - type: mrr_at_1000
      value: 46.27
    - type: mrr_at_3
      value: 43.086
    - type: mrr_at_5
      value: 44.452999999999996
    - type: ndcg_at_1
      value: 35.034
    - type: ndcg_at_10
      value: 46.076
    - type: ndcg_at_100
      value: 51.483000000000004
    - type: ndcg_at_1000
      value: 53.433
    - type: ndcg_at_3
      value: 41.304
    - type: ndcg_at_5
      value: 43.641999999999996
    - type: precision_at_1
      value: 35.034
    - type: precision_at_10
      value: 8.258000000000001
    - type: precision_at_100
      value: 1.268
    - type: precision_at_1000
      value: 0.161
    - type: precision_at_3
      value: 19.57
    - type: precision_at_5
      value: 13.782
    - type: recall_at_1
      value: 28.994999999999997
    - type: recall_at_10
      value: 58.538000000000004
    - type: recall_at_100
      value: 80.72399999999999
    - type: recall_at_1000
      value: 93.462
    - type: recall_at_3
      value: 45.199
    - type: recall_at_5
      value: 51.237
  - task:
      type: Retrieval
    dataset:
      type: BeIR/cqadupstack
      name: MTEB CQADupstackProgrammersRetrieval
      config: default
      split: test
      revision: None
    metrics:
    - type: map_at_1
      value: 24.795
    - type: map_at_10
      value: 34.935
    - type: map_at_100
      value: 36.306
    - type: map_at_1000
      value: 36.417
    - type: map_at_3
      value: 31.831
    - type: map_at_5
      value: 33.626
    - type: mrr_at_1
      value: 30.479
    - type: mrr_at_10
      value: 40.225
    - type: mrr_at_100
      value: 41.055
    - type: mrr_at_1000
      value: 41.114
    - type: mrr_at_3
      value: 37.538
    - type: mrr_at_5
      value: 39.073
    - type: ndcg_at_1
      value: 30.479
    - type: ndcg_at_10
      value: 40.949999999999996
    - type: ndcg_at_100
      value: 46.525
    - type: ndcg_at_1000
      value: 48.892
    - type: ndcg_at_3
      value: 35.79
    - type: ndcg_at_5
      value: 38.237
    - type: precision_at_1
      value: 30.479
    - type: precision_at_10
      value: 7.6259999999999994
    - type: precision_at_100
      value: 1.203
    - type: precision_at_1000
      value: 0.157
    - type: precision_at_3
      value: 17.199
    - type: precision_at_5
      value: 12.466000000000001
    - type: recall_at_1
      value: 24.795
    - type: recall_at_10
      value: 53.421
    - type: recall_at_100
      value: 77.189
    - type: recall_at_1000
      value: 93.407
    - type: recall_at_3
      value: 39.051
    - type: recall_at_5
      value: 45.462
  - task:
      type: Retrieval
    dataset:
      type: BeIR/cqadupstack
      name: MTEB CQADupstackRetrieval
      config: default
      split: test
      revision: None
    metrics:
    - type: map_at_1
      value: 26.853499999999997
    - type: map_at_10
      value: 36.20433333333333
    - type: map_at_100
      value: 37.40391666666667
    - type: map_at_1000
      value: 37.515
    - type: map_at_3
      value: 33.39975
    - type: map_at_5
      value: 34.9665
    - type: mrr_at_1
      value: 31.62666666666667
    - type: mrr_at_10
      value: 40.436749999999996
    - type: mrr_at_100
      value: 41.260333333333335
    - type: mrr_at_1000
      value: 41.31525
    - type: mrr_at_3
      value: 38.06733333333332
    - type: mrr_at_5
      value: 39.41541666666667
    - type: ndcg_at_1
      value: 31.62666666666667
    - type: ndcg_at_10
      value: 41.63341666666667
    - type: ndcg_at_100
      value: 46.704166666666666
    - type: ndcg_at_1000
      value: 48.88483333333335
    - type: ndcg_at_3
      value: 36.896
    - type: ndcg_at_5
      value: 39.11891666666667
    - type: precision_at_1
      value: 31.62666666666667
    - type: precision_at_10
      value: 7.241083333333333
    - type: precision_at_100
      value: 1.1488333333333334
    - type: precision_at_1000
      value: 0.15250000000000002
    - type: precision_at_3
      value: 16.908333333333335
    - type: precision_at_5
      value: 11.942833333333333
    - type: recall_at_1
      value: 26.853499999999997
    - type: recall_at_10
      value: 53.461333333333336
    - type: recall_at_100
      value: 75.63633333333333
    - type: recall_at_1000
      value: 90.67016666666666
    - type: recall_at_3
      value: 40.24241666666667
    - type: recall_at_5
      value: 45.98608333333333
  - task:
      type: Retrieval
    dataset:
      type: BeIR/cqadupstack
      name: MTEB CQADupstackStatsRetrieval
      config: default
      split: test
      revision: None
    metrics:
    - type: map_at_1
      value: 25.241999999999997
    - type: map_at_10
      value: 31.863999999999997
    - type: map_at_100
      value: 32.835
    - type: map_at_1000
      value: 32.928000000000004
    - type: map_at_3
      value: 29.694
    - type: map_at_5
      value: 30.978
    - type: mrr_at_1
      value: 28.374
    - type: mrr_at_10
      value: 34.814
    - type: mrr_at_100
      value: 35.596
    - type: mrr_at_1000
      value: 35.666
    - type: mrr_at_3
      value: 32.745000000000005
    - type: mrr_at_5
      value: 34.049
    - type: ndcg_at_1
      value: 28.374
    - type: ndcg_at_10
      value: 35.969
    - type: ndcg_at_100
      value: 40.708
    - type: ndcg_at_1000
      value: 43.08
    - type: ndcg_at_3
      value: 31.968999999999998
    - type: ndcg_at_5
      value: 34.069
    - type: precision_at_1
      value: 28.374
    - type: precision_at_10
      value: 5.583
    - type: precision_at_100
      value: 0.8630000000000001
    - type: precision_at_1000
      value: 0.11299999999999999
    - type: precision_at_3
      value: 13.547999999999998
    - type: precision_at_5
      value: 9.447999999999999
    - type: recall_at_1
      value: 25.241999999999997
    - type: recall_at_10
      value: 45.711
    - type: recall_at_100
      value: 67.482
    - type: recall_at_1000
      value: 85.13300000000001
    - type: recall_at_3
      value: 34.622
    - type: recall_at_5
      value: 40.043
  - task:
      type: Retrieval
    dataset:
      type: BeIR/cqadupstack
      name: MTEB CQADupstackTexRetrieval
      config: default
      split: test
      revision: None
    metrics:
    - type: map_at_1
      value: 17.488999999999997
    - type: map_at_10
      value: 25.142999999999997
    - type: map_at_100
      value: 26.244
    - type: map_at_1000
      value: 26.363999999999997
    - type: map_at_3
      value: 22.654
    - type: map_at_5
      value: 24.017
    - type: mrr_at_1
      value: 21.198
    - type: mrr_at_10
      value: 28.903000000000002
    - type: mrr_at_100
      value: 29.860999999999997
    - type: mrr_at_1000
      value: 29.934
    - type: mrr_at_3
      value: 26.634999999999998
    - type: mrr_at_5
      value: 27.903
    - type: ndcg_at_1
      value: 21.198
    - type: ndcg_at_10
      value: 29.982999999999997
    - type: ndcg_at_100
      value: 35.275
    - type: ndcg_at_1000
      value: 38.074000000000005
    - type: ndcg_at_3
      value: 25.502999999999997
    - type: ndcg_at_5
      value: 27.557
    - type: precision_at_1
      value: 21.198
    - type: precision_at_10
      value: 5.502
    - type: precision_at_100
      value: 0.942
    - type: precision_at_1000
      value: 0.136
    - type: precision_at_3
      value: 12.044
    - type: precision_at_5
      value: 8.782
    - type: recall_at_1
      value: 17.488999999999997
    - type: recall_at_10
      value: 40.821000000000005
    - type: recall_at_100
      value: 64.567
    - type: recall_at_1000
      value: 84.452
    - type: recall_at_3
      value: 28.351
    - type: recall_at_5
      value: 33.645
  - task:
      type: Retrieval
    dataset:
      type: BeIR/cqadupstack
      name: MTEB CQADupstackUnixRetrieval
      config: default
      split: test
      revision: None
    metrics:
    - type: map_at_1
      value: 27.066000000000003
    - type: map_at_10
      value: 36.134
    - type: map_at_100
      value: 37.285000000000004
    - type: map_at_1000
      value: 37.389
    - type: map_at_3
      value: 33.522999999999996
    - type: map_at_5
      value: 34.905
    - type: mrr_at_1
      value: 31.436999999999998
    - type: mrr_at_10
      value: 40.225
    - type: mrr_at_100
      value: 41.079
    - type: mrr_at_1000
      value: 41.138000000000005
    - type: mrr_at_3
      value: 38.074999999999996
    - type: mrr_at_5
      value: 39.190000000000005
    - type: ndcg_at_1
      value: 31.436999999999998
    - type: ndcg_at_10
      value: 41.494
    - type: ndcg_at_100
      value: 46.678999999999995
    - type: ndcg_at_1000
      value: 48.964
    - type: ndcg_at_3
      value: 36.828
    - type: ndcg_at_5
      value: 38.789
    - type: precision_at_1
      value: 31.436999999999998
    - type: precision_at_10
      value: 6.931
    - type: precision_at_100
      value: 1.072
    - type: precision_at_1000
      value: 0.13799999999999998
    - type: precision_at_3
      value: 16.729
    - type: precision_at_5
      value: 11.567
    - type: recall_at_1
      value: 27.066000000000003
    - type: recall_at_10
      value: 53.705000000000005
    - type: recall_at_100
      value: 75.968
    - type: recall_at_1000
      value: 91.937
    - type: recall_at_3
      value: 40.865
    - type: recall_at_5
      value: 45.739999999999995
  - task:
      type: Retrieval
    dataset:
      type: BeIR/cqadupstack
      name: MTEB CQADupstackWebmastersRetrieval
      config: default
      split: test
      revision: None
    metrics:
    - type: map_at_1
      value: 24.979000000000003
    - type: map_at_10
      value: 32.799
    - type: map_at_100
      value: 34.508
    - type: map_at_1000
      value: 34.719
    - type: map_at_3
      value: 29.947000000000003
    - type: map_at_5
      value: 31.584
    - type: mrr_at_1
      value: 30.237000000000002
    - type: mrr_at_10
      value: 37.651
    - type: mrr_at_100
      value: 38.805
    - type: mrr_at_1000
      value: 38.851
    - type: mrr_at_3
      value: 35.046
    - type: mrr_at_5
      value: 36.548
    - type: ndcg_at_1
      value: 30.237000000000002
    - type: ndcg_at_10
      value: 38.356
    - type: ndcg_at_100
      value: 44.906
    - type: ndcg_at_1000
      value: 47.299
    - type: ndcg_at_3
      value: 33.717999999999996
    - type: ndcg_at_5
      value: 35.946
    - type: precision_at_1
      value: 30.237000000000002
    - type: precision_at_10
      value: 7.292
    - type: precision_at_100
      value: 1.496
    - type: precision_at_1000
      value: 0.23600000000000002
    - type: precision_at_3
      value: 15.547
    - type: precision_at_5
      value: 11.344
    - type: recall_at_1
      value: 24.979000000000003
    - type: recall_at_10
      value: 48.624
    - type: recall_at_100
      value: 77.932
    - type: recall_at_1000
      value: 92.66499999999999
    - type: recall_at_3
      value: 35.217
    - type: recall_at_5
      value: 41.394
  - task:
      type: Retrieval
    dataset:
      type: BeIR/cqadupstack
      name: MTEB CQADupstackWordpressRetrieval
      config: default
      split: test
      revision: None
    metrics:
    - type: map_at_1
      value: 22.566
    - type: map_at_10
      value: 30.945
    - type: map_at_100
      value: 31.759999999999998
    - type: map_at_1000
      value: 31.855
    - type: map_at_3
      value: 28.64
    - type: map_at_5
      value: 29.787000000000003
    - type: mrr_at_1
      value: 24.954
    - type: mrr_at_10
      value: 33.311
    - type: mrr_at_100
      value: 34.050000000000004
    - type: mrr_at_1000
      value: 34.117999999999995
    - type: mrr_at_3
      value: 31.238
    - type: mrr_at_5
      value: 32.329
    - type: ndcg_at_1
      value: 24.954
    - type: ndcg_at_10
      value: 35.676
    - type: ndcg_at_100
      value: 39.931
    - type: ndcg_at_1000
      value: 42.43
    - type: ndcg_at_3
      value: 31.365
    - type: ndcg_at_5
      value: 33.184999999999995
    - type: precision_at_1
      value: 24.954
    - type: precision_at_10
      value: 5.564
    - type: precision_at_100
      value: 0.826
    - type: precision_at_1000
      value: 0.116
    - type: precision_at_3
      value: 13.555
    - type: precision_at_5
      value: 9.168
    - type: recall_at_1
      value: 22.566
    - type: recall_at_10
      value: 47.922
    - type: recall_at_100
      value: 67.931
    - type: recall_at_1000
      value: 86.653
    - type: recall_at_3
      value: 36.103
    - type: recall_at_5
      value: 40.699000000000005
  - task:
      type: Retrieval
    dataset:
      type: climate-fever
      name: MTEB ClimateFEVER
      config: default
      split: test
      revision: None
    metrics:
    - type: map_at_1
      value: 16.950000000000003
    - type: map_at_10
      value: 28.612
    - type: map_at_100
      value: 30.476999999999997
    - type: map_at_1000
      value: 30.674
    - type: map_at_3
      value: 24.262
    - type: map_at_5
      value: 26.554
    - type: mrr_at_1
      value: 38.241
    - type: mrr_at_10
      value: 50.43
    - type: mrr_at_100
      value: 51.059
    - type: mrr_at_1000
      value: 51.090999999999994
    - type: mrr_at_3
      value: 47.514
    - type: mrr_at_5
      value: 49.246
    - type: ndcg_at_1
      value: 38.241
    - type: ndcg_at_10
      value: 38.218
    - type: ndcg_at_100
      value: 45.003
    - type: ndcg_at_1000
      value: 48.269
    - type: ndcg_at_3
      value: 32.568000000000005
    - type: ndcg_at_5
      value: 34.400999999999996
    - type: precision_at_1
      value: 38.241
    - type: precision_at_10
      value: 11.674
    - type: precision_at_100
      value: 1.913
    - type: precision_at_1000
      value: 0.252
    - type: precision_at_3
      value: 24.387
    - type: precision_at_5
      value: 18.163
    - type: recall_at_1
      value: 16.950000000000003
    - type: recall_at_10
      value: 43.769000000000005
    - type: recall_at_100
      value: 66.875
    - type: recall_at_1000
      value: 84.92699999999999
    - type: recall_at_3
      value: 29.353
    - type: recall_at_5
      value: 35.467
  - task:
      type: Retrieval
    dataset:
      type: dbpedia-entity
      name: MTEB DBPedia
      config: default
      split: test
      revision: None
    metrics:
    - type: map_at_1
      value: 9.276
    - type: map_at_10
      value: 20.848
    - type: map_at_100
      value: 29.804000000000002
    - type: map_at_1000
      value: 31.398
    - type: map_at_3
      value: 14.886
    - type: map_at_5
      value: 17.516000000000002
    - type: mrr_at_1
      value: 71
    - type: mrr_at_10
      value: 78.724
    - type: mrr_at_100
      value: 78.976
    - type: mrr_at_1000
      value: 78.986
    - type: mrr_at_3
      value: 77.333
    - type: mrr_at_5
      value: 78.021
    - type: ndcg_at_1
      value: 57.875
    - type: ndcg_at_10
      value: 43.855
    - type: ndcg_at_100
      value: 48.99
    - type: ndcg_at_1000
      value: 56.141
    - type: ndcg_at_3
      value: 48.914
    - type: ndcg_at_5
      value: 45.961
    - type: precision_at_1
      value: 71
    - type: precision_at_10
      value: 34.575
    - type: precision_at_100
      value: 11.182
    - type: precision_at_1000
      value: 2.044
    - type: precision_at_3
      value: 52.5
    - type: precision_at_5
      value: 44.2
    - type: recall_at_1
      value: 9.276
    - type: recall_at_10
      value: 26.501
    - type: recall_at_100
      value: 55.72899999999999
    - type: recall_at_1000
      value: 78.532
    - type: recall_at_3
      value: 16.365
    - type: recall_at_5
      value: 20.154
  - task:
      type: Classification
    dataset:
      type: mteb/emotion
      name: MTEB EmotionClassification
      config: default
      split: test
      revision: 4f58c6b202a23cf9a4da393831edf4f9183cad37
    metrics:
    - type: accuracy
      value: 52.71
    - type: f1
      value: 47.74801556489574
  - task:
      type: Retrieval
    dataset:
      type: fever
      name: MTEB FEVER
      config: default
      split: test
      revision: None
    metrics:
    - type: map_at_1
      value: 73.405
    - type: map_at_10
      value: 82.822
    - type: map_at_100
      value: 83.042
    - type: map_at_1000
      value: 83.055
    - type: map_at_3
      value: 81.65299999999999
    - type: map_at_5
      value: 82.431
    - type: mrr_at_1
      value: 79.178
    - type: mrr_at_10
      value: 87.02
    - type: mrr_at_100
      value: 87.095
    - type: mrr_at_1000
      value: 87.09700000000001
    - type: mrr_at_3
      value: 86.309
    - type: mrr_at_5
      value: 86.824
    - type: ndcg_at_1
      value: 79.178
    - type: ndcg_at_10
      value: 86.72
    - type: ndcg_at_100
      value: 87.457
    - type: ndcg_at_1000
      value: 87.691
    - type: ndcg_at_3
      value: 84.974
    - type: ndcg_at_5
      value: 86.032
    - type: precision_at_1
      value: 79.178
    - type: precision_at_10
      value: 10.548
    - type: precision_at_100
      value: 1.113
    - type: precision_at_1000
      value: 0.11499999999999999
    - type: precision_at_3
      value: 32.848
    - type: precision_at_5
      value: 20.45
    - type: recall_at_1
      value: 73.405
    - type: recall_at_10
      value: 94.39699999999999
    - type: recall_at_100
      value: 97.219
    - type: recall_at_1000
      value: 98.675
    - type: recall_at_3
      value: 89.679
    - type: recall_at_5
      value: 92.392
  - task:
      type: Retrieval
    dataset:
      type: fiqa
      name: MTEB FiQA2018
      config: default
      split: test
      revision: None
    metrics:
    - type: map_at_1
      value: 22.651
    - type: map_at_10
      value: 36.886
    - type: map_at_100
      value: 38.811
    - type: map_at_1000
      value: 38.981
    - type: map_at_3
      value: 32.538
    - type: map_at_5
      value: 34.763
    - type: mrr_at_1
      value: 44.444
    - type: mrr_at_10
      value: 53.168000000000006
    - type: mrr_at_100
      value: 53.839000000000006
    - type: mrr_at_1000
      value: 53.869
    - type: mrr_at_3
      value: 50.54
    - type: mrr_at_5
      value: 52.068000000000005
    - type: ndcg_at_1
      value: 44.444
    - type: ndcg_at_10
      value: 44.994
    - type: ndcg_at_100
      value: 51.599
    - type: ndcg_at_1000
      value: 54.339999999999996
    - type: ndcg_at_3
      value: 41.372
    - type: ndcg_at_5
      value: 42.149
    - type: precision_at_1
      value: 44.444
    - type: precision_at_10
      value: 12.407
    - type: precision_at_100
      value: 1.9269999999999998
    - type: precision_at_1000
      value: 0.242
    - type: precision_at_3
      value: 27.726
    - type: precision_at_5
      value: 19.814999999999998
    - type: recall_at_1
      value: 22.651
    - type: recall_at_10
      value: 52.075
    - type: recall_at_100
      value: 76.51400000000001
    - type: recall_at_1000
      value: 92.852
    - type: recall_at_3
      value: 37.236000000000004
    - type: recall_at_5
      value: 43.175999999999995
  - task:
      type: Retrieval
    dataset:
      type: hotpotqa
      name: MTEB HotpotQA
      config: default
      split: test
      revision: None
    metrics:
    - type: map_at_1
      value: 40.777
    - type: map_at_10
      value: 66.79899999999999
    - type: map_at_100
      value: 67.65299999999999
    - type: map_at_1000
      value: 67.706
    - type: map_at_3
      value: 63.352
    - type: map_at_5
      value: 65.52900000000001
    - type: mrr_at_1
      value: 81.553
    - type: mrr_at_10
      value: 86.983
    - type: mrr_at_100
      value: 87.132
    - type: mrr_at_1000
      value: 87.136
    - type: mrr_at_3
      value: 86.156
    - type: mrr_at_5
      value: 86.726
    - type: ndcg_at_1
      value: 81.553
    - type: ndcg_at_10
      value: 74.64
    - type: ndcg_at_100
      value: 77.459
    - type: ndcg_at_1000
      value: 78.43
    - type: ndcg_at_3
      value: 69.878
    - type: ndcg_at_5
      value: 72.59400000000001
    - type: precision_at_1
      value: 81.553
    - type: precision_at_10
      value: 15.654000000000002
    - type: precision_at_100
      value: 1.783
    - type: precision_at_1000
      value: 0.191
    - type: precision_at_3
      value: 45.199
    - type: precision_at_5
      value: 29.267
    - type: recall_at_1
      value: 40.777
    - type: recall_at_10
      value: 78.271
    - type: recall_at_100
      value: 89.129
    - type: recall_at_1000
      value: 95.49
    - type: recall_at_3
      value: 67.79899999999999
    - type: recall_at_5
      value: 73.167
  - task:
      type: Classification
    dataset:
      type: mteb/imdb
      name: MTEB ImdbClassification
      config: default
      split: test
      revision: 3d86128a09e091d6018b6d26cad27f2739fc2db7
    metrics:
    - type: accuracy
      value: 93.5064
    - type: ap
      value: 90.25495114444111
    - type: f1
      value: 93.5012434973381
  - task:
      type: Retrieval
    dataset:
      type: msmarco
      name: MTEB MSMARCO
      config: default
      split: dev
      revision: None
    metrics:
    - type: map_at_1
      value: 23.301
    - type: map_at_10
      value: 35.657
    - type: map_at_100
      value: 36.797000000000004
    - type: map_at_1000
      value: 36.844
    - type: map_at_3
      value: 31.743
    - type: map_at_5
      value: 34.003
    - type: mrr_at_1
      value: 23.854
    - type: mrr_at_10
      value: 36.242999999999995
    - type: mrr_at_100
      value: 37.32
    - type: mrr_at_1000
      value: 37.361
    - type: mrr_at_3
      value: 32.4
    - type: mrr_at_5
      value: 34.634
    - type: ndcg_at_1
      value: 23.868000000000002
    - type: ndcg_at_10
      value: 42.589
    - type: ndcg_at_100
      value: 48.031
    - type: ndcg_at_1000
      value: 49.189
    - type: ndcg_at_3
      value: 34.649
    - type: ndcg_at_5
      value: 38.676
    - type: precision_at_1
      value: 23.868000000000002
    - type: precision_at_10
      value: 6.6850000000000005
    - type: precision_at_100
      value: 0.9400000000000001
    - type: precision_at_1000
      value: 0.104
    - type: precision_at_3
      value: 14.651
    - type: precision_at_5
      value: 10.834000000000001
    - type: recall_at_1
      value: 23.301
    - type: recall_at_10
      value: 63.88700000000001
    - type: recall_at_100
      value: 88.947
    - type: recall_at_1000
      value: 97.783
    - type: recall_at_3
      value: 42.393
    - type: recall_at_5
      value: 52.036
  - task:
      type: Classification
    dataset:
      type: mteb/mtop_domain
      name: MTEB MTOPDomainClassification (en)
      config: en
      split: test
      revision: d80d48c1eb48d3562165c59d59d0034df9fff0bf
    metrics:
    - type: accuracy
      value: 94.64888280893753
    - type: f1
      value: 94.41310774203512
  - task:
      type: Classification
    dataset:
      type: mteb/mtop_intent
      name: MTEB MTOPIntentClassification (en)
      config: en
      split: test
      revision: ae001d0e6b1228650b7bd1c2c65fb50ad11a8aba
    metrics:
    - type: accuracy
      value: 79.72184222526221
    - type: f1
      value: 61.522034067350106
  - task:
      type: Classification
    dataset:
      type: mteb/amazon_massive_intent
      name: MTEB MassiveIntentClassification (en)
      config: en
      split: test
      revision: 31efe3c427b0bae9c22cbb560b8f15491cc6bed7
    metrics:
    - type: accuracy
      value: 79.60659045057163
    - type: f1
      value: 77.268649687049
  - task:
      type: Classification
    dataset:
      type: mteb/amazon_massive_scenario
      name: MTEB MassiveScenarioClassification (en)
      config: en
      split: test
      revision: 7d571f92784cd94a019292a1f45445077d0ef634
    metrics:
    - type: accuracy
      value: 81.83254875588432
    - type: f1
      value: 81.61520635919082
  - task:
      type: Clustering
    dataset:
      type: mteb/medrxiv-clustering-p2p
      name: MTEB MedrxivClusteringP2P
      config: default
      split: test
      revision: e7a26af6f3ae46b30dde8737f02c07b1505bcc73
    metrics:
    - type: v_measure
      value: 36.31529875009507
  - task:
      type: Clustering
    dataset:
      type: mteb/medrxiv-clustering-s2s
      name: MTEB MedrxivClusteringS2S
      config: default
      split: test
      revision: 35191c8c0dca72d8ff3efcd72aa802307d469663
    metrics:
    - type: v_measure
      value: 31.734233714415073
  - task:
      type: Reranking
    dataset:
      type: mteb/mind_small
      name: MTEB MindSmallReranking
      config: default
      split: test
      revision: 3bdac13927fdc888b903db93b2ffdbd90b295a69
    metrics:
    - type: map
      value: 30.994501713009452
    - type: mrr
      value: 32.13512850703073
  - task:
      type: Retrieval
    dataset:
      type: nfcorpus
      name: MTEB NFCorpus
      config: default
      split: test
      revision: None
    metrics:
    - type: map_at_1
      value: 6.603000000000001
    - type: map_at_10
      value: 13.767999999999999
    - type: map_at_100
      value: 17.197000000000003
    - type: map_at_1000
      value: 18.615000000000002
    - type: map_at_3
      value: 10.567
    - type: map_at_5
      value: 12.078999999999999
    - type: mrr_at_1
      value: 44.891999999999996
    - type: mrr_at_10
      value: 53.75299999999999
    - type: mrr_at_100
      value: 54.35
    - type: mrr_at_1000
      value: 54.388000000000005
    - type: mrr_at_3
      value: 51.495999999999995
    - type: mrr_at_5
      value: 52.688
    - type: ndcg_at_1
      value: 43.189
    - type: ndcg_at_10
      value: 34.567
    - type: ndcg_at_100
      value: 32.273
    - type: ndcg_at_1000
      value: 41.321999999999996
    - type: ndcg_at_3
      value: 40.171
    - type: ndcg_at_5
      value: 37.502
    - type: precision_at_1
      value: 44.582
    - type: precision_at_10
      value: 25.139
    - type: precision_at_100
      value: 7.739999999999999
    - type: precision_at_1000
      value: 2.054
    - type: precision_at_3
      value: 37.152
    - type: precision_at_5
      value: 31.826999999999998
    - type: recall_at_1
      value: 6.603000000000001
    - type: recall_at_10
      value: 17.023
    - type: recall_at_100
      value: 32.914
    - type: recall_at_1000
      value: 64.44800000000001
    - type: recall_at_3
      value: 11.457
    - type: recall_at_5
      value: 13.816
  - task:
      type: Retrieval
    dataset:
      type: nq
      name: MTEB NQ
      config: default
      split: test
      revision: None
    metrics:
    - type: map_at_1
      value: 30.026000000000003
    - type: map_at_10
      value: 45.429
    - type: map_at_100
      value: 46.45
    - type: map_at_1000
      value: 46.478
    - type: map_at_3
      value: 41.147
    - type: map_at_5
      value: 43.627
    - type: mrr_at_1
      value: 33.951
    - type: mrr_at_10
      value: 47.953
    - type: mrr_at_100
      value: 48.731
    - type: mrr_at_1000
      value: 48.751
    - type: mrr_at_3
      value: 44.39
    - type: mrr_at_5
      value: 46.533
    - type: ndcg_at_1
      value: 33.951
    - type: ndcg_at_10
      value: 53.24100000000001
    - type: ndcg_at_100
      value: 57.599999999999994
    - type: ndcg_at_1000
      value: 58.270999999999994
    - type: ndcg_at_3
      value: 45.190999999999995
    - type: ndcg_at_5
      value: 49.339
    - type: precision_at_1
      value: 33.951
    - type: precision_at_10
      value: 8.856
    - type: precision_at_100
      value: 1.133
    - type: precision_at_1000
      value: 0.12
    - type: precision_at_3
      value: 20.713
    - type: precision_at_5
      value: 14.838000000000001
    - type: recall_at_1
      value: 30.026000000000003
    - type: recall_at_10
      value: 74.512
    - type: recall_at_100
      value: 93.395
    - type: recall_at_1000
      value: 98.402
    - type: recall_at_3
      value: 53.677
    - type: recall_at_5
      value: 63.198
  - task:
      type: Retrieval
    dataset:
      type: quora
      name: MTEB QuoraRetrieval
      config: default
      split: test
      revision: None
    metrics:
    - type: map_at_1
      value: 71.41300000000001
    - type: map_at_10
      value: 85.387
    - type: map_at_100
      value: 86.027
    - type: map_at_1000
      value: 86.041
    - type: map_at_3
      value: 82.543
    - type: map_at_5
      value: 84.304
    - type: mrr_at_1
      value: 82.35
    - type: mrr_at_10
      value: 88.248
    - type: mrr_at_100
      value: 88.348
    - type: mrr_at_1000
      value: 88.349
    - type: mrr_at_3
      value: 87.348
    - type: mrr_at_5
      value: 87.96300000000001
    - type: ndcg_at_1
      value: 82.37
    - type: ndcg_at_10
      value: 88.98
    - type: ndcg_at_100
      value: 90.16499999999999
    - type: ndcg_at_1000
      value: 90.239
    - type: ndcg_at_3
      value: 86.34100000000001
    - type: ndcg_at_5
      value: 87.761
    - type: precision_at_1
      value: 82.37
    - type: precision_at_10
      value: 13.471
    - type: precision_at_100
      value: 1.534
    - type: precision_at_1000
      value: 0.157
    - type: precision_at_3
      value: 37.827
    - type: precision_at_5
      value: 24.773999999999997
    - type: recall_at_1
      value: 71.41300000000001
    - type: recall_at_10
      value: 95.748
    - type: recall_at_100
      value: 99.69200000000001
    - type: recall_at_1000
      value: 99.98
    - type: recall_at_3
      value: 87.996
    - type: recall_at_5
      value: 92.142
  - task:
      type: Clustering
    dataset:
      type: mteb/reddit-clustering
      name: MTEB RedditClustering
      config: default
      split: test
      revision: 24640382cdbf8abc73003fb0fa6d111a705499eb
    metrics:
    - type: v_measure
      value: 56.96878497780007
  - task:
      type: Clustering
    dataset:
      type: mteb/reddit-clustering-p2p
      name: MTEB RedditClusteringP2P
      config: default
      split: test
      revision: 282350215ef01743dc01b456c7f5241fa8937f16
    metrics:
    - type: v_measure
      value: 65.31371347128074
  - task:
      type: Retrieval
    dataset:
      type: scidocs
      name: MTEB SCIDOCS
      config: default
      split: test
      revision: None
    metrics:
    - type: map_at_1
      value: 5.287
    - type: map_at_10
      value: 13.530000000000001
    - type: map_at_100
      value: 15.891
    - type: map_at_1000
      value: 16.245
    - type: map_at_3
      value: 9.612
    - type: map_at_5
      value: 11.672
    - type: mrr_at_1
      value: 26
    - type: mrr_at_10
      value: 37.335
    - type: mrr_at_100
      value: 38.443
    - type: mrr_at_1000
      value: 38.486
    - type: mrr_at_3
      value: 33.783
    - type: mrr_at_5
      value: 36.028
    - type: ndcg_at_1
      value: 26
    - type: ndcg_at_10
      value: 22.215
    - type: ndcg_at_100
      value: 31.101
    - type: ndcg_at_1000
      value: 36.809
    - type: ndcg_at_3
      value: 21.104
    - type: ndcg_at_5
      value: 18.759999999999998
    - type: precision_at_1
      value: 26
    - type: precision_at_10
      value: 11.43
    - type: precision_at_100
      value: 2.424
    - type: precision_at_1000
      value: 0.379
    - type: precision_at_3
      value: 19.7
    - type: precision_at_5
      value: 16.619999999999997
    - type: recall_at_1
      value: 5.287
    - type: recall_at_10
      value: 23.18
    - type: recall_at_100
      value: 49.208
    - type: recall_at_1000
      value: 76.85300000000001
    - type: recall_at_3
      value: 11.991999999999999
    - type: recall_at_5
      value: 16.85
  - task:
      type: STS
    dataset:
      type: mteb/sickr-sts
      name: MTEB SICK-R
      config: default
      split: test
      revision: a6ea5a8cab320b040a23452cc28066d9beae2cee
    metrics:
    - type: cos_sim_pearson
      value: 83.87834913790886
    - type: cos_sim_spearman
      value: 81.04583513112122
    - type: euclidean_pearson
      value: 81.20484174558065
    - type: euclidean_spearman
      value: 80.76430832561769
    - type: manhattan_pearson
      value: 81.21416730978615
    - type: manhattan_spearman
      value: 80.7797637394211
  - task:
      type: STS
    dataset:
      type: mteb/sts12-sts
      name: MTEB STS12
      config: default
      split: test
      revision: a0d554a64d88156834ff5ae9920b964011b16384
    metrics:
    - type: cos_sim_pearson
      value: 86.56143998865157
    - type: cos_sim_spearman
      value: 79.75387012744471
    - type: euclidean_pearson
      value: 83.7877519997019
    - type: euclidean_spearman
      value: 79.90489748003296
    - type: manhattan_pearson
      value: 83.7540590666095
    - type: manhattan_spearman
      value: 79.86434577931573
  - task:
      type: STS
    dataset:
      type: mteb/sts13-sts
      name: MTEB STS13
      config: default
      split: test
      revision: 7e90230a92c190f1bf69ae9002b8cea547a64cca
    metrics:
    - type: cos_sim_pearson
      value: 83.92102564177941
    - type: cos_sim_spearman
      value: 84.98234585939103
    - type: euclidean_pearson
      value: 84.47729567593696
    - type: euclidean_spearman
      value: 85.09490696194469
    - type: manhattan_pearson
      value: 84.38622951588229
    - type: manhattan_spearman
      value: 85.02507171545574
  - task:
      type: STS
    dataset:
      type: mteb/sts14-sts
      name: MTEB STS14
      config: default
      split: test
      revision: 6031580fec1f6af667f0bd2da0a551cf4f0b2375
    metrics:
    - type: cos_sim_pearson
      value: 80.1891164763377
    - type: cos_sim_spearman
      value: 80.7997969966883
    - type: euclidean_pearson
      value: 80.48572256162396
    - type: euclidean_spearman
      value: 80.57851903536378
    - type: manhattan_pearson
      value: 80.4324819433651
    - type: manhattan_spearman
      value: 80.5074526239062
  - task:
      type: STS
    dataset:
      type: mteb/sts15-sts
      name: MTEB STS15
      config: default
      split: test
      revision: ae752c7c21bf194d8b67fd573edf7ae58183cbe3
    metrics:
    - type: cos_sim_pearson
      value: 82.64319975116025
    - type: cos_sim_spearman
      value: 84.88671197763652
    - type: euclidean_pearson
      value: 84.74692193293231
    - type: euclidean_spearman
      value: 85.27151722073653
    - type: manhattan_pearson
      value: 84.72460516785438
    - type: manhattan_spearman
      value: 85.26518899786687
  - task:
      type: STS
    dataset:
      type: mteb/sts16-sts
      name: MTEB STS16
      config: default
      split: test
      revision: 4d8694f8f0e0100860b497b999b3dbed754a0513
    metrics:
    - type: cos_sim_pearson
      value: 83.24687565822381
    - type: cos_sim_spearman
      value: 85.60418454111263
    - type: euclidean_pearson
      value: 84.85829740169851
    - type: euclidean_spearman
      value: 85.66378014138306
    - type: manhattan_pearson
      value: 84.84672408808835
    - type: manhattan_spearman
      value: 85.63331924364891
  - task:
      type: STS
    dataset:
      type: mteb/sts17-crosslingual-sts
      name: MTEB STS17 (en-en)
      config: en-en
      split: test
      revision: af5e6fb845001ecf41f4c1e033ce921939a2a68d
    metrics:
    - type: cos_sim_pearson
      value: 84.87758895415485
    - type: cos_sim_spearman
      value: 85.8193745617297
    - type: euclidean_pearson
      value: 85.78719118848134
    - type: euclidean_spearman
      value: 84.35797575385688
    - type: manhattan_pearson
      value: 85.97919844815692
    - type: manhattan_spearman
      value: 84.58334745175151
  - task:
      type: STS
    dataset:
      type: mteb/sts22-crosslingual-sts
      name: MTEB STS22 (en)
      config: en
      split: test
      revision: 6d1ba47164174a496b7fa5d3569dae26a6813b80
    metrics:
    - type: cos_sim_pearson
      value: 67.27076035963599
    - type: cos_sim_spearman
      value: 67.21433656439973
    - type: euclidean_pearson
      value: 68.07434078679324
    - type: euclidean_spearman
      value: 66.0249731719049
    - type: manhattan_pearson
      value: 67.95495198947476
    - type: manhattan_spearman
      value: 65.99893908331886
  - task:
      type: STS
    dataset:
      type: mteb/stsbenchmark-sts
      name: MTEB STSBenchmark
      config: default
      split: test
      revision: b0fddb56ed78048fa8b90373c8a3cfc37b684831
    metrics:
    - type: cos_sim_pearson
      value: 82.22437747056817
    - type: cos_sim_spearman
      value: 85.0995685206174
    - type: euclidean_pearson
      value: 84.08616925603394
    - type: euclidean_spearman
      value: 84.89633925691658
    - type: manhattan_pearson
      value: 84.08332675923133
    - type: manhattan_spearman
      value: 84.8858228112915
  - task:
      type: Reranking
    dataset:
      type: mteb/scidocs-reranking
      name: MTEB SciDocsRR
      config: default
      split: test
      revision: d3c5e1fc0b855ab6097bf1cda04dd73947d7caab
    metrics:
    - type: map
      value: 87.6909022589666
    - type: mrr
      value: 96.43341952165481
  - task:
      type: Retrieval
    dataset:
      type: scifact
      name: MTEB SciFact
      config: default
      split: test
      revision: None
    metrics:
    - type: map_at_1
      value: 57.660999999999994
    - type: map_at_10
      value: 67.625
    - type: map_at_100
      value: 68.07600000000001
    - type: map_at_1000
      value: 68.10199999999999
    - type: map_at_3
      value: 64.50399999999999
    - type: map_at_5
      value: 66.281
    - type: mrr_at_1
      value: 61
    - type: mrr_at_10
      value: 68.953
    - type: mrr_at_100
      value: 69.327
    - type: mrr_at_1000
      value: 69.352
    - type: mrr_at_3
      value: 66.833
    - type: mrr_at_5
      value: 68.05
    - type: ndcg_at_1
      value: 61
    - type: ndcg_at_10
      value: 72.369
    - type: ndcg_at_100
      value: 74.237
    - type: ndcg_at_1000
      value: 74.939
    - type: ndcg_at_3
      value: 67.284
    - type: ndcg_at_5
      value: 69.72500000000001
    - type: precision_at_1
      value: 61
    - type: precision_at_10
      value: 9.733
    - type: precision_at_100
      value: 1.0670000000000002
    - type: precision_at_1000
      value: 0.11199999999999999
    - type: precision_at_3
      value: 26.222
    - type: precision_at_5
      value: 17.4
    - type: recall_at_1
      value: 57.660999999999994
    - type: recall_at_10
      value: 85.656
    - type: recall_at_100
      value: 93.833
    - type: recall_at_1000
      value: 99.333
    - type: recall_at_3
      value: 71.961
    - type: recall_at_5
      value: 78.094
  - task:
      type: PairClassification
    dataset:
      type: mteb/sprintduplicatequestions-pairclassification
      name: MTEB SprintDuplicateQuestions
      config: default
      split: test
      revision: d66bd1f72af766a5cc4b0ca5e00c162f89e8cc46
    metrics:
    - type: cos_sim_accuracy
      value: 99.86930693069307
    - type: cos_sim_ap
      value: 96.76685487950894
    - type: cos_sim_f1
      value: 93.44587884806354
    - type: cos_sim_precision
      value: 92.80078895463511
    - type: cos_sim_recall
      value: 94.1
    - type: dot_accuracy
      value: 99.54356435643564
    - type: dot_ap
      value: 81.18659960405607
    - type: dot_f1
      value: 75.78008915304605
    - type: dot_precision
      value: 75.07360157016683
    - type: dot_recall
      value: 76.5
    - type: euclidean_accuracy
      value: 99.87326732673267
    - type: euclidean_ap
      value: 96.8102411908941
    - type: euclidean_f1
      value: 93.6127744510978
    - type: euclidean_precision
      value: 93.42629482071713
    - type: euclidean_recall
      value: 93.8
    - type: manhattan_accuracy
      value: 99.87425742574257
    - type: manhattan_ap
      value: 96.82857341435529
    - type: manhattan_f1
      value: 93.62129583124059
    - type: manhattan_precision
      value: 94.04641775983855
    - type: manhattan_recall
      value: 93.2
    - type: max_accuracy
      value: 99.87425742574257
    - type: max_ap
      value: 96.82857341435529
    - type: max_f1
      value: 93.62129583124059
  - task:
      type: Clustering
    dataset:
      type: mteb/stackexchange-clustering
      name: MTEB StackExchangeClustering
      config: default
      split: test
      revision: 6cbc1f7b2bc0622f2e39d2c77fa502909748c259
    metrics:
    - type: v_measure
      value: 65.92560972698926
  - task:
      type: Clustering
    dataset:
      type: mteb/stackexchange-clustering-p2p
      name: MTEB StackExchangeClusteringP2P
      config: default
      split: test
      revision: 815ca46b2622cec33ccafc3735d572c266efdb44
    metrics:
    - type: v_measure
      value: 34.92797240259008
  - task:
      type: Reranking
    dataset:
      type: mteb/stackoverflowdupquestions-reranking
      name: MTEB StackOverflowDupQuestions
      config: default
      split: test
      revision: e185fbe320c72810689fc5848eb6114e1ef5ec69
    metrics:
    - type: map
      value: 55.244624045597654
    - type: mrr
      value: 56.185303666921314
  - task:
      type: Summarization
    dataset:
      type: mteb/summeval
      name: MTEB SummEval
      config: default
      split: test
      revision: cda12ad7615edc362dbf25a00fdd61d3b1eaf93c
    metrics:
    - type: cos_sim_pearson
      value: 31.02491987312937
    - type: cos_sim_spearman
      value: 32.055592206679734
    - type: dot_pearson
      value: 24.731627575422557
    - type: dot_spearman
      value: 24.308029077069733
  - task:
      type: Retrieval
    dataset:
      type: trec-covid
      name: MTEB TRECCOVID
      config: default
      split: test
      revision: None
    metrics:
    - type: map_at_1
      value: 0.231
    - type: map_at_10
      value: 1.899
    - type: map_at_100
      value: 9.498
    - type: map_at_1000
      value: 20.979999999999997
    - type: map_at_3
      value: 0.652
    - type: map_at_5
      value: 1.069
    - type: mrr_at_1
      value: 88
    - type: mrr_at_10
      value: 93.4
    - type: mrr_at_100
      value: 93.4
    - type: mrr_at_1000
      value: 93.4
    - type: mrr_at_3
      value: 93
    - type: mrr_at_5
      value: 93.4
    - type: ndcg_at_1
      value: 86
    - type: ndcg_at_10
      value: 75.375
    - type: ndcg_at_100
      value: 52.891999999999996
    - type: ndcg_at_1000
      value: 44.952999999999996
    - type: ndcg_at_3
      value: 81.05
    - type: ndcg_at_5
      value: 80.175
    - type: precision_at_1
      value: 88
    - type: precision_at_10
      value: 79
    - type: precision_at_100
      value: 53.16
    - type: precision_at_1000
      value: 19.408
    - type: precision_at_3
      value: 85.333
    - type: precision_at_5
      value: 84
    - type: recall_at_1
      value: 0.231
    - type: recall_at_10
      value: 2.078
    - type: recall_at_100
      value: 12.601
    - type: recall_at_1000
      value: 41.296
    - type: recall_at_3
      value: 0.6779999999999999
    - type: recall_at_5
      value: 1.1360000000000001
  - task:
      type: Retrieval
    dataset:
      type: webis-touche2020
      name: MTEB Touche2020
      config: default
      split: test
      revision: None
    metrics:
    - type: map_at_1
      value: 2.782
    - type: map_at_10
      value: 10.204
    - type: map_at_100
      value: 16.176
    - type: map_at_1000
      value: 17.456
    - type: map_at_3
      value: 5.354
    - type: map_at_5
      value: 7.503
    - type: mrr_at_1
      value: 40.816
    - type: mrr_at_10
      value: 54.010000000000005
    - type: mrr_at_100
      value: 54.49
    - type: mrr_at_1000
      value: 54.49
    - type: mrr_at_3
      value: 48.980000000000004
    - type: mrr_at_5
      value: 51.735
    - type: ndcg_at_1
      value: 36.735
    - type: ndcg_at_10
      value: 26.61
    - type: ndcg_at_100
      value: 36.967
    - type: ndcg_at_1000
      value: 47.274
    - type: ndcg_at_3
      value: 30.363
    - type: ndcg_at_5
      value: 29.448999999999998
    - type: precision_at_1
      value: 40.816
    - type: precision_at_10
      value: 23.878
    - type: precision_at_100
      value: 7.693999999999999
    - type: precision_at_1000
      value: 1.4489999999999998
    - type: precision_at_3
      value: 31.293
    - type: precision_at_5
      value: 29.796
    - type: recall_at_1
      value: 2.782
    - type: recall_at_10
      value: 16.485
    - type: recall_at_100
      value: 46.924
    - type: recall_at_1000
      value: 79.365
    - type: recall_at_3
      value: 6.52
    - type: recall_at_5
      value: 10.48
  - task:
      type: Classification
    dataset:
      type: mteb/toxic_conversations_50k
      name: MTEB ToxicConversationsClassification
      config: default
      split: test
      revision: d7c0de2777da35d6aae2200a62c6e0e5af397c4c
    metrics:
    - type: accuracy
      value: 70.08300000000001
    - type: ap
      value: 13.91559884590195
    - type: f1
      value: 53.956838444291364
  - task:
      type: Classification
    dataset:
      type: mteb/tweet_sentiment_extraction
      name: MTEB TweetSentimentExtractionClassification
      config: default
      split: test
      revision: d604517c81ca91fe16a244d1248fc021f9ecee7a
    metrics:
    - type: accuracy
      value: 59.34069043576683
    - type: f1
      value: 59.662041994618406
  - task:
      type: Clustering
    dataset:
      type: mteb/twentynewsgroups-clustering
      name: MTEB TwentyNewsgroupsClustering
      config: default
      split: test
      revision: 6125ec4e24fa026cec8a478383ee943acfbd5449
    metrics:
    - type: v_measure
      value: 53.70780611078653
  - task:
      type: PairClassification
    dataset:
      type: mteb/twittersemeval2015-pairclassification
      name: MTEB TwitterSemEval2015
      config: default
      split: test
      revision: 70970daeab8776df92f5ea462b6173c0b46fd2d1
    metrics:
    - type: cos_sim_accuracy
      value: 87.10734934732073
    - type: cos_sim_ap
      value: 77.58349999516054
    - type: cos_sim_f1
      value: 70.25391395868965
    - type: cos_sim_precision
      value: 70.06035161374967
    - type: cos_sim_recall
      value: 70.44854881266491
    - type: dot_accuracy
      value: 80.60439887941826
    - type: dot_ap
      value: 54.52935200483575
    - type: dot_f1
      value: 54.170444242973716
    - type: dot_precision
      value: 47.47715534366309
    - type: dot_recall
      value: 63.06068601583114
    - type: euclidean_accuracy
      value: 87.26828396018358
    - type: euclidean_ap
      value: 78.00158454104036
    - type: euclidean_f1
      value: 70.70292457670601
    - type: euclidean_precision
      value: 68.79680479281079
    - type: euclidean_recall
      value: 72.71767810026385
    - type: manhattan_accuracy
      value: 87.11330988853788
    - type: manhattan_ap
      value: 77.92527099601855
    - type: manhattan_f1
      value: 70.76488706365502
    - type: manhattan_precision
      value: 68.89055472263868
    - type: manhattan_recall
      value: 72.74406332453826
    - type: max_accuracy
      value: 87.26828396018358
    - type: max_ap
      value: 78.00158454104036
    - type: max_f1
      value: 70.76488706365502
  - task:
      type: PairClassification
    dataset:
      type: mteb/twitterurlcorpus-pairclassification
      name: MTEB TwitterURLCorpus
      config: default
      split: test
      revision: 8b6510b0b1fa4e4c4f879467980e9be563ec1cdf
    metrics:
    - type: cos_sim_accuracy
      value: 87.80804905499282
    - type: cos_sim_ap
      value: 83.06187782630936
    - type: cos_sim_f1
      value: 74.99716435403985
    - type: cos_sim_precision
      value: 73.67951860931579
    - type: cos_sim_recall
      value: 76.36279642747151
    - type: dot_accuracy
      value: 81.83141227151008
    - type: dot_ap
      value: 67.18241090841795
    - type: dot_f1
      value: 62.216037571751606
    - type: dot_precision
      value: 56.749381227391005
    - type: dot_recall
      value: 68.84816753926701
    - type: euclidean_accuracy
      value: 87.91671517832887
    - type: euclidean_ap
      value: 83.56538942001427
    - type: euclidean_f1
      value: 75.7327253337256
    - type: euclidean_precision
      value: 72.48856036606828
    - type: euclidean_recall
      value: 79.28087465352634
    - type: manhattan_accuracy
      value: 87.86626304963713
    - type: manhattan_ap
      value: 83.52939841172832
    - type: manhattan_f1
      value: 75.73635656329888
    - type: manhattan_precision
      value: 72.99150182103836
    - type: manhattan_recall
      value: 78.69571912534647
    - type: max_accuracy
      value: 87.91671517832887
    - type: max_ap
      value: 83.56538942001427
    - type: max_f1
      value: 75.73635656329888
license: mit
language:
- en
pipeline_tag: sentence-similarity
---


<h1 align="center">FlagEmbedding</h1>


<h4 align="center">
    <p>
        <a href=#model-list>Model List</a> | 
        <a href=#usage>Usage</a>  |
        <a href="#evaluation">Evaluation</a> |
        <a href="#train">Train</a> |
        <a href="#contact">Contact</a> |
        <a href="#license">License</a> 
    <p>
</h4>

More details please refer to our Github: [FlagEmbedding](https://github.com/FlagOpen/FlagEmbedding).

[English](README.md) | [中文](https://github.com/FlagOpen/FlagEmbedding/blob/master/README_zh.md)

FlagEmbedding can map any text to a low-dimensional dense vector which can be used for tasks like retrieval, classification,  clustering, or semantic search.
And it also can be used in vector database for LLMs.

************* 🌟**Updates**🌟 *************
- 08/09/2023: BGE Models are integrated into **Langchain**, you can use it like [**this**](#using-langchain); C-MTEB **leaderboard** is [avaliable](https://huggingface.co/spaces/mteb/leaderboard).  
- 08/05/2023: Release base-scale and small-scale models, **best performance among the models of the same size 🤗**
- 08/02/2023: Release `bge-large-*`(short for BAAI General Embedding) Models, **rank 1st on MTEB and C-MTEB benchmark!**  
- 08/01/2023: We release the [Chinese Massive Text Embedding Benchmark](https://github.com/FlagOpen/FlagEmbedding/blob/master/C_MTEB) (**C-MTEB**), consisting of 31 test dataset.   


## Model List

`bge` is short for `BAAI general embedding`.

|              Model              | Language | Description | query instruction for retrieval\* |
|:-------------------------------|:--------:| :--------:| :--------:|
|  [BAAI/bge-large-en](https://huggingface.co/BAAI/bge-large-en) |   English |  rank **1st** in [MTEB](https://huggingface.co/spaces/mteb/leaderboard) leaderboard | `Represent this sentence for searching relevant passages: `  |
|  [BAAI/bge-base-en](https://huggingface.co/BAAI/bge-base-en) |   English |  rank **2nd** in [MTEB](https://huggingface.co/spaces/mteb/leaderboard) leaderboard | `Represent this sentence for searching relevant passages: `  |
|  [BAAI/bge-small-en](https://huggingface.co/BAAI/bge-small-en) |   English | a small-scale model but with competitive performance  | `Represent this sentence for searching relevant passages: `  |
|  [BAAI/bge-large-zh](https://huggingface.co/BAAI/bge-large-zh) |   Chinese | rank **1st** in [C-MTEB](https://github.com/FlagOpen/FlagEmbedding/tree/master/C_MTEB) benchmark | `为这个句子生成表示以用于检索相关文章：`  |
|  [BAAI/bge-large-zh-noinstruct](https://huggingface.co/BAAI/bge-large-zh-noinstruct) |   Chinese | This model is trained without instruction, and rank **2nd** in [C-MTEB](https://github.com/FlagOpen/FlagEmbedding/tree/master/C_MTEB) benchmark |   |
|  [BAAI/bge-base-zh](https://huggingface.co/BAAI/bge-base-zh) |   Chinese |  a base-scale model but has similar ability with `bge-large-zh` | `为这个句子生成表示以用于检索相关文章：`  |
|  [BAAI/bge-small-zh](https://huggingface.co/BAAI/bge-small-zh) |   Chinese | a small-scale model but with competitive performance | `为这个句子生成表示以用于检索相关文章：`  |

\*: If you need to search the **long** relevant passages to a **short** query (s2p retrieval task), you need to add the instruction to the query; in other cases, no instruction is needed, just use the original query directly. In all cases, **no instruction** need to be added to passages.

## Usage 

Here are some examples to use `bge` models with 
[FlagEmbedding](#using-flagembedding), [Sentence-Transformers](#using-sentence-transformers), [Langchain](#using-langchain), or [Huggingface Transformers](#using-huggingface-transformers).

#### Using FlagEmbedding
```
pip install -U FlagEmbedding
```
If it doesn't work for you, you can see [FlagEmbedding](https://github.com/FlagOpen/FlagEmbedding/blob/master/FlagEmbedding/baai_general_embedding/README.md) for more methods to install FlagEmbedding.

```python
from FlagEmbedding import FlagModel
sentences = ["样例数据-1", "样例数据-2"]
model = FlagModel('BAAI/bge-large-zh', query_instruction_for_retrieval="为这个句子生成表示以用于检索相关文章：")
embeddings_1 = model.encode(sentences)
embeddings_2 = model.encode(sentences)
similarity = embeddings_1 @ embeddings_2.T
print(similarity)

# for s2p(short query to long passage) retrieval task, please use encode_queries() which will automatically add the instruction to each query
# corpus in retrieval task can still use encode() or encode_corpus(), since they don't need instruction
queries = ['query_1', 'query_2']
passages = ["样例文档-1", "样例文档-2"]
q_embeddings = model.encode_queries(queries)
p_embeddings = model.encode(passages)
scores = q_embeddings @ p_embeddings.T
```
The value of argument `query_instruction_for_retrieval` see [Model List](https://github.com/FlagOpen/FlagEmbedding/tree/master#model-list). 

FlagModel will use all available GPUs when encoding, please set `os.environ["CUDA_VISIBLE_DEVICES"]` to choose GPU.


#### Using Sentence-Transformers

Using this model also is easy when you have [sentence-transformers](https://www.SBERT.net) installed:

```
pip install -U sentence-transformers
```
```python
from sentence_transformers import SentenceTransformer
sentences = ["样例数据-1", "样例数据-2"]
model = SentenceTransformer('BAAI/bge-large-zh')
embeddings_1 = model.encode(sentences, normalize_embeddings=True)
embeddings_2 = model.encode(sentences, normalize_embeddings=True)
similarity = embeddings_1 @ embeddings_2.T
print(similarity)
```
For s2p(short query to long passage) retrieval task, 
each short query should start with an instruction (instructions see [Model List](https://github.com/FlagOpen/FlagEmbedding/tree/master#model-list)). 
But the instruction is not needed for passages.
```python
from sentence_transformers import SentenceTransformer
queries = ['query_1', 'query_2']
passages = ["样例文档-1", "样例文档-2"]
instruction = "为这个句子生成表示以用于检索相关文章："

model = SentenceTransformer('BAAI/bge-large-zh')
q_embeddings = model.encode([instruction+q for q in queries], normalize_embeddings=True)
p_embeddings = model.encode(passages, normalize_embeddings=True)
scores = q_embeddings @ p_embeddings.T
```

#### Using Langchain 

You can use `bge` in langchain like this:
```python
from langchain.embeddings import HuggingFaceBgeEmbeddings
model_name = "BAAI/bge-small-en"
model_kwargs = {'device': 'cuda'}
encode_kwargs = {'normalize_embeddings': True} # set True to compute cosine similarity
model_norm = HuggingFaceBgeEmbeddings(
    model_name=model_name,
    model_kwargs=model_kwargs,
    encode_kwargs=encode_kwargs
)
```


#### Using HuggingFace Transformers

With transformers package, you can use the model like this: First, you pass your input through the transformer model, then you select the last hidden state of first token (i.e., [CLS]) as the sentence embedding.

```python
from transformers import AutoTokenizer, AutoModel
import torch
# Sentences we want sentence embeddings for
sentences = ["样例数据-1", "样例数据-2"]

# Load model from HuggingFace Hub
tokenizer = AutoTokenizer.from_pretrained('BAAI/bge-large-zh')
model = AutoModel.from_pretrained('BAAI/bge-large-zh')

# Tokenize sentences
encoded_input = tokenizer(sentences, padding=True, truncation=True, return_tensors='pt')
# for s2p(short query to long passage) retrieval task, add an instruction to query (not add instruction for passages)
# encoded_input = tokenizer([instruction + q for q in queries], padding=True, truncation=True, return_tensors='pt')

# Compute token embeddings
with torch.no_grad():
    model_output = model(**encoded_input)
    # Perform pooling. In this case, cls pooling.
    sentence_embeddings = model_output[0][:, 0]
# normalize embeddings
sentence_embeddings = torch.nn.functional.normalize(sentence_embeddings, p=2, dim=1)
print("Sentence embeddings:", sentence_embeddings)
```


## Evaluation  
`baai-general-embedding` models achieve **state-of-the-art performance on both MTEB and C-MTEB leaderboard!**
More details and evaluation tools see our [scripts](https://github.com/FlagOpen/FlagEmbedding/blob/master/C_MTEB/README.md). 

- **MTEB**:   

| Model Name |  Dimension | Sequence Length | Average (56) | Retrieval (15) |Clustering (11) | Pair Classification (3) | Reranking (4) |  STS (10) | Summarization (1) | Classification (12) |
|:----:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| [**bge-large-en**](https://huggingface.co/BAAI/bge-large-en) |  1024 | 512 | **63.98** |  **53.9** | **46.98** | 85.8 | **59.48** | 81.56 | 32.06 | **76.21** | 
| [**bge-base-en**](https://huggingface.co/BAAI/bge-base-en) |  768 | 512 |  63.36 | 53.0 | 46.32 | 85.86 | 58.7 | 81.84 | 29.27 | 75.27 | 
| [gte-large](https://huggingface.co/thenlper/gte-large) |  1024 | 512 | 63.13 | 52.22 | 46.84 | 85.00 | 59.13 | 83.35 | 31.66 | 73.33 |
| [gte-base](https://huggingface.co/thenlper/gte-base) 	|  768 | 512 | 62.39 | 51.14 | 46.2 | 84.57 | 58.61 | 82.3 | 31.17 | 73.01 |
| [e5-large-v2](https://huggingface.co/intfloat/e5-large-v2) |  1024| 512 | 62.25 | 50.56 | 44.49 | 86.03 | 56.61 | 82.05 | 30.19 | 75.24 |
| [**bge-small-en**](https://huggingface.co/BAAI/bge-small-en) |  384 | 512 | 62.11 |  51.82 | 44.31 | 83.78 | 57.97 | 80.72 | 30.53 | 74.37 |  
| [instructor-xl](https://huggingface.co/hkunlp/instructor-xl) |  768 | 512 | 61.79 | 49.26 | 44.74 | 86.62 | 57.29 | 83.06 | 32.32 | 61.79 |
| [e5-base-v2](https://huggingface.co/intfloat/e5-base-v2) |  768 | 512 | 61.5 | 50.29 | 43.80 | 85.73 | 55.91 | 81.05 | 30.28 | 73.84 |
| [gte-small](https://huggingface.co/thenlper/gte-small) |  384 | 512 | 61.36 | 49.46 | 44.89 | 83.54 | 57.7 | 82.07 | 30.42 | 72.31 |
| [text-embedding-ada-002](https://platform.openai.com/docs/guides/embeddings) | 1536 | 8192 | 60.99 | 49.25 | 45.9 | 84.89 | 56.32 | 80.97 | 30.8 | 70.93 |
| [e5-small-v2](https://huggingface.co/intfloat/e5-base-v2) | 384 | 512 | 59.93 | 49.04 | 39.92 | 84.67 | 54.32 | 80.39 | 31.16 | 72.94 |
| [sentence-t5-xxl](https://huggingface.co/sentence-transformers/sentence-t5-xxl) |  768 | 512 | 59.51 | 42.24 | 43.72 | 85.06 | 56.42 | 82.63 | 30.08 | 73.42 |
| [all-mpnet-base-v2](https://huggingface.co/sentence-transformers/all-mpnet-base-v2) 	|  768 | 514 	| 57.78 | 43.81 | 43.69 | 83.04 | 59.36 | 80.28 | 27.49 | 65.07 |
| [sgpt-bloom-7b1-msmarco](https://huggingface.co/bigscience/sgpt-bloom-7b1-msmarco) 	|  4096 | 2048 | 57.59 | 48.22 | 38.93 | 81.9 | 55.65 | 77.74 | 33.6 | 66.19 |
| [all-MiniLM-L12-v2](https://huggingface.co/sentence-transformers/all-MiniLM-L12-v2) 	|  384 | 512 	| 56.53 | 42.69 | 41.81 | 82.41 | 58.44 | 79.8 | 27.9 | 63.21 |
| [all-MiniLM-L6-v2](https://huggingface.co/sentence-transformers/all-MiniLM-L6-v2) 	|  384 | 512 	| 56.26 | 41.95 | 42.35 | 82.37 | 58.04 | 78.9 | 30.81 | 63.05 |
| [contriever-base-msmarco](https://huggingface.co/nthakur/contriever-base-msmarco) 	|  768 | 512 	| 56.00 | 41.88 | 41.1 	| 82.54 | 53.14 | 76.51 | 30.36 | 66.68 |
| [sentence-t5-base](https://huggingface.co/sentence-transformers/sentence-t5-base) 	|  768 | 512 	| 55.27 | 33.63 | 40.21 | 85.18 | 53.09 | 81.14 | 31.39 | 69.81 |



- **C-MTEB**:  
We create a benchmark C-MTEB for chinese text embedding which consists of  31 datasets from 6 tasks. 
Please refer to [C_MTEB](https://github.com/FlagOpen/FlagEmbedding/blob/master/C_MTEB/README.md) for a detailed introduction.
 
| Model | Embedding dimension | Avg | Retrieval | STS | PairClassification | Classification | Reranking | Clustering |
|:-------------------------------|:--------:|:--------:|:--------:|:--------:|:--------:|:--------:|:--------:|:--------:|
| [**bge-large-zh**](https://huggingface.co/BAAI/bge-large-zh) | 1024 | **64.20** | **71.53** | **53.23** | **78.94** | 72.26 | **65.11** | 48.39 |  
| [**bge-large-zh-noinstruct**](https://huggingface.co/BAAI/bge-large-zh-noinstruct) | 1024 | 63.53 | 70.55 | 50.98 | 76.77 | **72.49** | 64.91 | **50.01** |   
| [**BAAI/bge-base-zh**](https://huggingface.co/BAAI/bge-base-zh) |  768 | 62.96 | 69.53 | 52.05 | 77.5 | 70.98 | 64.91 | 47.63 |  
| [**BAAI/bge-small-zh**](https://huggingface.co/BAAI/bge-small-zh) | 512 | 58.27 |  63.07 | 46.87 | 70.35 | 67.78 | 61.48 | 45.09 |  
| [m3e-base](https://huggingface.co/moka-ai/m3e-base) | 768 | 57.10 |56.91 | 48.15 | 63.99 | 70.28 | 59.34 | 47.68 |  
| [m3e-large](https://huggingface.co/moka-ai/m3e-large) | 1024 |  57.05 |54.75 | 48.64 | 64.3 | 71.22 | 59.66 | 48.88 |  
| [text-embedding-ada-002(OpenAI)](https://platform.openai.com/docs/guides/embeddings/what-are-embeddings) | 1536 |  53.02 | 52.0 | 40.61 | 69.56 | 67.38 | 54.28 | 45.68 |  
| [luotuo](https://huggingface.co/silk-road/luotuo-bert-medium) | 1024 | 49.37 |  44.4 | 39.41 | 66.62 | 65.29 | 49.25 | 44.39 | 
| [text2vec](https://huggingface.co/shibing624/text2vec-base-chinese) | 768 |  47.63 | 38.79 | 41.71 | 67.41 | 65.18 | 49.45 | 37.66 |  
| [text2vec-large](https://huggingface.co/GanymedeNil/text2vec-large-chinese) | 1024 | 47.36 | 41.94 | 41.98 | 70.86 | 63.42 | 49.16 | 30.02 |  



## Train
This section will introduce the way we used to train the general embedding. 
The training scripts are in [FlagEmbedding](https://github.com/FlagOpen/FlagEmbedding/blob/master/FlagEmbedding/baai_general_embedding/README.md), 
and we provide some examples to do [pre-train](https://github.com/FlagOpen/FlagEmbedding/blob/master/examples/pretrain/README.md) and [fine-tune](https://github.com/FlagOpen/FlagEmbedding/blob/master/examples/finetune/README.md).


**1. RetroMAE Pre-train**  
We pre-train the model following the method [retromae](https://github.com/staoxiao/RetroMAE), 
which shows promising improvement in retrieval task ([paper](https://aclanthology.org/2022.emnlp-main.35.pdf)). 
The pre-training was conducted on 24 A100(40G) GPUs with a batch size of 720. 
In retromae, the mask ratio of encoder and decoder are 0.3, 0.5 respectively.
We used the AdamW optimizer and the learning rate is 2e-5.

**Pre-training data**:
- English: 
    - [Pile](https://pile.eleuther.ai/)
    - [wikipedia](https://huggingface.co/datasets/wikipedia)
    - [msmarco](https://huggingface.co/datasets/Tevatron/msmarco-passage-corpus)
- Chinese: 
    - [wudao](https://github.com/BAAI-WuDao/Data)


**2. Finetune**  
We fine-tune the model using a contrastive objective. 
The format of input data is a triple`(query, positive, negative)`. 
Besides the negative in the triple, we also adopt in-batch negatives strategy. 
We employ the cross-device negatives sharing method to share negatives among different GPUs, 
which can dramatically **increase the number of negatives**.

We trained our model on 48 A100(40G) GPUs with a large batch size of 32,768 (so there are **65,535** negatives for each query in a batch). 
We used the AdamW optimizer and the learning rate is 1e-5.
The temperature for contrastive loss is 0.01.

Besides, we add instruction to the query for s2p(short query to long passage) retrieval task in the training (add nothing to passages). 
For English, the instruction is `Represent this sentence for searching relevant passages: `;
For Chinese, the instruction is `为这个句子生成表示以用于检索相关文章：`.
In the evaluation, the instruction should be added for queries in retrieval task, not be added for other tasks.
Noted that the instruction is not needed for passages.

The finetune script is accessible in this repository: [FlagEmbedding](https://github.com/FlagOpen/FlagEmbedding/blob/master/FlagEmbedding/baai_general_embedding/README.md). 
You can easily finetune your model with it.

**Training data**:

- For English, we collect 230M text pairs from [wikipedia](https://huggingface.co/datasets/wikipedia), [cc-net](https://github.com/facebookresearch/cc_net), and so on.

- For chinese, we collect 120M text pairs from [wudao](https://github.com/BAAI-WuDao/Data), [simclue](https://github.com/CLUEbenchmark/SimCLUE) and so on.

**The data collection is to be released in the future.**

We will continually update the embedding models and training codes, 
hoping to promote the development of the embedding model community.



## License
FlagEmbedding is licensed under [MIT License](https://github.com/FlagOpen/FlagEmbedding/blob/master/LICENSE). The released models can be used for commercial purposes free of charge.



