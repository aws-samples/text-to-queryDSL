# Text-To-Query DSL with Synthetic Data Leveraging Claude3 Models

This repository provides guideance on prompting techniques for text-to-DSL query generation (the query language used for Elasticserach and Opensearch) as well as synthetic data to improve development efficiency. OpenSearch provides a search language called query domain-specific language (DSL) that you can use to search your data and this notebook will walk through how to use LLMs to create the queries based on natural language.

## Deployment

1. Open text2ES_prompting_guide.ipynb file where the code resides.
2. Use kernel either conda_python3, conda_pytorch_p310 or conda_tensorflow2_p310.
3. Install the required packages.
4. Access to the Claude3 models on Amazon Bedrock and access to the Converse API.
5. The code will generate synthetic data based on provided schemas as well as the prompt for text-to-queryDSL.


## Contributing

We welcome community contributions! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the [LICENSE](LICENSE) file.
