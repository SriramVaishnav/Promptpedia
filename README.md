<a name="readme-top"></a>

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]




<br />
<div align="center">

<h3 align="center">PROMPTPEDIA</h3>

  <p align="center">
    A platform to discover, create and share useful AI prompts.
    <br />
    <a href="https://promptpedia.sriramvaishnav.com"><strong>Visit the Website »</strong></a>
    <br />
    <br />
    ·
    <a href="https://github.com/Oxlac/Promptpedia/issues">Report Bug</a>
    ·
    <a href="https://github.com/Oxlac/Promptpedia/issues">Request Feature</a>
  </p>
</div>

## About The Project

![image](https://github.com/Oxlac/Promptpedia/assets/100900868/327d9171-8bb4-4bb3-a6e4-d71a5c023d78)


Promtpedia is a community-driven platform for discovering and sharing useful and working AI prompts. Everybody is using AI to bring the best outta them. It's essential to provide an AI tool powerful prompts that brings the best output. Using promptpedia, you can discover, create and share such powerful prompts. 

1. Sign in with Google.
2. Create a prompt and share it with the world.
3. Delete and Edit the prompts you have posted in the past with ease, no pressure.
4. Discover other powerful prompts posted by other users in the platform.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Features

* Secured authentication using Google oAuth.
* Multiple accounts support.
* Full CRUD operations can be performed by an user.
* Copy the prompts you need with ease.
* Visit other users' profiles and discover the prompts they've posted.
* Post unlimited prompts.

### Built With

* [Next.js](https://nextjs.org/)
* [MongoDB](https://www.mongodb.com/)
* [NextAuth.js](https://next-auth.js.org/)
* [React](https://react.dev/)
* [Express.js](https://expressjs.com/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## Getting Started

Promptpedia is a web based platform which also gives a native feel on mobile devices. You can use it for free from [Promptpedia](https://promptpedia.sriramvaishnav.com/). Or you can build it from the source
with the following instructions.

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/Oxlac/Promptpedia.git
   ```
2. Install Requirements
   ```sh
    npm install
   ```
3. Run the app
   ```sh
    npm run dev
   ```

## Environment Variables

In order for the app to function ideally as the final site, You have to create a .env in the root directory and include the following 6 keys:
1. GOOGLE_ID 
2. GOOGLE_CLIENT_SECRET
   GET THESE TWO BY FOLLOWING THE BELOW STEPS:
   - Go to the Google Developers Console.
   - Click Select a project ➝ New Project ➝ the Create button.
   - Enter your Project name ➝ click the Create button.
   - Click OAuth consent screen in the left side menu ➝ choose User Type ➝ click the Create button.
   - Add Application name ➝ Support email ➝ Authorized domain ➝ Developer content information ➝ click the Save and Continue button.
   - Complete all 4 steps in OAuth consent screen ➝ click the Back to Dashboard button.
   - Go to Credentials ➝ click Create Credentials ➝ select OAuth client ID from the dropdown list.
   - Open the dropdown list Application type ➝ select Web application ➝ enter the name of your OAuth 2.0 client.
   - Enter your site URL in Authorized JavaScript origins ➝ in Authorized redirect URIs, enter the page URL where you wanted your users redirected back after they have authenticated with Google ➝ click the Create button.
   - Copy your Client ID and Client Secret.
   
3. MONGODB_URI
     - Create and set up a new mongoDB cluster
     - Get your URI Connection string by clicking 'connect' -> 'connect your application' -> copy the connection string and paste it in your .env file.
     - It should be in this format : mongodb://[specified user name: specified password@]host 1[:specified port number 1][,….. host N][:specified port number N] [/[specified database name]][?options]
       
5. NEXTAUTH_URL - The URL in which you want the auth to work (eg: 'http://localhost:3000')
6. NEXTAUTH_URL_INTERNAL - Same as above (eg: 'http://localhost:3000')
7. NEXTAUTH_SECRET - Run this command in any bash terminal - 'openssl rand -base64 32' and copy the output you get.


<p align="right">(<a href="#readme-top">back to top</a>)</p>

See the [open issues](https://github.com/Oxlac/Promptpedia/issues) for a full list of proposed features (and known issues). If you have any other ideas, please open an issue and let us know.

## Contributing

Contributions are what makes the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Ensure that your code passes the ruff linter. If it does not pass view the errors and fix them.
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## Contact

Website: [Oxlac](https://oxlac.com) - contact@oxlac.com

Project Link: [https://github.com/Oxlac/Promptpedia](https://github.com/Oxlac/Promptpedia)

Developer: [Sriram Vaishnav](https://sriramvaishnav.com)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
