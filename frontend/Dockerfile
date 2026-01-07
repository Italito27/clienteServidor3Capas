# Dockerfile para Frontend - Tier 1: Presentación
FROM node:18-alpine

WORKDIR /app

# Copiar package files
COPY package*.json ./

# Instalar dependencias
RUN npm install

# Copiar código de la aplicación
COPY . .

# Exponer puerto
EXPOSE 3001

# Comando por defecto
CMD ["npm", "start"]



