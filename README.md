# Bio-OS TES

The Task Execution Service (TES) API is a standardized schema and API for describing and executing batch execution tasks. A task defines a set of nput files, a set of containers and commands to run, a set of output files and some other logging and metadata.

Based on the TES standard defined by GA4GH, Guangzhou Lab and Volcano Engine have implemented the TES standard using the cloud-native container service engine This implementation includes the extension of the TesTask tags, enabling the declaration and utilization of GPU resources. Additionally, the project incorporates task priority statements and supports metering and billing within the Bio-OS framework.

Serving as the backend computing service for the Miracle Cloud project, this TES implementation has undergone extensive testing to ensure its functionality and reliability.


See the human-readable and the [OpenAPI YAML description](openapi/bioos-tes.yaml). You can also explore the specification in the [Swagger Editor](https://editor.swagger.io/?url=https://LLZ-Group.github.io/bioos-tes/openapi/bioos-tes.yaml).