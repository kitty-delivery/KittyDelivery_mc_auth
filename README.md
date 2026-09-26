<div align="center">
  <img src=".github/assets/banner.png" alt="KittyDelivery Auth Service banner" width="100%" />

  <h1>KittyDelivery, Auth Service</h1>

  <p>Node.js / Express microservice of the KittyDelivery project, internally declared as "KittyDelivery_General".</p>

  <p>
    <img src="https://img.shields.io/github/last-commit/kitty-delivery/KittyDelivery_mc_auth" alt="last update" />
    <img src="https://img.shields.io/badge/stack-Node.js%20%2F%20Express-green" alt="stack" />
  </p>
</div>

<br />

## :notebook_with_decorative_cover: Table of Contents

- [About the Project](#star2-about-the-project)
  * [Tech Stack](#space_invader-tech-stack)
- [Installation](#gear-installation)
- [Related Repositories](#link-related-repositories)
- [Contact](#handshake-contact)

## :star2: About the Project

This repository is part of the [KittyDelivery](https://github.com/kitty-delivery/KittyDelivery) microservices architecture, a food delivery application built as a student project. The service's `package.json` names it `kittydelivery-general` and its original README says "KittyDelivery_General".

Like the other services generated from the same Express skeleton (EJS view engine with layouts), the exposed routes still return the generator's default responses and do not implement any business logic of their own at this stage.

### :space_invader: Tech Stack

<details>
  <summary>Server</summary>
  <ul>
    <li><a href="https://expressjs.com/">Express</a></li>
    <li><a href="https://ejs.co/">EJS</a> with express-ejs-layouts</li>
    <li>cookie-parser, morgan, http-errors</li>
  </ul>
</details>

## :gear: Installation

```bash
npm install
npm run devstart
```

The service starts via `node ./bin/www` (`start` script), or with automatic reload via `nodemon` (`devstart` script).

## :link: Related Repositories

This microservice is part of the [KittyDelivery](https://github.com/kitty-delivery/KittyDelivery) project, alongside [KittyDelivery_core](https://github.com/kitty-delivery/KittyDelivery_core), [KittyDelivery_API](https://github.com/kitty-delivery/KittyDelivery_API), [KittyDelivery_mc_user](https://github.com/kitty-delivery/KittyDelivery_mc_user), [KittyDelivery_mc_restaurant](https://github.com/kitty-delivery/KittyDelivery_mc_restaurant), [KittyDelivery_mc_component](https://github.com/kitty-delivery/KittyDelivery_mc_component), [KittyDelivery_mc_notif](https://github.com/kitty-delivery/KittyDelivery_mc_notif), [KittyDelivery_mc_article](https://github.com/kitty-delivery/KittyDelivery_mc_article), [KittyDelivery_mc_log](https://github.com/kitty-delivery/KittyDelivery_mc_log), [KittyDelivery_mc_menu](https://github.com/kitty-delivery/KittyDelivery_mc_menu) and [KittyDelivery_mc_order](https://github.com/kitty-delivery/KittyDelivery_mc_order).

## :handshake: Contact

Brieuc Dumortier, [LinkedIn](https://www.linkedin.com/in/dumortier-brieuc/), dumortier.contact@gmail.com
