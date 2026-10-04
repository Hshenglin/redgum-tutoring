# Changelog

All notable changes to this project are documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.2.0] - 2026-10-03

### Added

- Container and deployment configuration: a `Dockerfile`, a `docker-compose.yml`
  and an environment template (`.env.example`).
- A GitHub Actions pipeline that installs the dependencies and runs the test suite.

### Changed

- Documented the `pytest` configuration in `pytest.ini`.

## [0.1.0] - 2026-09-24

### Added

- Coordinator login with role separation between administrators and tutors.
- Student and tutor records with search, create, edit and deactivate.
- Weekly availability windows per tutor.
- Session booking, moving, cancelling and outcome recording, with the centre's
  rule that a session must fit inside a tutor's availability window.
- Day and week schedule, per-student session history, and the tutor's own
  upcoming sessions.
- Demo seed data, a design spec, a handover document and the Jira backlog import,
  delivered as ten story branches.
