# python-serverless-with-dependencies
Python serverless project with dependencies using layers

Setup instructurtion:
1. pushd layers/pandas && chmod +x get_layer_packages.sh && ./get_layer_packages.sh && popd
2. serverless package
3. serverless deploy --package .serverless
