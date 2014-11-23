rails-3
=======

The life of a request


Routes
---

| http verb 	|       path       	| controller#action 	| used for                                     	|
|-----------	|:----------------:	|-------------------	|----------------------------------------------	|
| GET       	| /photos          	| photos#index      	| display a list of all photos                 	|
| GET       	| /photos/new      	| photos#new        	| return an HTML form for creating a new photo 	|
| POST      	| /photos          	| photos#create     	| create a new photo                           	|
| GET       	| /photos/:id      	| photos#show       	| display a specific photo                     	|
| GET       	| /photos/:id/edit 	| photos#edit       	| return an HTML form for editing a photo      	|
| PATCH/PUT 	| /photos/:id      	| photos#update     	| update a specific photo                      	|
| DELETE    	| /photos/:id      	| photos#destroy    	|                                              	|
