<p align="center">Project LECOP</p>

<p align="center">
<a href="https://github.com/DevDHera/Project-LECOP/issues"><img alt="Issues" src="https://img.shields.io/github/issues/DevDHera/Project-LECOP.svg"></a>
<a href="https://github.com/DevDHera/Project-LECOP/blob/master/LICENSE"><img alt="License" src="https://img.shields.io/github/license/DevDHera/Project-LECOP.svg"></a>
<a href="https://app.fossa.io/projects/git%2Bgithub.com%2FDevDHera%2FProject-LECOP?ref=badge_shield" alt="FOSSA Status"><img src="https://app.fossa.io/api/projects/git%2Bgithub.com%2FDevDHera%2FProject-LECOP.svg?type=shield"/></a>
<a href="https://www.codacy.com/app/DevDHera/Project-LECOP?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=DevDHera/Project-LECOP&amp;utm_campaign=Badge_Grade"><img src="https://api.codacy.com/project/badge/Grade/aaf647761af846fe8ef35d0bd6221f27"/></a>
</p>

# Project LECOP

Project LECOP is a Laravel based ECommerce platform. Current stage focuses heavily on the API development with tons of features like,

* Stripe Integration
* Email Verifications

and much more.

## Getting Started

Getting started with the `Project LECOP` is easy.

First clone the project.

```sh
git clone https://github.com/DevDHera/Project-LECOP.git
```

Now head over to our [issue board](https://github.com/DevDHera/Project-LECOP/issues) and help solving :angel: 

### Prerequisites

`Project LECOP` uses **[Vagrant](https://www.vagrantup.com/)** to manage Dev Environments.

In order to successfully run the project install the following.

* XAMPP | WAMP | LAMP
* Composer
* Virtual Box
* Vagrant

### Configurations

After installing the above make sure to create `Homestead.yaml` file on the root of the project containg envs.

Following is the structure that we are using.

```yaml
ip: 
memory: 
cpus: 
provider: 
authorize: 
keys:
    - 
folders:
    -
        map: 
        to: 
sites:
    -
        map: 
        to: 
databases:
    - 
name: 
hostname: 

```

## Deployment

To deploy the API first you need to start the dev environment using the following command.

```sh
vagrant up
```

Then connet by using ssh.

```sh
vagrant ssh
```

No need to run `php artisan serve` commannds. 

## Built With

* [Laravel](https://laravel.com/) - The web framework used
* [Composer](https://getcomposer.org/) - Dependency Management
* [Vagrant](https://www.vagrantup.com/) - Used to manage Development Environments

## Contributing

Please read [CODE_OF_CONDUCT.md](https://github.com/DevDHera/Project-LECOP/blob/master/CODE_OF_CONDUCT.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Authors

* **Devin Herath** - *Initial work* - [DevDHera](https://github.com/DevDHera)

See also the list of [contributors](https://github.com/DevDHera/Project-LECOP/graphs/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/DevDHera/Project-LECOP/blob/master/LICENSE) file for details.

[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FDevDHera%2FProject-LECOP.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2FDevDHera%2FProject-LECOP?ref=badge_large)

## Acknowledgments

* [PurpleBooth](https://github.com/PurpleBooth) for this awesome README template :heart: