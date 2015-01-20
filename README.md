# plushu-mongodb-service

Plushu service module for MongoDB

## Usage

(assuming a Plushu setup with the `apps`, `services`, `addons`, and `app-long-opt` plugins installed)

```bash
plushu services:install mongodb
plushu apps:create example
plushu --app=example addons:add mongodb
```
