# Crear y arrancar infraestructura
Para crear y arrancar toda la infraestructura por primera vez:
```bash
docker compose up -d
```

# VirtualHost (dominios)
Recuerda añadir al archivo `hosts` los dominios del frontend y backend:
```bash
<ip_maquina_anfitrión> peliculas.iaas.com
<ip_maquina_anfitrión> peliculas.iaas.api.com
```