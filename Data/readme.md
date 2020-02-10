# Available data in .csv format.

**Associative Table**
- *Key1 PersonID* : unique ID per virtual people (int)
- *Key2 DateID* : unique ID per day (int)
- Visit Duration : number of hours that visitors were seen in the area of interest *('Duration 2h', 'Duration 3h', 'Duration 4h', 'Duration 5h', 'Duration 6h', 'Duration 7h', 'Duration 8h', 'Duration 9h', 'Duration 10h', 'Duration 10h-18h')* **(str)**

**Personal Info Table**
- PersonID : unique ID per virtual people **(int)**
- Name: fake name **(str)**
- Gender : the gender *(masculine, feminine)* **(str)**
- Age : age range *(less than 18, 18-24, 25-34, 35-44, 45-54, 55-64, more than 65)* **(str)**
- geoLife : socio-category profile *('NR', 'comfortable family pavilion','growing peri-urban', 'popular', 'secondary residence', 'dynamic rural', 'rural worker', 'traditional rural', 'middle-class urban', 'low-income urban', 'dynamic urban', 'comfortable family urban')** **(str)**
- Visitor category : resident, French or foreign tourist **(str)**
- Region : the region or country the visitor is from **(str)**
- Sleeping area : the area which the visitor slept the previous night **(str)**

**Dates = {(1: 2017-05-31), (2: 2017-06-01), (3: 2017-06-03), (4: 2017-06-04), (5: 2017-06-05), (7: 2017-06-06)}**
