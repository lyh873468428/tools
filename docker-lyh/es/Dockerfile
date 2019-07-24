
FROM elasticsearch:6.7.2

#RUN useradd elasticsearch #es已经创建了
#RUN chown -R elasticsearch:elasticsearch /usr/share/elasticsearch
#RUN chmod -R 777 /usr/share/elasticsearch/data
COPY ./config/elasticsearch.yml /usr/share/elasticsearch/config/elasticsearch.yml

EXPOSE 9200