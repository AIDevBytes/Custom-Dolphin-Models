# Custom Dolphin Llama 3 and Dolphin Mixtral Model Files

This repo is a companion to the YouTube video titled: <a href="https://youtu.be/oMqiDTvYKFM">Create your own CUSTOM Dolphin Llama 3 and Dolphin Mixtral models using Ollama</a>. You can find the custom model file named "custom-mixtral" to use as a starting pointing for creating your own custom Mixtral 8x7b model to be run with Ollama.

[Dolphin Mixtral](https://ollama.com/library/dolphin-mixtral)

[Dolphin Llama 3](https://ollama.com/library/dolphin-llama3)

[Ollama Model File docs](https://github.com/ollama/ollama/blob/main/docs/modelfile.md)  

### Ollama Commands

#### Start Ollama Server
```
ollama serve
```

#### Run Ollama Model
```
ollama run <model_name>
```

```
ollama run dolphin-llama3
ollama run dolphin-mixtral
```

#### Download Ollama Model
```
ollama pull <model_name>
```

```
ollama pull dolphin-llama3
ollama pull dolphin-mixtral
```

#### List Installed Ollama Models
```
ollama list
```

#### Delete Installed Ollama Models
```
ollama rm <model_name>
```

```
ollama rm dolphin-llama3
ollama rm dolphin-mixtral
```


