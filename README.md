# angular-tour-of-heroes
Angular sample project to play around with

#1) The Hero Editor https://angular.io/tutorial/toh-pt1

npm install -g @angular/cli
ng new angular-tour-of-heroes
cd angular-tour-of-heroes
ng serve --open

#Add a Component
ng generate component heroes

#2) Display a List - https://angular.io/tutorial/toh-pt2

#3) Create a feature component - https://angular.io/tutorial/toh-pt3

#4) Add services - https://angular.io/tutorial/toh-pt4
#Add a Service
ng generate service hero
ng generate component messages
ng generate service message

#5) Add in-app navigation with routing - https://angular.io/tutorial/toh-pt5
#Adding Routing
ng generate module app-routing --flat --module=app
	--flat puts the file in src/app instead of its own folder.
	--module=app tells the CLI to register it in the imports array of the AppModule.

#Add a Dashboard view
ng generate component dashboard

#Navigating to hero details.

#Routable HeroDetailComponent

#6) Get data from a server -  https://angular.io/tutorial/toh-pt6
#Heroes and HTTP
npm install angular-in-memory-web-api --save 
ng generate service InMemoryData

#Update heroes

#Add a new hero

#Delete a hero

#Search by name
ng generate component hero-search