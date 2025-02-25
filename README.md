# 4Goods

It is a communication app for non-profits and donors. It brings different non-profit organizations and donors together. It is a common issue that donations are not efficiently distributed and used. On 4Goods, any non-profit can easily create posts for surplus donations or items that are needed. By sharing surplus donations, non-profits can efficiently share and distribute their resources while limiting or preventing food waste. Donation Hub can also help donors find whatto donate and match them with organizations in need. I hope you will enjoy Donation Hub and find it useful. Happy sharing and happy donating!
It is a full-stack project.Therefore, both the node modules in the server folder and client folder need to be installed before running the app. environment variables are not uploaded to github but a sample .env file is present.

## Tech Stack
1. Frontend: React.js, Sass, Helmet, Rest APIs
2. Backend: Node.js, Express.js, JTW Token
3. Storage: MongoDB, Cloudinary

## Screenshots

![App Screenshot](https://happyaviationenglish.sfo3.digitaloceanspaces.com/4goods.png)


## Demo
watch the video demo 
https://happyaviationenglish.sfo3.digitaloceanspaces.com/4Goods%20-%207%20February%202022.mp4


## Team Members

[Huanyu Wang](https://github.com/hnslyswhy):
I worked on the backend, connecting backend with database MongoDB, and the signup, login and logout components in the frontend. It's a great learning opportunity for me to learn about how to use JTW for auth and cooperate with my team to get the backend and database setup properly.
After the hackathon, I added goods pages and managing donation items function to make imporve the functionality of the application. 


[Miriam Nakiyingi](https://github.com/miriamnaki): 
I worked on front end setup and the profile page that needed to use JWT tokens for authentication, multiple API calls to the back end to display data. I enjoyed working on the team and learned more about mongoDB and jwt tokens.

[Carol Deweger](https://github.com/CDeweger) : 
I worked on the front-end using React.js, set up the image upload function with Cloudinary, I also did the initial research, collecting data. And I use Sass for stylings. I am passionate about poverty alleviation. I want to use my programming skill to make a positive impact in my community.

[Phoebe Chang](https://github.com/phoebe03111) : 
I worked on designing, making prototype, mostly focused on front-end side of the project. I also incorporated Google Maps API to display a map on the website.



## Installation

1. Clone this repo
2. Setup frontend
```bash
  cd client
  npm i
  npm start
```
3. Setup backend
```bash
  cd server
  npm i
  npm start
```

## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`MONGODB_URL`

`REACT_APP_MAP_API_KEY`
