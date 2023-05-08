# EDA_ModelBuilding_Churnbase
The purpose of this report and the work behind it is to demonstrate and apply the skills taught by the Foundations class, as well as explore a dataset of interest to us.  
With this data science project, we explored a dataset that was timely and relevant to the world of technology. As such, we decided to use a dataset on startups. This dataset includes a broad view into many aspects of start-up life including funding information, overview of the founders of the startup and their education background, the locations of the startups, and more. Upon exploring these data sets, we became very curious about which elements lead to start-up success. For example, we desired to learn what were the characteristics of successful start-up founders. As well, we were curious about what specific characteristics, milestones, and funding brackets lead to a startup becoming ultimately successful?  

Data source  

 

Crunchbase is a leading company behind collection and aggregation of data within the startup and technology space. They offer a variety of data products that provide access to the most up-to-date information on companies, investors, investments, and funding.  

 

Through Kaggle datasets, we were able to obtain a usable export of some Crunchbase data, a snapshot from 2013. The data files available were:  

acquisitions - details the company acquired, by whom, when, and for how much 

degrees - for people in the dataset, highest degree, institution, subject, graduation date 

funding_rounds - company, date, funding round type, amount raised, currency  

funds - fund, date founded, total raised, currency 

investments - company, investor (fund, person, etc), date 

ipos - company, date, valuation, currency, amount raised, stock symbol 

milestones - object (company, person, etc), date, description, source (news link) 

objects - object (company, person, etc), name, link, category, status (operating, acquired, etc) 

offices - company, office, region, city, address, state 

people - name, birthplace, affiliation 

relationships - person, object (company, fund, etc), title (CEO, Partner, Board Member, etc), start & end date 

 

Although we spent a considerable amount of time looking for exports or other ways to obtain more recent data, those attempts were ultimately unsuccessful (detailed in a later section). Since the central business of Crunchbase is to sell their data, we believe the only reason the Kaggle dataset is readily available is because of its eight year latency. 
