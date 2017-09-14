######################################################################################
# Dockerfile[ubuntu]
#
######################################################################################
# コンテナ作成元イメージ
FROM ubuntu:16.04

# コンテナ設定
RUN apt-get update \
 && apt-get install -y language-pack-ja-base \
                       language-pack-ja \
                       ibus-mozc \
                       man \
                       manpages-ja \
                       wget \
                       sudo \
                       vim \
                       tar \
                       rsync \
                       supervisor \
 && apt-get clean \
 && update-locale LANG=ja_JP.UTF-8 LANGUAGE=ja_JP:ja

# プロセス開始
CMD ["tail", "-f", "/dev/null"]
