# DALLE-using-OpenAI-API

Generating images using the most famous model, DALL.E, by integrating OpenAI API.

## **Instructions:**

1- Sign up for [OpenAI](https://auth0.openai.com/u/signup/identifier?state=hKFo2SBvSy02UTZIXzJqSm1OREl2UnY5OTljc1haMl9mb21GdKFur3VuaXZlcnNhbC1sb2dpbqN0aWTZIFVyU1BZaDJhOGR0NUlSdU5PSENPOHJpcHVOWU5BRXFpo2NpZNkgRFJpdnNubTJNdTQyVDNLT3BxZHR3QjNOWXZpSFl6d0Q)

2- Generate your secret API-key using the api-key generator in this [link](https://beta.openai.com/account/api-keys)

3- Refer to this [Notebook](https://github.com/OmarAlkousa/DALLE-using-OpenAI-API/blob/d60296d9ffee198830fc3992143900d42f3ec322/OpenAI_API_DALLE.ipynb) and paste your secret API-key into **my_api_key** variable.

4- You're ready to generate images using texts:)

The image below was an example when:
```sh
openai.Image.create(prompt = "Biomedical Engineer works with the medical imaging system",
                    n = 4,
                    size = "1024x1024"
                    )
```

<p align="center">
  <img src="https://github.com/OmarAlkousa/DALLE-using-OpenAI-API/blob/d60296d9ffee198830fc3992143900d42f3ec322/Example/Medical%20Engineer%20by%20Dalle.png", width="600">
</p>

## Acknowledgment:
- OpenAI API Documentation, Libraries, [Python Bindings](https://beta.openai.com/docs/libraries/python-bindings) [Accessed at 11-Jan-2023]
- OpenAI API Documentation, Guides, [Image Generation](https://beta.openai.com/docs/guides/images/introduction) [Accessed at 11-Jan-2023]
- OpenAI API Documentation, API Reference, [Authentication](https://beta.openai.com/docs/api-reference/authentication) [Accessed at 11-Jan-2023]
- OpenAI API Repository, [OpenAI Python](https://github.com/openai/openai-python.git) [Accessed at 11-Jan-2023]
