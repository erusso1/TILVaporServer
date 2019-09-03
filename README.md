<p align="center">
    <img src="https://user-images.githubusercontent.com/1342803/43869499-ce6ce122-9b40-11e8-8894-e0c48eabf270.png" width="320" alt="Web Template">
    <br>
    <br>
    <a href="http://docs.vapor.codes/3.0/">
        <img src="http://img.shields.io/badge/read_the-docs-2196f3.svg" alt="Documentation">
    </a>
    <a href="https://discord.gg/vapor">
        <img src="https://img.shields.io/discord/431917998102675485.svg" alt="Team Chat">
    </a>
    <a href="LICENSE">
        <img src="http://img.shields.io/badge/license-MIT-brightgreen.svg" alt="MIT License">
    </a>
    <a href="https://circleci.com/gh/vapor/web-template">
        <img src="https://circleci.com/gh/vapor/web-template.svg?style=shield" alt="Continuous Integration">
    </a>
    <a href="https://swift.org">
        <img src="http://img.shields.io/badge/swift-4.1-brightgreen.svg" alt="Swift 4.1">
    </a>
</p>

## Installation instructions
* Grab this repo
* Install Vapor if needed
* run `brew tap vapor/tap`
* run `brew install vapor/tap/vapor`
* Export development environment variables i.e `export SOME_VARIABLE=<YOUR_KEY_HERE>`
* Run a PostgreSQL databse instance via `Docker` using `docker run --name postgres -e POSTGRES_DB=vapor -e POSTGRES_USER=vapor -e POSTGRES_PASSWORD=password -p 5432:5432 -d postgres`.
* run `vapor build` from inside of it
* run `vapor run` for a hot-reloading dev server on `localhost:8080`
* If you'd like to use Xcode as your editor, run `vapor xcode -y`. Select the `Run` scheme, use CMD+B to build & CMD+R to build + run. Edit scheme and select `Arguments` tab to add environment variables there.
