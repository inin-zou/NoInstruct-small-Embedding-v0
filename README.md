---
language:
- en
library_name: sentence-transformers
license: mit
pipeline_tag: sentence-similarity
tags:
  - feature-extraction
  - mteb
  - sentence-similarity
  - sentence-transformers
  - transformers
model-index:
- name: NoInstruct-small-Embedding-v0
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
      value: 75.76119402985074
    - type: ap
      value: 39.03628777559392
    - type: f1
      value: 69.85860402259618
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
      value: 93.29920000000001
    - type: ap
      value: 90.03479490717608
    - type: f1
      value: 93.28554395248467
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
      value: 49.98799999999999
    - type: f1
      value: 49.46151232451642
  - task:
      type: Retrieval
    dataset:
      type: mteb/arguana
      name: MTEB ArguAna
      config: default
      split: test
      revision: c22ab2a51041ffd869aaddef7af8d8215647e41a
    metrics:
    - type: map_at_1
      value: 31.935000000000002
    - type: map_at_10
      value: 48.791000000000004
    - type: map_at_100
      value: 49.619
    - type: map_at_1000
      value: 49.623
    - type: map_at_3
      value: 44.334
    - type: map_at_5
      value: 46.908
    - type: mrr_at_1
      value: 32.93
    - type: mrr_at_10
      value: 49.158
    - type: mrr_at_100
      value: 50.00599999999999
    - type: mrr_at_1000
      value: 50.01
    - type: mrr_at_3
      value: 44.618
    - type: mrr_at_5
      value: 47.325
    - type: ndcg_at_1
      value: 31.935000000000002
    - type: ndcg_at_10
      value: 57.593
    - type: ndcg_at_100
      value: 60.841
    - type: ndcg_at_1000
      value: 60.924
    - type: ndcg_at_3
      value: 48.416
    - type: ndcg_at_5
      value: 53.05
    - type: precision_at_1
      value: 31.935000000000002
    - type: precision_at_10
      value: 8.549
    - type: precision_at_100
      value: 0.9900000000000001
    - type: precision_at_1000
      value: 0.1
    - type: precision_at_3
      value: 20.081
    - type: precision_at_5
      value: 14.296000000000001
    - type: recall_at_1
      value: 31.935000000000002
    - type: recall_at_10
      value: 85.491
    - type: recall_at_100
      value: 99.004
    - type: recall_at_1000
      value: 99.644
    - type: recall_at_3
      value: 60.242
    - type: recall_at_5
      value: 71.479
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
      value: 47.78438534940855
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
      value: 40.12916178519471
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
      value: 62.125361608299855
    - type: mrr
      value: 74.92525172580574
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
      value: 88.64322910336641
    - type: cos_sim_spearman
      value: 87.20138453306345
    - type: euclidean_pearson
      value: 87.08547818178234
    - type: euclidean_spearman
      value: 87.17066094143931
    - type: manhattan_pearson
      value: 87.30053110771618
    - type: manhattan_spearman
      value: 86.86824441211934
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
      value: 86.3961038961039
    - type: f1
      value: 86.3669961645295
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
      value: 39.40291404289857
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
      value: 35.102356817746816
  - task:
      type: Retrieval
    dataset:
      type: mteb/cqadupstack-android
      name: MTEB CQADupstackAndroidRetrieval
      config: default
      split: test
      revision: f46a197baaae43b4f621051089b82a364682dfeb
    metrics:
    - type: map_at_1
      value: 31.013
    - type: map_at_10
      value: 42.681999999999995
    - type: map_at_100
      value: 44.24
    - type: map_at_1000
      value: 44.372
    - type: map_at_3
      value: 39.181
    - type: map_at_5
      value: 41.071999999999996
    - type: mrr_at_1
      value: 38.196999999999996
    - type: mrr_at_10
      value: 48.604
    - type: mrr_at_100
      value: 49.315
    - type: mrr_at_1000
      value: 49.363
    - type: mrr_at_3
      value: 45.756
    - type: mrr_at_5
      value: 47.43
    - type: ndcg_at_1
      value: 38.196999999999996
    - type: ndcg_at_10
      value: 49.344
    - type: ndcg_at_100
      value: 54.662
    - type: ndcg_at_1000
      value: 56.665
    - type: ndcg_at_3
      value: 44.146
    - type: ndcg_at_5
      value: 46.514
    - type: precision_at_1
      value: 38.196999999999996
    - type: precision_at_10
      value: 9.571
    - type: precision_at_100
      value: 1.542
    - type: precision_at_1000
      value: 0.202
    - type: precision_at_3
      value: 21.364
    - type: precision_at_5
      value: 15.336
    - type: recall_at_1
      value: 31.013
    - type: recall_at_10
      value: 61.934999999999995
    - type: recall_at_100
      value: 83.923
    - type: recall_at_1000
      value: 96.601
    - type: recall_at_3
      value: 46.86
    - type: recall_at_5
      value: 53.620000000000005
  - task:
      type: Retrieval
    dataset:
      type: mteb/cqadupstack-english
      name: MTEB CQADupstackEnglishRetrieval
      config: default
      split: test
      revision: ad9991cb51e31e31e430383c75ffb2885547b5f0
    metrics:
    - type: map_at_1
      value: 29.84
    - type: map_at_10
      value: 39.335
    - type: map_at_100
      value: 40.647
    - type: map_at_1000
      value: 40.778
    - type: map_at_3
      value: 36.556
    - type: map_at_5
      value: 38.048
    - type: mrr_at_1
      value: 36.815
    - type: mrr_at_10
      value: 45.175
    - type: mrr_at_100
      value: 45.907
    - type: mrr_at_1000
      value: 45.946999999999996
    - type: mrr_at_3
      value: 42.909000000000006
    - type: mrr_at_5
      value: 44.227
    - type: ndcg_at_1
      value: 36.815
    - type: ndcg_at_10
      value: 44.783
    - type: ndcg_at_100
      value: 49.551
    - type: ndcg_at_1000
      value: 51.612
    - type: ndcg_at_3
      value: 40.697
    - type: ndcg_at_5
      value: 42.558
    - type: precision_at_1
      value: 36.815
    - type: precision_at_10
      value: 8.363
    - type: precision_at_100
      value: 1.385
    - type: precision_at_1000
      value: 0.186
    - type: precision_at_3
      value: 19.342000000000002
    - type: precision_at_5
      value: 13.706999999999999
    - type: recall_at_1
      value: 29.84
    - type: recall_at_10
      value: 54.164
    - type: recall_at_100
      value: 74.36
    - type: recall_at_1000
      value: 87.484
    - type: recall_at_3
      value: 42.306
    - type: recall_at_5
      value: 47.371
  - task:
      type: Retrieval
    dataset:
      type: mteb/cqadupstack-gaming
      name: MTEB CQADupstackGamingRetrieval
      config: default
      split: test
      revision: 4885aa143210c98657558c04aaf3dc47cfb54340
    metrics:
    - type: map_at_1
      value: 39.231
    - type: map_at_10
      value: 51.44800000000001
    - type: map_at_100
      value: 52.574
    - type: map_at_1000
      value: 52.629999999999995
    - type: map_at_3
      value: 48.077
    - type: map_at_5
      value: 50.019000000000005
    - type: mrr_at_1
      value: 44.89
    - type: mrr_at_10
      value: 54.803000000000004
    - type: mrr_at_100
      value: 55.556000000000004
    - type: mrr_at_1000
      value: 55.584
    - type: mrr_at_3
      value: 52.32
    - type: mrr_at_5
      value: 53.846000000000004
    - type: ndcg_at_1
      value: 44.89
    - type: ndcg_at_10
      value: 57.228
    - type: ndcg_at_100
      value: 61.57
    - type: ndcg_at_1000
      value: 62.613
    - type: ndcg_at_3
      value: 51.727000000000004
    - type: ndcg_at_5
      value: 54.496
    - type: precision_at_1
      value: 44.89
    - type: precision_at_10
      value: 9.266
    - type: precision_at_100
      value: 1.2309999999999999
    - type: precision_at_1000
      value: 0.136
    - type: precision_at_3
      value: 23.051
    - type: precision_at_5
      value: 15.987000000000002
    - type: recall_at_1
      value: 39.231
    - type: recall_at_10
      value: 70.82000000000001
    - type: recall_at_100
      value: 89.446
    - type: recall_at_1000
      value: 96.665
    - type: recall_at_3
      value: 56.40500000000001
    - type: recall_at_5
      value: 62.993
  - task:
      type: Retrieval
    dataset:
      type: mteb/cqadupstack-gis
      name: MTEB CQADupstackGisRetrieval
      config: default
      split: test
      revision: 5003b3064772da1887988e05400cf3806fe491f2
    metrics:
    - type: map_at_1
      value: 25.296000000000003
    - type: map_at_10
      value: 34.021
    - type: map_at_100
      value: 35.158
    - type: map_at_1000
      value: 35.233
    - type: map_at_3
      value: 31.424999999999997
    - type: map_at_5
      value: 33.046
    - type: mrr_at_1
      value: 27.232
    - type: mrr_at_10
      value: 36.103
    - type: mrr_at_100
      value: 37.076
    - type: mrr_at_1000
      value: 37.135
    - type: mrr_at_3
      value: 33.635
    - type: mrr_at_5
      value: 35.211
    - type: ndcg_at_1
      value: 27.232
    - type: ndcg_at_10
      value: 38.878
    - type: ndcg_at_100
      value: 44.284
    - type: ndcg_at_1000
      value: 46.268
    - type: ndcg_at_3
      value: 33.94
    - type: ndcg_at_5
      value: 36.687
    - type: precision_at_1
      value: 27.232
    - type: precision_at_10
      value: 5.921
    - type: precision_at_100
      value: 0.907
    - type: precision_at_1000
      value: 0.11199999999999999
    - type: precision_at_3
      value: 14.426
    - type: precision_at_5
      value: 10.215
    - type: recall_at_1
      value: 25.296000000000003
    - type: recall_at_10
      value: 51.708
    - type: recall_at_100
      value: 76.36699999999999
    - type: recall_at_1000
      value: 91.306
    - type: recall_at_3
      value: 38.651
    - type: recall_at_5
      value: 45.201
  - task:
      type: Retrieval
    dataset:
      type: mteb/cqadupstack-mathematica
      name: MTEB CQADupstackMathematicaRetrieval
      config: default
      split: test
      revision: 90fceea13679c63fe563ded68f3b6f06e50061de
    metrics:
    - type: map_at_1
      value: 16.24
    - type: map_at_10
      value: 24.696
    - type: map_at_100
      value: 25.945
    - type: map_at_1000
      value: 26.069
    - type: map_at_3
      value: 22.542
    - type: map_at_5
      value: 23.526
    - type: mrr_at_1
      value: 20.149
    - type: mrr_at_10
      value: 29.584
    - type: mrr_at_100
      value: 30.548
    - type: mrr_at_1000
      value: 30.618000000000002
    - type: mrr_at_3
      value: 27.301
    - type: mrr_at_5
      value: 28.563
    - type: ndcg_at_1
      value: 20.149
    - type: ndcg_at_10
      value: 30.029
    - type: ndcg_at_100
      value: 35.812
    - type: ndcg_at_1000
      value: 38.755
    - type: ndcg_at_3
      value: 26.008
    - type: ndcg_at_5
      value: 27.517000000000003
    - type: precision_at_1
      value: 20.149
    - type: precision_at_10
      value: 5.647
    - type: precision_at_100
      value: 0.968
    - type: precision_at_1000
      value: 0.136
    - type: precision_at_3
      value: 12.934999999999999
    - type: precision_at_5
      value: 8.955
    - type: recall_at_1
      value: 16.24
    - type: recall_at_10
      value: 41.464
    - type: recall_at_100
      value: 66.781
    - type: recall_at_1000
      value: 87.85300000000001
    - type: recall_at_3
      value: 29.822
    - type: recall_at_5
      value: 34.096
  - task:
      type: Retrieval
    dataset:
      type: mteb/cqadupstack-physics
      name: MTEB CQADupstackPhysicsRetrieval
      config: default
      split: test
      revision: 79531abbd1fb92d06c6d6315a0cbbbf5bb247ea4
    metrics:
    - type: map_at_1
      value: 29.044999999999998
    - type: map_at_10
      value: 39.568999999999996
    - type: map_at_100
      value: 40.831
    - type: map_at_1000
      value: 40.948
    - type: map_at_3
      value: 36.495
    - type: map_at_5
      value: 38.21
    - type: mrr_at_1
      value: 35.611
    - type: mrr_at_10
      value: 45.175
    - type: mrr_at_100
      value: 45.974
    - type: mrr_at_1000
      value: 46.025
    - type: mrr_at_3
      value: 42.765
    - type: mrr_at_5
      value: 44.151
    - type: ndcg_at_1
      value: 35.611
    - type: ndcg_at_10
      value: 45.556999999999995
    - type: ndcg_at_100
      value: 50.86000000000001
    - type: ndcg_at_1000
      value: 52.983000000000004
    - type: ndcg_at_3
      value: 40.881
    - type: ndcg_at_5
      value: 43.035000000000004
    - type: precision_at_1
      value: 35.611
    - type: precision_at_10
      value: 8.306
    - type: precision_at_100
      value: 1.276
    - type: precision_at_1000
      value: 0.165
    - type: precision_at_3
      value: 19.57
    - type: precision_at_5
      value: 13.725000000000001
    - type: recall_at_1
      value: 29.044999999999998
    - type: recall_at_10
      value: 57.513999999999996
    - type: recall_at_100
      value: 80.152
    - type: recall_at_1000
      value: 93.982
    - type: recall_at_3
      value: 44.121
    - type: recall_at_5
      value: 50.007000000000005
  - task:
      type: Retrieval
    dataset:
      type: mteb/cqadupstack-programmers
      name: MTEB CQADupstackProgrammersRetrieval
      config: default
      split: test
      revision: 6184bc1440d2dbc7612be22b50686b8826d22b32
    metrics:
    - type: map_at_1
      value: 22.349
    - type: map_at_10
      value: 33.434000000000005
    - type: map_at_100
      value: 34.8
    - type: map_at_1000
      value: 34.919
    - type: map_at_3
      value: 30.348000000000003
    - type: map_at_5
      value: 31.917
    - type: mrr_at_1
      value: 28.195999999999998
    - type: mrr_at_10
      value: 38.557
    - type: mrr_at_100
      value: 39.550999999999995
    - type: mrr_at_1000
      value: 39.607
    - type: mrr_at_3
      value: 36.035000000000004
    - type: mrr_at_5
      value: 37.364999999999995
    - type: ndcg_at_1
      value: 28.195999999999998
    - type: ndcg_at_10
      value: 39.656000000000006
    - type: ndcg_at_100
      value: 45.507999999999996
    - type: ndcg_at_1000
      value: 47.848
    - type: ndcg_at_3
      value: 34.609
    - type: ndcg_at_5
      value: 36.65
    - type: precision_at_1
      value: 28.195999999999998
    - type: precision_at_10
      value: 7.534000000000001
    - type: precision_at_100
      value: 1.217
    - type: precision_at_1000
      value: 0.158
    - type: precision_at_3
      value: 17.085
    - type: precision_at_5
      value: 12.169
    - type: recall_at_1
      value: 22.349
    - type: recall_at_10
      value: 53.127
    - type: recall_at_100
      value: 77.884
    - type: recall_at_1000
      value: 93.705
    - type: recall_at_3
      value: 38.611000000000004
    - type: recall_at_5
      value: 44.182
  - task:
      type: Retrieval
    dataset:
      type: mteb/cqadupstack
      name: MTEB CQADupstackRetrieval
      config: default
      split: test
      revision: 4ffe81d471b1924886b33c7567bfb200e9eec5c4
    metrics:
    - type: map_at_1
      value: 25.215749999999996
    - type: map_at_10
      value: 34.332750000000004
    - type: map_at_100
      value: 35.58683333333333
    - type: map_at_1000
      value: 35.70458333333333
    - type: map_at_3
      value: 31.55441666666667
    - type: map_at_5
      value: 33.100833333333334
    - type: mrr_at_1
      value: 29.697250000000004
    - type: mrr_at_10
      value: 38.372249999999994
    - type: mrr_at_100
      value: 39.26708333333334
    - type: mrr_at_1000
      value: 39.3265
    - type: mrr_at_3
      value: 35.946083333333334
    - type: mrr_at_5
      value: 37.336999999999996
    - type: ndcg_at_1
      value: 29.697250000000004
    - type: ndcg_at_10
      value: 39.64575
    - type: ndcg_at_100
      value: 44.996833333333335
    - type: ndcg_at_1000
      value: 47.314499999999995
    - type: ndcg_at_3
      value: 34.93383333333334
    - type: ndcg_at_5
      value: 37.15291666666667
    - type: precision_at_1
      value: 29.697250000000004
    - type: precision_at_10
      value: 6.98825
    - type: precision_at_100
      value: 1.138
    - type: precision_at_1000
      value: 0.15283333333333332
    - type: precision_at_3
      value: 16.115583333333333
    - type: precision_at_5
      value: 11.460916666666666
    - type: recall_at_1
      value: 25.215749999999996
    - type: recall_at_10
      value: 51.261250000000004
    - type: recall_at_100
      value: 74.67258333333334
    - type: recall_at_1000
      value: 90.72033333333334
    - type: recall_at_3
      value: 38.1795
    - type: recall_at_5
      value: 43.90658333333334
  - task:
      type: Retrieval
    dataset:
      type: mteb/cqadupstack-stats
      name: MTEB CQADupstackStatsRetrieval
      config: default
      split: test
      revision: 65ac3a16b8e91f9cee4c9828cc7c335575432a2a
    metrics:
    - type: map_at_1
      value: 24.352
    - type: map_at_10
      value: 30.576999999999998
    - type: map_at_100
      value: 31.545
    - type: map_at_1000
      value: 31.642
    - type: map_at_3
      value: 28.605000000000004
    - type: map_at_5
      value: 29.828
    - type: mrr_at_1
      value: 26.994
    - type: mrr_at_10
      value: 33.151
    - type: mrr_at_100
      value: 33.973
    - type: mrr_at_1000
      value: 34.044999999999995
    - type: mrr_at_3
      value: 31.135
    - type: mrr_at_5
      value: 32.262
    - type: ndcg_at_1
      value: 26.994
    - type: ndcg_at_10
      value: 34.307
    - type: ndcg_at_100
      value: 39.079
    - type: ndcg_at_1000
      value: 41.548
    - type: ndcg_at_3
      value: 30.581000000000003
    - type: ndcg_at_5
      value: 32.541
    - type: precision_at_1
      value: 26.994
    - type: precision_at_10
      value: 5.244999999999999
    - type: precision_at_100
      value: 0.831
    - type: precision_at_1000
      value: 0.11100000000000002
    - type: precision_at_3
      value: 12.781
    - type: precision_at_5
      value: 9.017999999999999
    - type: recall_at_1
      value: 24.352
    - type: recall_at_10
      value: 43.126999999999995
    - type: recall_at_100
      value: 64.845
    - type: recall_at_1000
      value: 83.244
    - type: recall_at_3
      value: 33.308
    - type: recall_at_5
      value: 37.984
  - task:
      type: Retrieval
    dataset:
      type: mteb/cqadupstack-tex
      name: MTEB CQADupstackTexRetrieval
      config: default
      split: test
      revision: 46989137a86843e03a6195de44b09deda022eec7
    metrics:
    - type: map_at_1
      value: 16.592000000000002
    - type: map_at_10
      value: 23.29
    - type: map_at_100
      value: 24.423000000000002
    - type: map_at_1000
      value: 24.554000000000002
    - type: map_at_3
      value: 20.958
    - type: map_at_5
      value: 22.267
    - type: mrr_at_1
      value: 20.061999999999998
    - type: mrr_at_10
      value: 26.973999999999997
    - type: mrr_at_100
      value: 27.944999999999997
    - type: mrr_at_1000
      value: 28.023999999999997
    - type: mrr_at_3
      value: 24.839
    - type: mrr_at_5
      value: 26.033
    - type: ndcg_at_1
      value: 20.061999999999998
    - type: ndcg_at_10
      value: 27.682000000000002
    - type: ndcg_at_100
      value: 33.196
    - type: ndcg_at_1000
      value: 36.246
    - type: ndcg_at_3
      value: 23.559
    - type: ndcg_at_5
      value: 25.507
    - type: precision_at_1
      value: 20.061999999999998
    - type: precision_at_10
      value: 5.086
    - type: precision_at_100
      value: 0.9249999999999999
    - type: precision_at_1000
      value: 0.136
    - type: precision_at_3
      value: 11.046
    - type: precision_at_5
      value: 8.149000000000001
    - type: recall_at_1
      value: 16.592000000000002
    - type: recall_at_10
      value: 37.181999999999995
    - type: recall_at_100
      value: 62.224999999999994
    - type: recall_at_1000
      value: 84.072
    - type: recall_at_3
      value: 25.776
    - type: recall_at_5
      value: 30.680000000000003
  - task:
      type: Retrieval
    dataset:
      type: mteb/cqadupstack-unix
      name: MTEB CQADupstackUnixRetrieval
      config: default
      split: test
      revision: 6c6430d3a6d36f8d2a829195bc5dc94d7e063e53
    metrics:
    - type: map_at_1
      value: 26.035999999999998
    - type: map_at_10
      value: 34.447
    - type: map_at_100
      value: 35.697
    - type: map_at_1000
      value: 35.802
    - type: map_at_3
      value: 31.64
    - type: map_at_5
      value: 33.056999999999995
    - type: mrr_at_1
      value: 29.851
    - type: mrr_at_10
      value: 38.143
    - type: mrr_at_100
      value: 39.113
    - type: mrr_at_1000
      value: 39.175
    - type: mrr_at_3
      value: 35.665
    - type: mrr_at_5
      value: 36.901
    - type: ndcg_at_1
      value: 29.851
    - type: ndcg_at_10
      value: 39.554
    - type: ndcg_at_100
      value: 45.091
    - type: ndcg_at_1000
      value: 47.504000000000005
    - type: ndcg_at_3
      value: 34.414
    - type: ndcg_at_5
      value: 36.508
    - type: precision_at_1
      value: 29.851
    - type: precision_at_10
      value: 6.614000000000001
    - type: precision_at_100
      value: 1.051
    - type: precision_at_1000
      value: 0.13699999999999998
    - type: precision_at_3
      value: 15.329999999999998
    - type: precision_at_5
      value: 10.671999999999999
    - type: recall_at_1
      value: 26.035999999999998
    - type: recall_at_10
      value: 51.396
    - type: recall_at_100
      value: 75.09
    - type: recall_at_1000
      value: 91.904
    - type: recall_at_3
      value: 37.378
    - type: recall_at_5
      value: 42.69
  - task:
      type: Retrieval
    dataset:
      type: mteb/cqadupstack-webmasters
      name: MTEB CQADupstackWebmastersRetrieval
      config: default
      split: test
      revision: 160c094312a0e1facb97e55eeddb698c0abe3571
    metrics:
    - type: map_at_1
      value: 23.211000000000002
    - type: map_at_10
      value: 32.231
    - type: map_at_100
      value: 33.772999999999996
    - type: map_at_1000
      value: 33.982
    - type: map_at_3
      value: 29.128
    - type: map_at_5
      value: 31.002999999999997
    - type: mrr_at_1
      value: 27.668
    - type: mrr_at_10
      value: 36.388
    - type: mrr_at_100
      value: 37.384
    - type: mrr_at_1000
      value: 37.44
    - type: mrr_at_3
      value: 33.762
    - type: mrr_at_5
      value: 35.234
    - type: ndcg_at_1
      value: 27.668
    - type: ndcg_at_10
      value: 38.043
    - type: ndcg_at_100
      value: 44.21
    - type: ndcg_at_1000
      value: 46.748
    - type: ndcg_at_3
      value: 32.981
    - type: ndcg_at_5
      value: 35.58
    - type: precision_at_1
      value: 27.668
    - type: precision_at_10
      value: 7.352
    - type: precision_at_100
      value: 1.5
    - type: precision_at_1000
      value: 0.23700000000000002
    - type: precision_at_3
      value: 15.613
    - type: precision_at_5
      value: 11.501999999999999
    - type: recall_at_1
      value: 23.211000000000002
    - type: recall_at_10
      value: 49.851
    - type: recall_at_100
      value: 77.596
    - type: recall_at_1000
      value: 93.683
    - type: recall_at_3
      value: 35.403
    - type: recall_at_5
      value: 42.485
  - task:
      type: Retrieval
    dataset:
      type: mteb/cqadupstack-wordpress
      name: MTEB CQADupstackWordpressRetrieval
      config: default
      split: test
      revision: 4ffe81d471b1924886b33c7567bfb200e9eec5c4
    metrics:
    - type: map_at_1
      value: 19.384
    - type: map_at_10
      value: 26.262999999999998
    - type: map_at_100
      value: 27.409
    - type: map_at_1000
      value: 27.526
    - type: map_at_3
      value: 23.698
    - type: map_at_5
      value: 25.217
    - type: mrr_at_1
      value: 20.702
    - type: mrr_at_10
      value: 27.810000000000002
    - type: mrr_at_100
      value: 28.863
    - type: mrr_at_1000
      value: 28.955
    - type: mrr_at_3
      value: 25.230999999999998
    - type: mrr_at_5
      value: 26.821
    - type: ndcg_at_1
      value: 20.702
    - type: ndcg_at_10
      value: 30.688
    - type: ndcg_at_100
      value: 36.138999999999996
    - type: ndcg_at_1000
      value: 38.984
    - type: ndcg_at_3
      value: 25.663000000000004
    - type: ndcg_at_5
      value: 28.242
    - type: precision_at_1
      value: 20.702
    - type: precision_at_10
      value: 4.954
    - type: precision_at_100
      value: 0.823
    - type: precision_at_1000
      value: 0.11800000000000001
    - type: precision_at_3
      value: 10.844
    - type: precision_at_5
      value: 8.096
    - type: recall_at_1
      value: 19.384
    - type: recall_at_10
      value: 42.847
    - type: recall_at_100
      value: 67.402
    - type: recall_at_1000
      value: 88.145
    - type: recall_at_3
      value: 29.513
    - type: recall_at_5
      value: 35.57
  - task:
      type: Retrieval
    dataset:
      type: mteb/climate-fever
      name: MTEB ClimateFEVER
      config: default
      split: test
      revision: 47f2ac6acb640fc46020b02a5b59fdda04d39380
    metrics:
    - type: map_at_1
      value: 14.915000000000001
    - type: map_at_10
      value: 25.846999999999998
    - type: map_at_100
      value: 27.741
    - type: map_at_1000
      value: 27.921000000000003
    - type: map_at_3
      value: 21.718
    - type: map_at_5
      value: 23.948
    - type: mrr_at_1
      value: 33.941
    - type: mrr_at_10
      value: 46.897
    - type: mrr_at_100
      value: 47.63
    - type: mrr_at_1000
      value: 47.658
    - type: mrr_at_3
      value: 43.919999999999995
    - type: mrr_at_5
      value: 45.783
    - type: ndcg_at_1
      value: 33.941
    - type: ndcg_at_10
      value: 35.202
    - type: ndcg_at_100
      value: 42.132
    - type: ndcg_at_1000
      value: 45.190999999999995
    - type: ndcg_at_3
      value: 29.68
    - type: ndcg_at_5
      value: 31.631999999999998
    - type: precision_at_1
      value: 33.941
    - type: precision_at_10
      value: 10.906
    - type: precision_at_100
      value: 1.8339999999999999
    - type: precision_at_1000
      value: 0.241
    - type: precision_at_3
      value: 22.606
    - type: precision_at_5
      value: 17.081
    - type: recall_at_1
      value: 14.915000000000001
    - type: recall_at_10
      value: 40.737
    - type: recall_at_100
      value: 64.42
    - type: recall_at_1000
      value: 81.435
    - type: recall_at_3
      value: 26.767000000000003
    - type: recall_at_5
      value: 32.895
  - task:
      type: Retrieval
    dataset:
      type: mteb/dbpedia
      name: MTEB DBPedia
      config: default
      split: test
      revision: c0f706b76e590d620bd6618b3ca8efdd34e2d659
    metrics:
    - type: map_at_1
      value: 8.665000000000001
    - type: map_at_10
      value: 19.087
    - type: map_at_100
      value: 26.555
    - type: map_at_1000
      value: 28.105999999999998
    - type: map_at_3
      value: 13.858999999999998
    - type: map_at_5
      value: 16.083
    - type: mrr_at_1
      value: 68.5
    - type: mrr_at_10
      value: 76.725
    - type: mrr_at_100
      value: 76.974
    - type: mrr_at_1000
      value: 76.981
    - type: mrr_at_3
      value: 75.583
    - type: mrr_at_5
      value: 76.208
    - type: ndcg_at_1
      value: 55.875
    - type: ndcg_at_10
      value: 41.018
    - type: ndcg_at_100
      value: 44.982
    - type: ndcg_at_1000
      value: 52.43
    - type: ndcg_at_3
      value: 46.534
    - type: ndcg_at_5
      value: 43.083
    - type: precision_at_1
      value: 68.5
    - type: precision_at_10
      value: 32.35
    - type: precision_at_100
      value: 10.078
    - type: precision_at_1000
      value: 1.957
    - type: precision_at_3
      value: 50.083
    - type: precision_at_5
      value: 41.3
    - type: recall_at_1
      value: 8.665000000000001
    - type: recall_at_10
      value: 24.596999999999998
    - type: recall_at_100
      value: 50.612
    - type: recall_at_1000
      value: 74.24
    - type: recall_at_3
      value: 15.337
    - type: recall_at_5
      value: 18.796
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
      value: 55.06500000000001
    - type: f1
      value: 49.827367590822035
  - task:
      type: Retrieval
    dataset:
      type: mteb/fever
      name: MTEB FEVER
      config: default
      split: test
      revision: bea83ef9e8fb933d90a2f1d5515737465d613e12
    metrics:
    - type: map_at_1
      value: 76.059
    - type: map_at_10
      value: 83.625
    - type: map_at_100
      value: 83.845
    - type: map_at_1000
      value: 83.858
    - type: map_at_3
      value: 82.67099999999999
    - type: map_at_5
      value: 83.223
    - type: mrr_at_1
      value: 82.013
    - type: mrr_at_10
      value: 88.44800000000001
    - type: mrr_at_100
      value: 88.535
    - type: mrr_at_1000
      value: 88.537
    - type: mrr_at_3
      value: 87.854
    - type: mrr_at_5
      value: 88.221
    - type: ndcg_at_1
      value: 82.013
    - type: ndcg_at_10
      value: 87.128
    - type: ndcg_at_100
      value: 87.922
    - type: ndcg_at_1000
      value: 88.166
    - type: ndcg_at_3
      value: 85.648
    - type: ndcg_at_5
      value: 86.366
    - type: precision_at_1
      value: 82.013
    - type: precision_at_10
      value: 10.32
    - type: precision_at_100
      value: 1.093
    - type: precision_at_1000
      value: 0.11299999999999999
    - type: precision_at_3
      value: 32.408
    - type: precision_at_5
      value: 19.973
    - type: recall_at_1
      value: 76.059
    - type: recall_at_10
      value: 93.229
    - type: recall_at_100
      value: 96.387
    - type: recall_at_1000
      value: 97.916
    - type: recall_at_3
      value: 89.025
    - type: recall_at_5
      value: 90.96300000000001
  - task:
      type: Retrieval
    dataset:
      type: mteb/fiqa
      name: MTEB FiQA2018
      config: default
      split: test
      revision: 27a168819829fe9bcd655c2df245fb19452e8e06
    metrics:
    - type: map_at_1
      value: 20.479
    - type: map_at_10
      value: 33.109
    - type: map_at_100
      value: 34.803
    - type: map_at_1000
      value: 35.003
    - type: map_at_3
      value: 28.967
    - type: map_at_5
      value: 31.385
    - type: mrr_at_1
      value: 40.278000000000006
    - type: mrr_at_10
      value: 48.929
    - type: mrr_at_100
      value: 49.655
    - type: mrr_at_1000
      value: 49.691
    - type: mrr_at_3
      value: 46.605000000000004
    - type: mrr_at_5
      value: 48.056
    - type: ndcg_at_1
      value: 40.278000000000006
    - type: ndcg_at_10
      value: 40.649
    - type: ndcg_at_100
      value: 47.027
    - type: ndcg_at_1000
      value: 50.249
    - type: ndcg_at_3
      value: 37.364000000000004
    - type: ndcg_at_5
      value: 38.494
    - type: precision_at_1
      value: 40.278000000000006
    - type: precision_at_10
      value: 11.327
    - type: precision_at_100
      value: 1.802
    - type: precision_at_1000
      value: 0.23700000000000002
    - type: precision_at_3
      value: 25.102999999999998
    - type: precision_at_5
      value: 18.457
    - type: recall_at_1
      value: 20.479
    - type: recall_at_10
      value: 46.594
    - type: recall_at_100
      value: 71.101
    - type: recall_at_1000
      value: 90.31099999999999
    - type: recall_at_3
      value: 33.378
    - type: recall_at_5
      value: 39.587
  - task:
      type: Retrieval
    dataset:
      type: mteb/hotpotqa
      name: MTEB HotpotQA
      config: default
      split: test
      revision: ab518f4d6fcca38d87c25209f94beba119d02014
    metrics:
    - type: map_at_1
      value: 36.59
    - type: map_at_10
      value: 58.178
    - type: map_at_100
      value: 59.095
    - type: map_at_1000
      value: 59.16400000000001
    - type: map_at_3
      value: 54.907
    - type: map_at_5
      value: 56.89999999999999
    - type: mrr_at_1
      value: 73.18
    - type: mrr_at_10
      value: 79.935
    - type: mrr_at_100
      value: 80.16799999999999
    - type: mrr_at_1000
      value: 80.17800000000001
    - type: mrr_at_3
      value: 78.776
    - type: mrr_at_5
      value: 79.522
    - type: ndcg_at_1
      value: 73.18
    - type: ndcg_at_10
      value: 66.538
    - type: ndcg_at_100
      value: 69.78
    - type: ndcg_at_1000
      value: 71.102
    - type: ndcg_at_3
      value: 61.739
    - type: ndcg_at_5
      value: 64.35600000000001
    - type: precision_at_1
      value: 73.18
    - type: precision_at_10
      value: 14.035
    - type: precision_at_100
      value: 1.657
    - type: precision_at_1000
      value: 0.183
    - type: precision_at_3
      value: 39.684999999999995
    - type: precision_at_5
      value: 25.885
    - type: recall_at_1
      value: 36.59
    - type: recall_at_10
      value: 70.176
    - type: recall_at_100
      value: 82.836
    - type: recall_at_1000
      value: 91.526
    - type: recall_at_3
      value: 59.526999999999994
    - type: recall_at_5
      value: 64.713
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
      value: 90.1472
    - type: ap
      value: 85.73994227076815
    - type: f1
      value: 90.1271700788608
  - task:
      type: Retrieval
    dataset:
      type: mteb/msmarco
      name: MTEB MSMARCO
      config: default
      split: dev
      revision: c5a29a104738b98a9e76336939199e264163d4a0
    metrics:
    - type: map_at_1
      value: 21.689
    - type: map_at_10
      value: 33.518
    - type: map_at_100
      value: 34.715
    - type: map_at_1000
      value: 34.766000000000005
    - type: map_at_3
      value: 29.781000000000002
    - type: map_at_5
      value: 31.838
    - type: mrr_at_1
      value: 22.249
    - type: mrr_at_10
      value: 34.085
    - type: mrr_at_100
      value: 35.223
    - type: mrr_at_1000
      value: 35.266999999999996
    - type: mrr_at_3
      value: 30.398999999999997
    - type: mrr_at_5
      value: 32.437
    - type: ndcg_at_1
      value: 22.249
    - type: ndcg_at_10
      value: 40.227000000000004
    - type: ndcg_at_100
      value: 45.961999999999996
    - type: ndcg_at_1000
      value: 47.248000000000005
    - type: ndcg_at_3
      value: 32.566
    - type: ndcg_at_5
      value: 36.229
    - type: precision_at_1
      value: 22.249
    - type: precision_at_10
      value: 6.358
    - type: precision_at_100
      value: 0.923
    - type: precision_at_1000
      value: 0.10300000000000001
    - type: precision_at_3
      value: 13.83
    - type: precision_at_5
      value: 10.145999999999999
    - type: recall_at_1
      value: 21.689
    - type: recall_at_10
      value: 60.92999999999999
    - type: recall_at_100
      value: 87.40599999999999
    - type: recall_at_1000
      value: 97.283
    - type: recall_at_3
      value: 40.01
    - type: recall_at_5
      value: 48.776
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
      value: 95.28727770177838
    - type: f1
      value: 95.02577308660041
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
      value: 79.5736434108527
    - type: f1
      value: 61.2451202054398
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
      value: 76.01210490921318
    - type: f1
      value: 73.70188053982473
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
      value: 79.33422999327504
    - type: f1
      value: 79.48369022509658
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
      value: 34.70891567267726
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
      value: 32.15203494451706
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
      value: 31.919517862194173
    - type: mrr
      value: 33.15466289140483
  - task:
      type: Retrieval
    dataset:
      type: mteb/nfcorpus
      name: MTEB NFCorpus
      config: default
      split: test
      revision: ec0fa4fe99da2ff19ca1214b7966684033a58814
    metrics:
    - type: map_at_1
      value: 5.992
    - type: map_at_10
      value: 13.197000000000001
    - type: map_at_100
      value: 16.907
    - type: map_at_1000
      value: 18.44
    - type: map_at_3
      value: 9.631
    - type: map_at_5
      value: 11.243
    - type: mrr_at_1
      value: 44.272
    - type: mrr_at_10
      value: 53.321
    - type: mrr_at_100
      value: 53.903
    - type: mrr_at_1000
      value: 53.952999999999996
    - type: mrr_at_3
      value: 51.393
    - type: mrr_at_5
      value: 52.708999999999996
    - type: ndcg_at_1
      value: 42.415000000000006
    - type: ndcg_at_10
      value: 34.921
    - type: ndcg_at_100
      value: 32.384
    - type: ndcg_at_1000
      value: 41.260000000000005
    - type: ndcg_at_3
      value: 40.186
    - type: ndcg_at_5
      value: 37.89
    - type: precision_at_1
      value: 44.272
    - type: precision_at_10
      value: 26.006
    - type: precision_at_100
      value: 8.44
    - type: precision_at_1000
      value: 2.136
    - type: precision_at_3
      value: 37.977
    - type: precision_at_5
      value: 32.755
    - type: recall_at_1
      value: 5.992
    - type: recall_at_10
      value: 17.01
    - type: recall_at_100
      value: 33.080999999999996
    - type: recall_at_1000
      value: 65.054
    - type: recall_at_3
      value: 10.528
    - type: recall_at_5
      value: 13.233
  - task:
      type: Retrieval
    dataset:
      type: mteb/nq
      name: MTEB NQ
      config: default
      split: test
      revision: b774495ed302d8c44a3a7ea25c90dbce03968f31
    metrics:
    - type: map_at_1
      value: 28.871999999999996
    - type: map_at_10
      value: 43.286
    - type: map_at_100
      value: 44.432
    - type: map_at_1000
      value: 44.464999999999996
    - type: map_at_3
      value: 38.856
    - type: map_at_5
      value: 41.514
    - type: mrr_at_1
      value: 32.619
    - type: mrr_at_10
      value: 45.75
    - type: mrr_at_100
      value: 46.622
    - type: mrr_at_1000
      value: 46.646
    - type: mrr_at_3
      value: 41.985
    - type: mrr_at_5
      value: 44.277
    - type: ndcg_at_1
      value: 32.59
    - type: ndcg_at_10
      value: 50.895999999999994
    - type: ndcg_at_100
      value: 55.711999999999996
    - type: ndcg_at_1000
      value: 56.48800000000001
    - type: ndcg_at_3
      value: 42.504999999999995
    - type: ndcg_at_5
      value: 46.969
    - type: precision_at_1
      value: 32.59
    - type: precision_at_10
      value: 8.543000000000001
    - type: precision_at_100
      value: 1.123
    - type: precision_at_1000
      value: 0.12
    - type: precision_at_3
      value: 19.448
    - type: precision_at_5
      value: 14.218
    - type: recall_at_1
      value: 28.871999999999996
    - type: recall_at_10
      value: 71.748
    - type: recall_at_100
      value: 92.55499999999999
    - type: recall_at_1000
      value: 98.327
    - type: recall_at_3
      value: 49.944
    - type: recall_at_5
      value: 60.291
  - task:
      type: Retrieval
    dataset:
      type: mteb/quora
      name: MTEB QuoraRetrieval
      config: default
      split: test
      revision: e4e08e0b7dbe3c8700f0daef558ff32256715259
    metrics:
    - type: map_at_1
      value: 70.664
    - type: map_at_10
      value: 84.681
    - type: map_at_100
      value: 85.289
    - type: map_at_1000
      value: 85.306
    - type: map_at_3
      value: 81.719
    - type: map_at_5
      value: 83.601
    - type: mrr_at_1
      value: 81.35
    - type: mrr_at_10
      value: 87.591
    - type: mrr_at_100
      value: 87.691
    - type: mrr_at_1000
      value: 87.693
    - type: mrr_at_3
      value: 86.675
    - type: mrr_at_5
      value: 87.29299999999999
    - type: ndcg_at_1
      value: 81.33
    - type: ndcg_at_10
      value: 88.411
    - type: ndcg_at_100
      value: 89.579
    - type: ndcg_at_1000
      value: 89.687
    - type: ndcg_at_3
      value: 85.613
    - type: ndcg_at_5
      value: 87.17
    - type: precision_at_1
      value: 81.33
    - type: precision_at_10
      value: 13.422
    - type: precision_at_100
      value: 1.5270000000000001
    - type: precision_at_1000
      value: 0.157
    - type: precision_at_3
      value: 37.463
    - type: precision_at_5
      value: 24.646
    - type: recall_at_1
      value: 70.664
    - type: recall_at_10
      value: 95.54
    - type: recall_at_100
      value: 99.496
    - type: recall_at_1000
      value: 99.978
    - type: recall_at_3
      value: 87.481
    - type: recall_at_5
      value: 91.88499999999999
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
      value: 55.40341814991112
  - task:
      type: Clustering
    dataset:
      type: mteb/reddit-clustering-p2p
      name: MTEB RedditClusteringP2P
      config: default
      split: test
      revision: 385e3cb46b4cfa89021f56c4380204149d0efe33
    metrics:
    - type: v_measure
      value: 61.231318481346655
  - task:
      type: Retrieval
    dataset:
      type: mteb/scidocs
      name: MTEB SCIDOCS
      config: default
      split: test
      revision: f8c2fcf00f625baaa80f62ec5bd9e1fff3b8ae88
    metrics:
    - type: map_at_1
      value: 4.833
    - type: map_at_10
      value: 13.149
    - type: map_at_100
      value: 15.578
    - type: map_at_1000
      value: 15.963
    - type: map_at_3
      value: 9.269
    - type: map_at_5
      value: 11.182
    - type: mrr_at_1
      value: 23.9
    - type: mrr_at_10
      value: 35.978
    - type: mrr_at_100
      value: 37.076
    - type: mrr_at_1000
      value: 37.126
    - type: mrr_at_3
      value: 32.333
    - type: mrr_at_5
      value: 34.413
    - type: ndcg_at_1
      value: 23.9
    - type: ndcg_at_10
      value: 21.823
    - type: ndcg_at_100
      value: 30.833
    - type: ndcg_at_1000
      value: 36.991
    - type: ndcg_at_3
      value: 20.465
    - type: ndcg_at_5
      value: 17.965999999999998
    - type: precision_at_1
      value: 23.9
    - type: precision_at_10
      value: 11.49
    - type: precision_at_100
      value: 2.444
    - type: precision_at_1000
      value: 0.392
    - type: precision_at_3
      value: 19.3
    - type: precision_at_5
      value: 15.959999999999999
    - type: recall_at_1
      value: 4.833
    - type: recall_at_10
      value: 23.294999999999998
    - type: recall_at_100
      value: 49.63
    - type: recall_at_1000
      value: 79.49199999999999
    - type: recall_at_3
      value: 11.732
    - type: recall_at_5
      value: 16.167
  - task:
      type: STS
    dataset:
      type: mteb/sickr-sts
      name: MTEB SICK-R
      config: default
      split: test
      revision: 20a6d6f312dd54037fe07a32d58e5e168867909d
    metrics:
    - type: cos_sim_pearson
      value: 85.62938108735759
    - type: cos_sim_spearman
      value: 80.30777094408789
    - type: euclidean_pearson
      value: 82.94516686659536
    - type: euclidean_spearman
      value: 80.34489663248169
    - type: manhattan_pearson
      value: 82.85830094736245
    - type: manhattan_spearman
      value: 80.24902623215449
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
      value: 85.23777464247604
    - type: cos_sim_spearman
      value: 75.75714864112797
    - type: euclidean_pearson
      value: 82.33806918604493
    - type: euclidean_spearman
      value: 75.45282124387357
    - type: manhattan_pearson
      value: 82.32555620660538
    - type: manhattan_spearman
      value: 75.49228731684082
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
      value: 84.88151620954451
    - type: cos_sim_spearman
      value: 86.08377598473446
    - type: euclidean_pearson
      value: 85.36958329369413
    - type: euclidean_spearman
      value: 86.10274219670679
    - type: manhattan_pearson
      value: 85.25873897594711
    - type: manhattan_spearman
      value: 85.98096461661584
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
      value: 84.29360558735978
    - type: cos_sim_spearman
      value: 82.28284203795577
    - type: euclidean_pearson
      value: 83.81636655536633
    - type: euclidean_spearman
      value: 82.24340438530236
    - type: manhattan_pearson
      value: 83.83914453428608
    - type: manhattan_spearman
      value: 82.28391354080694
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
      value: 87.47344180426744
    - type: cos_sim_spearman
      value: 88.90045649789438
    - type: euclidean_pearson
      value: 88.43020815961273
    - type: euclidean_spearman
      value: 89.0087449011776
    - type: manhattan_pearson
      value: 88.37601826505525
    - type: manhattan_spearman
      value: 88.96756360690617
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
      value: 83.35997025304613
    - type: cos_sim_spearman
      value: 85.18237675717147
    - type: euclidean_pearson
      value: 84.46478196990202
    - type: euclidean_spearman
      value: 85.27748677712205
    - type: manhattan_pearson
      value: 84.29342543953123
    - type: manhattan_spearman
      value: 85.10579612516567
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
      value: 88.56668329596836
    - type: cos_sim_spearman
      value: 88.72837234129177
    - type: euclidean_pearson
      value: 89.39395650897828
    - type: euclidean_spearman
      value: 88.82001247906778
    - type: manhattan_pearson
      value: 89.41735354368878
    - type: manhattan_spearman
      value: 88.95159141850039
  - task:
      type: STS
    dataset:
      type: mteb/sts22-crosslingual-sts
      name: MTEB STS22 (en)
      config: en
      split: test
      revision: eea2b4fe26a775864c896887d910b76a8098ad3f
    metrics:
    - type: cos_sim_pearson
      value: 67.466167902991
    - type: cos_sim_spearman
      value: 68.54466147197274
    - type: euclidean_pearson
      value: 69.35551179564695
    - type: euclidean_spearman
      value: 68.75455717749132
    - type: manhattan_pearson
      value: 69.42432368208264
    - type: manhattan_spearman
      value: 68.83203709670562
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
      value: 85.33241300373689
    - type: cos_sim_spearman
      value: 86.97909372129874
    - type: euclidean_pearson
      value: 86.99526113559924
    - type: euclidean_spearman
      value: 87.02644372623219
    - type: manhattan_pearson
      value: 86.78744182759846
    - type: manhattan_spearman
      value: 86.8886180198196
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
      value: 86.18374413668717
    - type: mrr
      value: 95.93213068703264
  - task:
      type: Retrieval
    dataset:
      type: mteb/scifact
      name: MTEB SciFact
      config: default
      split: test
      revision: 0228b52cf27578f30900b9e5271d331663a030d7
    metrics:
    - type: map_at_1
      value: 58.31699999999999
    - type: map_at_10
      value: 67.691
    - type: map_at_100
      value: 68.201
    - type: map_at_1000
      value: 68.232
    - type: map_at_3
      value: 64.47800000000001
    - type: map_at_5
      value: 66.51
    - type: mrr_at_1
      value: 61.0
    - type: mrr_at_10
      value: 68.621
    - type: mrr_at_100
      value: 68.973
    - type: mrr_at_1000
      value: 69.002
    - type: mrr_at_3
      value: 66.111
    - type: mrr_at_5
      value: 67.578
    - type: ndcg_at_1
      value: 61.0
    - type: ndcg_at_10
      value: 72.219
    - type: ndcg_at_100
      value: 74.397
    - type: ndcg_at_1000
      value: 75.021
    - type: ndcg_at_3
      value: 66.747
    - type: ndcg_at_5
      value: 69.609
    - type: precision_at_1
      value: 61.0
    - type: precision_at_10
      value: 9.6
    - type: precision_at_100
      value: 1.08
    - type: precision_at_1000
      value: 0.11299999999999999
    - type: precision_at_3
      value: 25.667
    - type: precision_at_5
      value: 17.267
    - type: recall_at_1
      value: 58.31699999999999
    - type: recall_at_10
      value: 85.233
    - type: recall_at_100
      value: 95.167
    - type: recall_at_1000
      value: 99.667
    - type: recall_at_3
      value: 70.589
    - type: recall_at_5
      value: 77.628
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
      value: 99.83267326732673
    - type: cos_sim_ap
      value: 96.13707107038228
    - type: cos_sim_f1
      value: 91.48830263812842
    - type: cos_sim_precision
      value: 91.0802775024777
    - type: cos_sim_recall
      value: 91.9
    - type: dot_accuracy
      value: 99.83069306930693
    - type: dot_ap
      value: 96.21199069147254
    - type: dot_f1
      value: 91.36295556665004
    - type: dot_precision
      value: 91.22632103688933
    - type: dot_recall
      value: 91.5
    - type: euclidean_accuracy
      value: 99.83267326732673
    - type: euclidean_ap
      value: 96.08957801367436
    - type: euclidean_f1
      value: 91.33004926108374
    - type: euclidean_precision
      value: 90.0
    - type: euclidean_recall
      value: 92.7
    - type: manhattan_accuracy
      value: 99.83564356435643
    - type: manhattan_ap
      value: 96.10534946461945
    - type: manhattan_f1
      value: 91.74950298210736
    - type: manhattan_precision
      value: 91.20553359683794
    - type: manhattan_recall
      value: 92.30000000000001
    - type: max_accuracy
      value: 99.83564356435643
    - type: max_ap
      value: 96.21199069147254
    - type: max_f1
      value: 91.74950298210736
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
      value: 62.045718843534736
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
      value: 36.6501777041092
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
      value: 52.963913408053955
    - type: mrr
      value: 53.87972423818012
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
      value: 30.44195730764998
    - type: cos_sim_spearman
      value: 30.59626288679397
    - type: dot_pearson
      value: 30.22974492404086
    - type: dot_spearman
      value: 29.345245972906497
  - task:
      type: Retrieval
    dataset:
      type: mteb/trec-covid
      name: MTEB TRECCOVID
      config: default
      split: test
      revision: bb9466bac8153a0349341eb1b22e06409e78ef4e
    metrics:
    - type: map_at_1
      value: 0.24
    - type: map_at_10
      value: 2.01
    - type: map_at_100
      value: 11.928999999999998
    - type: map_at_1000
      value: 29.034
    - type: map_at_3
      value: 0.679
    - type: map_at_5
      value: 1.064
    - type: mrr_at_1
      value: 92.0
    - type: mrr_at_10
      value: 96.0
    - type: mrr_at_100
      value: 96.0
    - type: mrr_at_1000
      value: 96.0
    - type: mrr_at_3
      value: 96.0
    - type: mrr_at_5
      value: 96.0
    - type: ndcg_at_1
      value: 87.0
    - type: ndcg_at_10
      value: 80.118
    - type: ndcg_at_100
      value: 60.753
    - type: ndcg_at_1000
      value: 54.632999999999996
    - type: ndcg_at_3
      value: 83.073
    - type: ndcg_at_5
      value: 80.733
    - type: precision_at_1
      value: 92.0
    - type: precision_at_10
      value: 84.8
    - type: precision_at_100
      value: 62.019999999999996
    - type: precision_at_1000
      value: 24.028
    - type: precision_at_3
      value: 87.333
    - type: precision_at_5
      value: 85.2
    - type: recall_at_1
      value: 0.24
    - type: recall_at_10
      value: 2.205
    - type: recall_at_100
      value: 15.068000000000001
    - type: recall_at_1000
      value: 51.796
    - type: recall_at_3
      value: 0.698
    - type: recall_at_5
      value: 1.1199999999999999
  - task:
      type: Retrieval
    dataset:
      type: mteb/touche2020
      name: MTEB Touche2020
      config: default
      split: test
      revision: a34f9a33db75fa0cbb21bb5cfc3dae8dc8bec93f
    metrics:
    - type: map_at_1
      value: 3.066
    - type: map_at_10
      value: 9.219
    - type: map_at_100
      value: 15.387
    - type: map_at_1000
      value: 16.957
    - type: map_at_3
      value: 5.146
    - type: map_at_5
      value: 6.6739999999999995
    - type: mrr_at_1
      value: 40.816
    - type: mrr_at_10
      value: 50.844
    - type: mrr_at_100
      value: 51.664
    - type: mrr_at_1000
      value: 51.664
    - type: mrr_at_3
      value: 46.259
    - type: mrr_at_5
      value: 49.116
    - type: ndcg_at_1
      value: 37.755
    - type: ndcg_at_10
      value: 23.477
    - type: ndcg_at_100
      value: 36.268
    - type: ndcg_at_1000
      value: 47.946
    - type: ndcg_at_3
      value: 25.832
    - type: ndcg_at_5
      value: 24.235
    - type: precision_at_1
      value: 40.816
    - type: precision_at_10
      value: 20.204
    - type: precision_at_100
      value: 7.611999999999999
    - type: precision_at_1000
      value: 1.543
    - type: precision_at_3
      value: 25.169999999999998
    - type: precision_at_5
      value: 23.265
    - type: recall_at_1
      value: 3.066
    - type: recall_at_10
      value: 14.985999999999999
    - type: recall_at_100
      value: 47.902
    - type: recall_at_1000
      value: 83.56400000000001
    - type: recall_at_3
      value: 5.755
    - type: recall_at_5
      value: 8.741999999999999
  - task:
      type: Classification
    dataset:
      type: mteb/toxic_conversations_50k
      name: MTEB ToxicConversationsClassification
      config: default
      split: test
      revision: edfaf9da55d3dd50d43143d90c1ac476895ae6de
    metrics:
    - type: accuracy
      value: 69.437
    - type: ap
      value: 12.844066827082706
    - type: f1
      value: 52.74974809872495
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
      value: 61.26768534238823
    - type: f1
      value: 61.65100187399282
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
      value: 49.860968711078804
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
      value: 85.7423854085951
    - type: cos_sim_ap
      value: 73.47560303339571
    - type: cos_sim_f1
      value: 67.372778183589
    - type: cos_sim_precision
      value: 62.54520795660036
    - type: cos_sim_recall
      value: 73.00791556728232
    - type: dot_accuracy
      value: 85.36091077069798
    - type: dot_ap
      value: 72.42521572307255
    - type: dot_f1
      value: 66.90576304724215
    - type: dot_precision
      value: 62.96554934823091
    - type: dot_recall
      value: 71.37203166226914
    - type: euclidean_accuracy
      value: 85.76026703224653
    - type: euclidean_ap
      value: 73.44852563860128
    - type: euclidean_f1
      value: 67.3
    - type: euclidean_precision
      value: 63.94299287410926
    - type: euclidean_recall
      value: 71.02902374670185
    - type: manhattan_accuracy
      value: 85.7423854085951
    - type: manhattan_ap
      value: 73.2635034755551
    - type: manhattan_f1
      value: 67.3180263800684
    - type: manhattan_precision
      value: 62.66484765802638
    - type: manhattan_recall
      value: 72.71767810026385
    - type: max_accuracy
      value: 85.76026703224653
    - type: max_ap
      value: 73.47560303339571
    - type: max_f1
      value: 67.372778183589
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
      value: 88.67543757519307
    - type: cos_sim_ap
      value: 85.35516518531304
    - type: cos_sim_f1
      value: 77.58197635511934
    - type: cos_sim_precision
      value: 75.01078360891445
    - type: cos_sim_recall
      value: 80.33569448721897
    - type: dot_accuracy
      value: 87.61400240617844
    - type: dot_ap
      value: 83.0774968268665
    - type: dot_f1
      value: 75.68229012162561
    - type: dot_precision
      value: 72.99713876967095
    - type: dot_recall
      value: 78.57252848783493
    - type: euclidean_accuracy
      value: 88.73753250281368
    - type: euclidean_ap
      value: 85.48043564821317
    - type: euclidean_f1
      value: 77.75975862719216
    - type: euclidean_precision
      value: 76.21054187920456
    - type: euclidean_recall
      value: 79.37326763166
    - type: manhattan_accuracy
      value: 88.75111576823068
    - type: manhattan_ap
      value: 85.44993439423668
    - type: manhattan_f1
      value: 77.6861329994845
    - type: manhattan_precision
      value: 74.44601270289344
    - type: manhattan_recall
      value: 81.22112719433323
    - type: max_accuracy
      value: 88.75111576823068
    - type: max_ap
      value: 85.48043564821317
    - type: max_f1
      value: 77.75975862719216
---
<h1 align="center">NoInstruct small Embedding v0</h1>

*NoInstruct Embedding: Asymmetric Pooling is All You Need*

This model has improved retrieval performance compared to the [avsolatorio/GIST-small-Embedding-v0](https://huggingface.co/avsolatorio/GIST-small-Embedding-v0) model.

One of the things that the `GIST` family of models fell short on is the performance on retrieval tasks. We propose a method that produces improved retrieval performance while maintaining independence on crafting arbitrary instructions, a trending paradigm in embedding models for retrieval tasks, when encoding a query.

Technical details of the model will be published shortly.

# Usage

```Python
from typing import Union
import torch
import torch.nn.functional as F
from transformers import AutoModel, AutoTokenizer

model = AutoModel.from_pretrained("avsolatorio/NoInstruct-small-Embedding-v0")
tokenizer = AutoTokenizer.from_pretrained("avsolatorio/NoInstruct-small-Embedding-v0")


def get_embedding(text: Union[str, list[str]], mode: str = "sentence"):
    model.eval()

    assert mode in ("query", "sentence"), f"mode={mode} was passed but only `query` and `sentence` are the supported modes."

    if isinstance(text, str):
        text = [text]

    inp = tokenizer(text, return_tensors="pt", padding=True, truncation=True)

    with torch.no_grad():
        output = model(**inp)

    # The model is optimized to use the mean pooling for queries,
    # while the sentence / document embedding uses the [CLS] representation.

    if mode == "query":
        vectors = output.last_hidden_state * inp["attention_mask"].unsqueeze(2)
        vectors = vectors.sum(dim=1) / inp["attention_mask"].sum(dim=-1).view(-1, 1)
    else:
        vectors = output.last_hidden_state[:, 0, :]

    return vectors


texts = [
    "Illustration of the REaLTabFormer model. The left block shows the non-relational tabular data model using GPT-2 with a causal LM head. In contrast, the right block shows how a relational dataset's child table is modeled using a sequence-to-sequence (Seq2Seq) model. The Seq2Seq model uses the observations in the parent table to condition the generation of the observations in the child table. The trained GPT-2 model on the parent table, with weights frozen, is also used as the encoder in the Seq2Seq model.",
    "Predicting human mobility holds significant practical value, with applications ranging from enhancing disaster risk planning to simulating epidemic spread. In this paper, we present the GeoFormer, a decoder-only transformer model adapted from the GPT architecture to forecast human mobility.",
    "As the economies of Southeast Asia continue adopting digital technologies, policy makers increasingly ask how to prepare the workforce for emerging labor demands. However, little is known about the skills that workers need to adapt to these changes"
]

# Compute embeddings
embeddings = get_embedding(texts, mode="sentence")

# Compute cosine-similarity for each pair of sentences
scores = F.cosine_similarity(embeddings.unsqueeze(1), embeddings.unsqueeze(0), dim=-1)
print(scores.cpu().numpy())

# Test the retrieval performance.
query = get_embedding("Which sentence talks about concept on jobs?", mode="query")

scores = F.cosine_similarity(query, embeddings, dim=-1)
print(scores.cpu().numpy())
```

Support for the Sentence Transformers library will follow soon.
