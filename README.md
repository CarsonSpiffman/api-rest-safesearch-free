# api-rest-safesearch-free
API REST SafeSearch Google Cloud Free

##### Just make a POST request with the imageURL parameter and a URL of a photo you want to analyze to http://ai.safesearch-sadge-1.repl.co/api/v1/safesearch
![Captura2](https://user-images.githubusercontent.com/99296245/166129718-5807e586-9cf8-4e66-864a-87498ea451a2.PNG)

##### Response example
```json
{
    "adult": "VERY_UNLIKELY",
    "spoof": "UNLIKELY",
    "medical": "VERY_UNLIKELY",
    "violence": "VERY_UNLIKELY",
    "racy": "VERY_UNLIKELY",
    "adultConfidence": 0,
    "spoofConfidence": 0,
    "medicalConfidence": 0,
    "violenceConfidence": 0,
    "racyConfidence": 0,
    "nsfwConfidence": 0,
    "imageURL": "https://upload.wikimedia.org/wikipedia/commons/4/44/Cat_img.jpg"
}
```
