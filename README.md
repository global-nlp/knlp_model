# knlp_model

本项目作为knlp的姊妹项目，保存knlp的model中的完全数据。在运行knlp中依赖到本项目中的数据时，将会自动从本项目中下载数据，并解压缩到knlp/model目录下。
数据都来自于网络开源数据，感谢各位开源。

## 数据罗列

─model
    ├─crf
    │	crf.pkl
    │	hanzi_segment.pkl
    │	NER.pkl
    │	pinyin.pkl
    │	pinyin_segment.pkl
    │      
    └─hmm
        ├─pinyin_input_data
        │	emission_pro.json
        │	pinyin_hanzi.json
        │	start_state.json
        │	transition_pro.json
        │      
        └─seg
			emission_pro.json
            init_state_set.json
            state_set.json
            transition_pro.json