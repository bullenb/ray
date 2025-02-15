---
title: Installation in Laravel
weight: 3
---

If you use Laravel, this is the way.

```bash
composer require spatie/laravel-ray
```

By installing Ray this way it will also be installed in your production environment. This way your application will not break if you forget to remove a `ray` call.  The package will not attempt to transmit information to Ray when the app environment is set to `production`.

You could opt to install `laravel-ray` as a dev dependency. If you go this route, make sure to remove every `ray` call in the code before deploying.

```bash
composer require spatie/laravel-ray --dev
```
