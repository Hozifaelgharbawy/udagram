## Pipeline Description

- This application’s repository is monitored by CircleCI, so any time a code commit is pushed to
- the master branch of this application’s repository (udagram-udacity) the CircleCI pipeline is
- triggered, and a series of events are executed.

### This series of CircleCI pipeline events include

      . a Docker container is set up
      . NodeJS is set up inside the container
      . Dependencies are installed
      . AWS command line interfaces are set up
      . Environment secrets are read from inside CircleCI
      . The front-end dependencies are installed
      . The front-end is built
      . The back-end dependencies are installed
      . The back-end is built
      . The back-end is deployed to Elastic Beanstalk inside AWS
      . The front-end is deployed to S3 inside AWS