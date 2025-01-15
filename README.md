# conversao-distancia

Construir a imagem
  docker build -t conversao-distancia -f Dockerfile .

Executar o container a partir da imagem
  docker container run -d -p 8181:5000 conversao-distancia

Padrão de nomenclatura:
  namespace/repo-name:version
  mrochaol77/conversao-distancia:v1
  mrochaol77/conversao-distancia:latest

