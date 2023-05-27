# Splunk Dashboard Studio WireframeGenerator

Splunk Dashboard Studio helper using chatgpt. There is the ocasional time where is necesary to quickly generate a dashboard wireframe to be filled with the required information and format. By "feeding" chatgpt a basic JSON schema it will be able to generate on top of that as per users request. 


## Requirements. 

1. Get your API key [openai](https://platform.openai.com/docs/api-reference)

2. Check the Splunk Dashboard Studio Documentation for the JSON schema [here](https://docs.splunk.com/Documentation/SplunkCloud/9.0.2303/DashStudio/dashDef).

3. You may want you to request a test/dev license from Splunk in order to test this.

4. Python Libraries:

| Package | 
| -------------- | 
| json |  |
| argparse | 
| openai | 
| os | 

Openai python library: https://github.com/openai/openai-python

## How to setup? 

### 1. Set your API key as a env variable this will vary on your OS:


#### Linux / MacOS 

1.1 Type the following command to set the env variable `OPENAI_API_KEY`.

```bash 
export OPENAI_API_KEY="your-API-key-here"
```

To make this change persistent, add the command to your shell's config either `~/.bash_profile` or `~/.zshrc`. 


### 2. Run the `dashai_setup.sh`

``` bash 
./dashai_setup.sh
```


## Examples: 


