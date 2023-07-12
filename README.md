# For demo

fly -t ci destroy-pipeline --pipeline use-common-pipeline
fly -t ci set-pipeline --pipeline use-common-pipeline --config $LANGUAGE/ci/pipeline.yml
