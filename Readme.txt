1. Firstly, install all the required packages like rougue-score, rouge-metric, nltk, boto3, networkx, sklearn, bs4, pandas, s3fs, boto3 --upgrade,
 rouge --upgrade, requests, networkx --upgrade, --upgrade sciy , --upgrade networkx, genism, rougue_score and upgrade few of them

2. We have the two different .ipynb files
   i. PageRankAlgo.ipynb
   ii. LSA_TS.ipynb

3. Dataset link - https://www.tensorflow.org/datasets/catalog/cnn_dailymail

4. Import the first file(PageRankAlgo.ipynb) into databricks, start the cluster and run all the cells. It generates the ROUGE values and summaries for all the stories

5. Import the second file(LSA_TS.ipynb) into databricks, start the cluster and run all the cells. It generates the ROUGE values and summaries for all the stories.

6. The published link for PageRankAlgo - https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/1238976419172215/2221581848295054/5114953453089264/latest.html

7. The published link for LSA_TS - https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/3441969184380383/205666822500436/4638214704103479/latest.html

8. The input files are accessed from the following AWS s3 buckets which contain the following files mentioned in (8) in .txt and. story format
   i. s3://vinnubigdata/Project/story/
   ii. s3://6350-big-data/Project/cnn/
   iii.  0a57c604f972b4b190cf02819ef1b50d0886d88a.txt', '0ac7adff1e1da0757f8ae1825872b0ac51236928.txt', '0ad6e0e18918f8ea0c33ac3f4b07f791bfc5929b.txt', '0b8afba5b0e6d9ac633a58ef4b6cb830e3fcd85c.txt',
 '0ba73570295a5ca2951079aed5e1dc5fe7e58b21.txt', '0bc55c4e3c651628ad0e409a8b7c15139a917e3e.txt', '0c0a6a6459a9fda3a5fdd3bfb15e26afb206d3f1.txt', '0c15f4bb435ecef83ae88a19ba9e3a4bff98ce28.txt', 
'0c3378f7968d8c3b2309485806a9cc6a0035837d.txt', '0d70bf0e7219e1bae4a6fe178c16b6628349c54d.txt', '0e0bdf77a264313fa9c706e2a02ce33b42e6494d.txt', '0f0c1a6393cdc7b73a305d5c8486e0276a14d10a.txt', 
'0f403e5cb77aca20188e3d437e4f2d8566afe4a1.txt', '10547416183a0b7ade862789ca2445b00164efea.txt', '1a04fa5c48398379b500e1336c81decb2e9f82e1.txt', '1afd2df29d4e642f20130a231d27004216667fe1.txt', 
'1b1e38e9bf01b9030121bbcce049c15fb0673cb9.txt', '1b3bdc7fa131c4c82e8e996c936abe0da840e2ef.txt', '4d37e8e54986543598ced33dd2ebb1907e14f163.txt', '610c78a5a3d8ac17caa24646332e7cf938fae805.txt',
 '697d9ab27a5b76589bc93f1be2ca76a1605b21ef.txt', '9e107710387431c83cd2bc12f8fde0001617e3d1.txt', 'b787f83c7d6458e1574b3a2589759a6d60428da4.txt', 'd0ffe27ec1d04b350e41a69a60de2e98fa0c8e77.txt', 
'd9d7836b2bf65d6c3d2643fe9694a2234cb19281.txt'