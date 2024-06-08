# Getting Started with Create React App


## Available Scripts
nj
In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

###AWS configuartions 

### s3 bucket 

S3 bucket hosting 

https://www.youtube.com/watch?v=SHN48wTEQ5I&ab_channel=DevGuyAhnaf
used these instructions 

http://moviereviews-clone-app.s3-website-us-east-1.amazonaws.com


### EC2
https://www.youtube.com/watch?v=oaK223BiTBU&ab_channel=AlirazaKhan
used these instructions

### RDS
CREATE TABLE movies (
    id INT PRIMARY KEY,
    poster_path VARCHAR(255),
    original_title VARCHAR(255),
    release_date DATE,
    vote_average DECIMAL(3, 1),
    overview TEXT
);

INSERT INTO movies (id, poster_path, original_title, release_date, vote_average, overview) 
VALUES 
(1, '/path/to/poster1.jpg', 'Movie Title 1', '2023-06-01', 8.5, 'This is the overview for movie 1.'),
(2, '/path/to/poster2.jpg', 'Movie Title 2', '2023-07-15', 7.2, 'This is the overview for movie 2.'),
(3, '/path/to/poster3.jpg', 'Movie Title 3', '2023-08-10', 9.0, 'This is the overview for movie 3.');

select * FROM movies;

instruction from: https://www.youtube.com/watch?v=wOZ1hYw5Arw&ab_channel=chrismello

### VCP

instructions from: https://www.youtube.com/watch?v=ApGz8tpNLgo&ab_channel=BeABetterDev

