# keigokun
#API品詞取得
from janome.tokenizer import Tokenizer
import pickle

#インスタンスを生成
t = Tokenizer()
t

#textの形態素解析を実行
text = '東京にお越しになったのですね。'
tokens = t.tokenize(text)
len(tokens)

#トークンの繰り返しの処理
for token in tokens:
    print(token)

#分かち書きを実行
t.tokenize(text, wakati=True)

#オブジェクトの直列化(bytesオブジェクト化)
data = {'name': 'short'}
pickled = pickle.dumps(data)
pickled

#bytesオブジェクトを元に戻す
data2 = pickle.loads(pickled)
data2
