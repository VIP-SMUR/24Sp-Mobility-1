### Calculating Commercial Density Index

#### Description

For this index, we gather the count of the different types of amenities in each block group. We then normalize the value by dividing each count by the greatest value for commerical density index within the region.

#### Parameters
- **atl_bg.geojson**: The data we are reading. This contains specific information about the neighborhood within Atlanta that we are researching. We will use OSMNx to calculate the quantity of each type of amenity.

#### Amenities & Tags Used
- **Groceries**: 'supermarket', 'convenience', 'grocery', 'food', 'organic'
- **Restaurants**: 'restaurant', 'cafe', 'food_court', 'bistro', 'fast_food'
- **Banks**: ''bank', 'atm'
- **Schools**: 'school', 'college', 'university', 'kindergarten', 'music_school', 'language_school', 'driving_school'
- **Entertainment**:'cinema', 'theatre', 'nightclub', 'casino', 'arts_centre', 'sports_centre', 'stadium', 'amusement_arcade', 'dance', 'bowling_alley', 'attraction', 'theme_park', 'zoo'
- **Parks**: 'recreation_ground', 'grass', 'greenfield'

#### Returns
Value for the commerical density Index, normalized by the maximum commerical density within the area.

