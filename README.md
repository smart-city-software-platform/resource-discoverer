![Build Status](https://gitlab.com/smart-city-platform/discovery-service/badges/master/build.svg)

#Resources Catalog API
#====================

Environment Setup
-----------------

* Install RVM
* Run on terminal: ```$ rvm install 2.3.1```
* In the project directory, run:
  * ```$ gem install bundle```
  * ```$ bundle install```
  Run the tests:
  * ```$ rspec```

You should see all tests passing =)

Provides
--------
* get /discovery/resources/? capability=[capability_name] 
							& lat=[number] 
							& lon=[number] 
							& min_cap_data=[minValue] 
							& max_cap_data=[maxValue] 
							& start_date=[date] 
							& end_date=[date]

Needs
-----

* data_catalog 		GET /resources/search
* data_collector	GET /events/?resource_id=:value
								&limit=:value
								&start=:value

Useful links
============

* [Project description](https://social.stoa.usp.br/poo2016/projeto/projeto-plataforma-cidades-inteligentes) @ STOA
* [Discovery Services description](https://social.stoa.usp.br/poo2016/projeto/grupo-5-middleware-cidade-inteligente) @ STOA
* [Group Repository](https://gitlab.com/groups/smart-city-platform)
* [email list](https://groups.google.com/forum/#!forum/pci-lideres-equipe-de-organizacao-poo-ime-2016)
