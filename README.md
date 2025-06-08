![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

# oic-ai-error-handler
An AI-powered fault handler for Oracle Integration Cloud (OIC) that analyzes integration errors using a Generative AI API (ChatGPT/OpenAI/OCI GenAI) and returns human-readable troubleshooting advice.

##Features -
 - Handles REST, DB, SOAP, and FTP errors
 - Uses structured JSON payloads
 - Returns human-friendly analysis
 - Easily pluggable into existing error handler scopes

##How to Use -
 - Import .car into OIC
 - Set up OpenAI/OCI GenAI REST connection
 - Adjust base URL and prompt if needed
 - Example payloads in /test/example_payloads.csv
