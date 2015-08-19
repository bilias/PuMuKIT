Installation Guide
==================

Steps to install and configure this bundle:

1.- Install the bundle into your Pumukit2 root project:

```bash
$ cd /path/to/pumukit2/
$ php app/console pumukit:install:bundle Pumukit/MoodleBundle/PumukitMoodleBundle
```

2.- Configure the parameters in your `app/config/parameters.yml` file:

```
pumukit_moodle:
    role: actor
    password: ThisIsASecretPasswordChangeMe
```

* `role` defines the role code the professor should be added with in a video. For example: actor.
* `password` defines the secret password between Pumukit and Moodle. It's the same password Moodle uses to install PuMoodle.