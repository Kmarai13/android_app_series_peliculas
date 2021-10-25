# android_app_series_peliculas

1. mostrar la lista de peliculas en un RecyclerView
2 Guardar en BD room la persistencia de datos, y para poder hacer que la aplicacion fuera offline,
 ya que por cuestiones laborales, en este momento solo use singleton para algunos datos que se pasan entre servicios.
3. utilice arquitectura MVP
4.ahorita solamente consume los 3 primeros servicios:

https://api.themoviedb.org/4/auth/request_token
https://api.themoviedb.org/4/auth/access_token
https://api.themoviedb.org/4/account/{account_id}/lists

El consumo de servicios se puede visalizar en el log del la aplicación

