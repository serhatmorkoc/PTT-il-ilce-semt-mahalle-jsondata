# PTT-il-ilce-semt-mahalle-jsondata

Son güncel PTT verisi 16.11.2021

<a name="dataModel"></a>
## Data Model

<a name="dataModelCity"></a>
### İl (City)
| Alan | Tip | Açıklama |
| ------ | ------ | ------ |
| id | string | Şehir id|
| name | string | Şehir ismi |


<a name="dataModelTown"></a>
### İlçe (Town)
| Alan | Tip | Açıklama |
| ------ | ------ | ------ |
| id | string | İlçe id|
| name | string | İlçe ismi |
| cityid | string | Şehir id |


<a name="dataModelDistrict"></a>
### Semt (District)
| Alan | Tip | Açıklama |
| ------ | ------ | ------ |
| id | string | Semt id|
| name | string | Semt ismi |
| cityid | string | İl id |
| townid | string | İlçe id |

<a name="dataModelNeighborhood"></a>
### Mahalle (Neighborhood)
| Alan | Tip | Açıklama |
| ------ | ------ | ------ |
| id | string | Mahalle id|
| name | string | Mahalle ismi |
| cityid | string | İl id |
| townid | string | İlçe id |
| districtid | string | Semt id |

