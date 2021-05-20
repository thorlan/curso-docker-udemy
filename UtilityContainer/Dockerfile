FROM node:14-alpine

#docker run pega esse dir como raiz!
WORKDIR /app  

#faz um bind mount para os comandos la de dentro serem refletidos fora
#docker run -it node-util -v ${pwd}:/app  npm init

#append os comandos usados apos o docker run
#docker run -it node-util -v ${pwd}:/app install expres --save   
#(tirei o npm do inicio! vai instalar o express)
ENTRYPOINT ["npm"] 

# é substituido pelos comandos usados no docker run
#CMD [""]