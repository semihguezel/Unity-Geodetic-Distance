# Unity-Geodetic-Distance
This package includes distance measurement methods such as Vincenty, Haversine and Euclidean. Necessary conversions can be made in "GeoManager" script. For Vicenty algorithm WGS84 model parameters is default. You can add your regions reference ellipsoid model in "Content" script for acquiring better accuracy. For distances up to 3 km you can use Euclidean distance, above 3 km use Vincenty Algorithm for better accuracy.</br>

Bearing angle between two gepgraphical coordinates can be calculated using "bearing" function. You can also calculate geographical coordinates of the desired location by destination function. This package also includes conversion to geographic coordinates(lat, lon, alt) to ECEF(Cartesian) system.</br>


For calculating distance between two geographic coordinates, initiliaze your position in the "GeoManager" script. From Prefab folder hold and drag GeodeticDistanceCalculator object to the sample scene, after that you can enter the second location's geographical coordinates.
In the test folder you can test some function we wrote for comparising accruacy between distance calculation methods.


