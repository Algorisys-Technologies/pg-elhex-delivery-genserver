# ElhexDelivery

# To start :- 
iex -S mix

# To get latitude and longitude from zip code:- 
ElhexDelivery.PostalCode.Store.get_geolocation("94062")

# To find the difference between to zip code:- 
ElhexDelivery.PostalCode.Navigator.get_distance(94062, 94104)
# pg-elhex-delivery-genserver
