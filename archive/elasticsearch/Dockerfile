FROM docker.elastic.co/elasticsearch/elasticsearch:6.7.2

RUN mkdir -p /usr/share/elasticsearch/config/hunspell/he_IL

RUN wget -O /usr/share/elasticsearch/config/hunspell/he_IL/he_IL.aff https://raw.githubusercontent.com/elastic/hunspell/master/dicts/he_IL/he_IL.aff
RUN wget -O /usr/share/elasticsearch/config/hunspell/he_IL/he_IL.dic https://raw.githubusercontent.com/elastic/hunspell/master/dicts/he_IL/he_IL.dic
RUN wget -O /usr/share/elasticsearch/config/hunspell/he_IL/settings.yml https://raw.githubusercontent.com/elastic/hunspell/master/dicts/he_IL/settings.yml


