make client
npx create-react-app ./

make server
npm init -y
npm i express graphql express-graphql cors nodemon
npm run dev

http://localhost:5000/graphql
query{
  getAllUsers {
    id, username, age
  }
}