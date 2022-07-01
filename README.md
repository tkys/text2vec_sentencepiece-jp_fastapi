# text2vec_sentencepiece-jp_fastapi



## About
Sentencepieceで分かち書きされた日本語学習済みのベクトル sentencepieceを fastapiでREST API化したもの

## How to use


### With docker

docker pull tkysyskw/vec_jp:latest

docker run -it --name sentencepiece-vecjp -p 80:80  tkysyskw/vec_jp:latest


### Get Vector (768 dimmension)

access on browser  http://0.0.0.0:80/vector/ベクトル取得したいテキスト

or

curl -X 'GET'   'http://0.0.0.0:80/vector/\\u8a00\\u8449'   -H 'accept: application/json'


git clone text2vec_sentencepiece-jp_fastapi.git
......
