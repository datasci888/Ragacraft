
# RagaCraft: Raga Music Generation Pipeline
![RagaCraft](https://github.com/BharatKatyal/Audio_Craft_Hackathon_Raga_Maker_FrontEnd/assets/119770980/66fb8154-50fe-49c7-85c3-f019e4fc3687)

RagaCraft bridges the gap between raw human emotion and the timeless art of raga music using cutting-edge AI. Here's a deeper dive into the underlying process:

Customer Interaction: Users interact with our platform, sharing their current emotions and contextual information. For example, "I am feeling romantic today. It is Valentine's Day. I'd like a song to suit the mood."

JavaScript Selection: Our system, powered by JavaScript, scans the user's input to select an appropriate raga that resonates with the given emotion.

OpenAI Integration: To add depth and specificity, RagaCraft sends a refined request to OpenAI: "Generate a text-to-music prompt for a single romantic raga. Include parameters such as tempo, scale, pitch, and rhythm to optimize the romantic mood. Define ideal values for these features."

OpenAI's Response: The API, enriched with musical knowledge, replies with precise musical direction. For instance, "For a romantic setting, employ the Hindustani raga Kamboji. Utilize a medium-slow tempo, major scale, and a high pitch with low undertones. The rhythm should be gentle with a 4/4 signature. Dynamics can vary, with crescendos and decrescendos, ensuring a light texture and smooth timbre."

Audiogen Transformation: The detailed prompt from OpenAI is fed into Audiogen, which processes it and crafts a song that encapsulates the user's emotions.

Delivering the Experience: Our user interface then presents the generated raga song to the user, completing a journey from raw emotion to personalized musical expression. Through RagaCraft, we're redefining the way users experience and interact with traditional music forms in the age of AI.

<img width="1093" alt="Screen Shot 2023-08-31 at 2 23 45 PM" src="https://github.com/BharatKatyal/Audio_Craft_Hackathon_Raga_Maker_FrontEnd/assets/119770980/361f3213-1bd7-4ff7-9c57-6c1a31fe85d0">


# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

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

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
