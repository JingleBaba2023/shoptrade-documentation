# Developer Guide

## Setup
For setting up the project on your local machine, follow the instructions below

## Github

Get the codebase from **Github** Repository

    git clone https://github.com/JingleBaba2023/shoptrade-documentation.git

## Local Setup

Follow the below commands to setup and start local sever on your system

<code-group>
  <code-block title="YARN" style="color: red">
  ```bash
    cd shoptrade-documentation/docs 
    yarn
    yarn dev
  ```
  </code-block>

  <code-block title="NPM">

  ```bash
    cd shoptrade-documentation/docs 
    npm install
    npm run dev
  ```
  </code-block>
</code-group>

::: tip local server
  Local server is now up and running and mostly accessible at **[localhost](https://github.com/JingleBaba2023/shoptrade-documentation)**
:::

## Deployment
To deploy the project on the Github pages move to the docs directory and run the following command.

    bash deploy.sh

::: warning
  Github pages takes little time to publish changes and be visible
:::
