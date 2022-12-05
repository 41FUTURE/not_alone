Rails app generated with [lewagon/rails-templates](https://github.com/lewagon/rails-templates), created by the [Le Wagon coding bootcamp](https://www.lewagon.com) team.

# 📚 NotAlone

A volunteer recruitment site/database developed in partnership with OpSAFE, an NPO that hosts camps for kids that have suffered from traumatic experiences. Not Alone allows camp organizers setting up a new camp page to immediately contact existing volunteers in the location of the new camp for recruitment.


App home: https://not-alone.online
 <img width="1248" alt="2022-12-05" src="https://user-images.githubusercontent.com/99112509/205581556-2e1ddc1d-450e-4076-ae6a-96c93487fed7.png">
 <img width="1248" alt="2022-12-05 (5)" src="https://user-images.githubusercontent.com/99112509/205581503-1c4010c1-d0fd-49df-a62a-c8a39218f517.png">
<img width="1248" alt="2022-12-05 (8)" src="https://user-images.githubusercontent.com/99112509/205581515-206efea5-19a9-47d2-a5ac-4a6320db5a99.png">
<img width="1248" alt="2022-12-05 (11)" src="https://user-images.githubusercontent.com/99112509/205581520-e74b04cd-0366-4410-8906-1796e4ec1789.png">
<img width="1248" alt="2022-12-05 (12)" src="https://user-images.githubusercontent.com/99112509/205581527-739abbe8-6139-480c-8192-a508069ab62c.png">
<img width="1248" alt="2022-12-05 (14)" src="https://user-images.githubusercontent.com/99112509/205581548-60481f8b-c337-4524-8553-4db916251720.png">
<img width="1248" alt="2022-12-05 (3)" src="https://user-images.githubusercontent.com/99112509/205581600-039bd16e-42d8-4585-9500-ecf240b72234.png">

## Getting Started
### Setup

Install gems
```
bundle install
```
Install JS packages
```
yarn install
```

### ENV Variables
Create `.env` file
```
touch .env
```
Inside `.env`, set these variables. For any APIs, see group Slack channel.
```
CLOUDINARY_URL=cloudinary://482279922763549:5tcC79BwTV8IXG2sBzPxMev7EtE@djnxkxxw9
MAPBOX_API_KEY=pk.eyJ1IjoiZGt3aWxzb24xOTkxIiwiYSI6ImNsYWtmbHhtZjA1Mmgzb3BqNnVvZm9tZ3EifQ.jqERiLo3qGRnI21NTc1YDA
```

### DB Setup
```
rails db:create
rails db:migrate
rails db:seed
```

### Run a server
```
rails s
```

## Built With
- [Rails 7](https://guides.rubyonrails.org/) - Backend / Front-end
- [Stimulus JS](https://stimulus.hotwired.dev/) - Front-end JS
- [Heroku](https://heroku.com/) - Deployment
- [PostgreSQL](https://www.postgresql.org/) - Database
- [Bootstrap](https://getbootstrap.com/) — Styling
- [Figma](https://www.figma.com) — Prototyping

## Acknowledgements
Inspired by the NPO, OpSAFE. We wanted to make the process of finding volunteers easier, so that the organization can focus on their priority of helping children with trauma.

Team Members

## Team Members

[Keita Wilson](https://www.linkedin.com/in/keita-wilson-1234aa142/)
[Yulia Naumenko](https://www.linkedin.com/in/yulia-naumenko-bba121119/)
[Savithri Wewala](https://www.linkedin.com/in/savithri-wewala-507308a1/)

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the MIT License
