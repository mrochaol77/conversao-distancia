# conversao-distancia

# Construir a imagem
#   docker build -t mrochaol/conversao-distancia:v1 -f Dockerfile .

# Executar o container a partir da imagem
#   docker container run -d -p 8181:5000 conversao-distancia

# Padrão de nomenclatura:
#   namespace/repo-name:version
#   mrochaol/conversao-distancia:v1
#   mrochaol/conversao-distancia:latest

# Conectar no docker hub
#  docker login

# Subir imagem corrente
#  docker push mrochaol/conversao-distancia:v1

# Subir imagem lastest
#  docker tag mrochaol/conversao-distancia:v1 mrochaol/conversao-distancia:latest

# Seguindo boas praticas e tagueando como ultima versao (latest)
#  docker push mrochaol/conversao-distancia:latest