# README

Techpays repository for configuring and deploying Elasticsearch on Render for Techpays.

* It uses [Render Disks](https://render.com/docs/disks) for persistent index storage.

* Elasticsearch runs in your [a private network](https://render.com/docs/private-services) so it isn't exposed to the public Internet.

* [Elasticsearch configuration](https://www.elastic.co/guide/en/elasticsearch/reference/current/settings.html) using `config/elasticsearch.yml` is done using the config/elasticsearch.yml file. Render will automatically redeploy Elasticsearch when you push your changes.

## Deployment

[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy)

For details and customization see https://render.com/docs/deploy-elasticsearch.
