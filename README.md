# api
# Pour effectuer une requête GET vers l'API de Nomad Immobilier, vous pouvez utiliser la commande suivante dans votre terminal :
```bash
curl -X GET 
'http://api.nomad.immo/properties?min_price=1000&max_price=5000'
```
2- Pour envoyer une requête POST avec les données d'un immobilier, vous 
pouvez utiliser la commande suivante :
```bash
curl -X POST -H "Content-Type: application/json" -d '{"title": "Mon 
immobilier", "description": "Ma description", "price": 1000, "surface": 
50}' http://api.nomad.immo/properties
```
3- Vous pouvez également utiliser des bibliothèques comme `requests` pour 
envoyer ces requêtes :
```python
import requests

response = 
requests.get('http://api.nomad.immo/properties?min_price=1000&max_price=500requests.get('http://api.nomad.immo/properties?min_price=1000&ma_price=5000000')
```
