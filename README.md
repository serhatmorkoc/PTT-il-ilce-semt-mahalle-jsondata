# PTT-il-ilce-semt-mahalle-jsondata

Son güncel PTT verisi 16.11.2021

<a name="dataModel"></a>
## Data Model

<a name="dataModelCity"></a>
### İl (City)
| Alan | Tip | Açıklama |
| ------ | ------ | ------ |
| id | int | Şehir id|
| name | string | Şehir ismi |


<a name="dataModelTown"></a>
### İlçe (Town)
| Alan | Tip | Açıklama |
| ------ | ------ | ------ |
| id | int | İlçe id|
| name | string | İlçe ismi |
| cityid | int | Şehir id |


<a name="dataModelDistrict"></a>
### Semt (District)
| Alan | Tip | Açıklama |
| ------ | ------ | ------ |
| id | int | Semt id|
| name | string | Semt ismi |
| cityid | int | İl id |
| townid | int | İlçe id |

<a name="dataModelNeighborhood"></a>
### Mahalle (Neighborhood)
| Alan | Tip | Açıklama |
| ------ | ------ | ------ |
| id | int | Mahalle id|
| name | string | Mahalle ismi |
| cityid | int | İl id |
| townid | int | İlçe id |
| districtid | int | Semt id |

