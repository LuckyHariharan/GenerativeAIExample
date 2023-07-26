# Generative AI Example #

How to use Google Generatve AI using Palm API in Android App using Jetpack Compose. 


# How to Run this project #

1. Currently generative ai sdk is not published to maven central, So we will have to use it locally
2. Download generative ai sdk from [here](https://storage.googleapis.com/generativeai-downloads/clients/google-cloud-ai-generativelanguage-v1beta2-java.tar.gz)
3. Extract the files:
`   tar -xzvf google-cloud-ai-generativelanguage-v1beta2-java.tar.gz
   cd google-cloud-ai-generativelanguage-v1beta2-java`
4. install them in mavenLocal: `./gradlew publishToMavenLocal`
5. Get An API KEY for PALM API from [here](https://makersuite.google.com/app/apikey)
6. Set the env variable with key: PALM_API_KEY and set that PALM API KEY as value for this env variable
7. And its done, you can build now and run the app

