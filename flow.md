# Model flow

data_utils.py
        |
        |
        |————> convert_examples_to_features
                    |
                    |————> 1. 使用bert对处理过的分词结果再次进行分词