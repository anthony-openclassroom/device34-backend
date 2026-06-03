# 1.0.0 (2026-06-02)


### Bug Fixes

* **security:** externalize database credentials to environment variables ([388e1d2](https://github.com/GorskiAnthony/device34-backend/commit/388e1d2d188aff807e26c838c85b9d63d75dcc06))
* **sonar:** exclude swagger-ui vendor files and generated code from analysis ([6bcc5b6](https://github.com/GorskiAnthony/device34-backend/commit/6bcc5b6cc9eb8b11ae7f282a693c2dd90afa79a2))
* use workshops_user as owner in SQL dump to match POSTGRES_USER ([9c70f6b](https://github.com/GorskiAnthony/device34-backend/commit/9c70f6b5e9ace59c3dc6e1002bd3693f866c5745))


### Features

* add multi-stage Dockerfile with Gradle builder and JRE runtime ([27d3bd8](https://github.com/GorskiAnthony/device34-backend/commit/27d3bd8842bfd9fc4fbf6b1e09d18cb170104266))
* **ci:** add scheduled CI job to run every Monday at 8:00 UTC for regression detection ([4a8128f](https://github.com/GorskiAnthony/device34-backend/commit/4a8128fd2150118d87aa379298a9f0142702f56e))
* configure docker-compose with healthcheck, persistence volume and env vars ([be2f634](https://github.com/GorskiAnthony/device34-backend/commit/be2f63415fd5bc0ec0ccbe1bdb210ac441f5f6f0))
