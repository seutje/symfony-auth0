# Demo TODO application using Symfony and React

This is a simple demo TODO application to show the use of Symfony in combination with React. Based on [this](https://auth0.com/blog/developing-modern-apps-with-symfony-and-react/) tutorial. It uses the Auth0 service, settings for which can be adjusted in ./config/packages/jwt_auth.yaml

## Getting Started

To get this application up and running, simply git clone the repository and run the steps in the "Installing" part.

### Prerequisites

The following things will be required to get the application up and running.

```
PHP7
Symfony
Composer

```

### Installing

After cloning the repository, install the composer packages by running

```
composer install
```

To start the application, run

```
php bin/console server:run
```

You should be presented with the following message

```
[OK] Server listening on http://127.0.0.1:8000
```

The application can now be accessed at the aformentioned URL.

## Built With

* [Symfony](https://symfony.com/) - The web framework used
* [Composer](https://getcomposer.org/) - Dependency Management

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
