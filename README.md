<h1 align="center">
	Background jobs in Node.js with Redis.
</h1>

<p align="center">
  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/luiz-araujo/background-jobs-node.js-redis.svg?color=34cb79">
  <img alt="Project programing languages count" src="https://img.shields.io/github/languages/count/luiz-araujo/background-jobs-node.js-redis?color=34cb79">
  <img alt="Repository size" src="https://img.shields.io/github/repo-size/luiz-araujo/background-jobs-node.js-redis?color=34cb79">
  <a href="https://www.linkedin.com/in/luiz-araujojr/">
    <img alt="Made by Luiz Araújo" src="https://img.shields.io/badge/made%20by-Luiz Araújo-%20?color=34cb79">
  </a>
  <img alt="GitHub license" src="https://img.shields.io/github/license/luiz-araujo/background-jobs-node.js-redis?color=34cb79">
  <a href="https://github.com/luiz-araujo/background-jobs-node.js-redis/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/luiz-araujo/background-jobs-node.js-redis.svg?color=34cb79">
  </a>
</p>

<p align="center">
  <a href="#project">Project</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#how-to-run">How to run</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#built-with">Built with</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#how-to-contribute">How to contribute</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#credits">Credits</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#license">License</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#get-in-touch">Get in touch!</a>
</p>

## Project

This code was made in DIO's Bootcamp Node.js Web Developer.
We will work with background in Node.js with Redis, using a library called Bull to prioritize processes, monitor events, number of simultaneous processes, in addition to working in separate threads in the application.

## How to run

#### Requirements

To clone and run the application you will need:

- [Git](https://git-scm.com)
- [Node](https://nodejs.org/)
- [Yarn](https://yarnpkg.com/)
- [Redis](https://redis.io/)

From your command line:

```bash
# Clone this repository
$ git clone https://github.com/luiz-araujo/background-jobs-node.js-redis.git

# Go into the folder repository
$ cd background-jobs-node.js-redis

# Install dependencies
$ yarn install

# Create your own .env file with email and Redis credentials using .env.example as model

# Run yarn start:server and yarn start:queue to start the full featured local server
$ yarn start:server
$ yarn start:queue

# Or just run yarn start:all to run all at the same time
$ yarn start:all
```

## Built With

- [Express](https://expressjs.com/) — A web framework for Node.js
- [Bull](https://optimalbits.github.io/bull/) — Premium Queue package for handling distributed jobs

## How to contribute

- Make a fork;
- Create a branch with your feature: `git checkout -b my-feature`;
- Commit changes: `git commit -m 'feat: My new feature'`;
- Make a push to your branch: `git push origin my-feature`.

After merging your receipt request to done, you can delete a branch from yours.

## Credits

- [Digital Innovation One](https://www.youtube.com/watch?v=mRHpgEF5JGU) - This video show in a practical way, the concept called “Background jobs”, that is, we will first answer the client's request (front-end) and only then process it, passing the responsibility to a parallel thread of the application, defining processing priority , monitoring events, number of simultaneous processing and more, all using Node.js for our API and Redis to bring the processing queue to life, taking your application to a new level.

## License

This project is under the MIT license. See the [LICENSE](https://github.com/luiz-araujo/background-jobs-node.js-redis/blob/master/LICENSE) for details.

## Get in touch!

<a href="https://www.linkedin.com/in/luiz-araujojr/" target="_blank" >
  <img alt="Linkedin - Luiz Araújo" src="https://img.shields.io/badge/Linkedin--%23F8952D?style=social&logo=linkedin">
</a>&nbsp;&nbsp;&nbsp;

---

Made with ❤️ by Luiz Araújo.
