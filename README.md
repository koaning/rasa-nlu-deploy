# rasa-nlu-deploy

You can build/run the container locally via; 

```
docker build -t koaning/rasa-spacy-example .
docker run -p 8080:8080 koaning/rasa-spacy-example
```

The container also has an entry point configured so you could
also talk to the shell if you'd like. 

```
docker run -p 8080:8080 koaning/rasa-spacy-example shell nlu
```
