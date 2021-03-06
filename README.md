# Ansible-Role-OpenJDK

Installs the OpenJDK version 10 from archive

## Table of content

* [How to install](#how-to-install)
* [Role variables](#role-variables)
* [Example playbook](#example-playbook)
* [Support](#support)
* [Contributing](#contributing)
* [License](#license)

## How to install

```
ansible-galaxy install janesmae.openjdk
```

## Role variables

```
# Default options
openjdk_source: https://download.java.net/java/GA/jdk10/10.0.2/19aef61b38124481863b1413dce1855f/13/openjdk-10.0.2_linux-x64_bin.tar.gz
openjdk_folder: /usr/local/jdk-10

# Setting alternatives
openjdk_alternatives: true
```

## Example playbook

    - hosts: all
      roles:
         - { role: janesmae.openjdk }

## Support

Please open an issue to receive support for this project.

## Contributing

Please read [CONTRIBUTING.md][contributing] for details on our code of conduct.

The process for submitting pull requests:.

* Fork it!
* Create your feature branch: `git checkout -b my-new-feature`
* Commit your changes: `git commit -am 'Add some feature'`
* Push to the branch: `git push origin my-new-feature`
* Submit a pull request

## License

The content of this repository is **&copy; Jaan Janesmae** and released under the **MIT License**.<br>
You can find a copy of this license in [LICENSE][license] file
or [https://opensource.org/licenses/MIT][license_web].

[contributing]:		./CONTRIBUTING.md
[license]:			./LICENSE
[license_web]:		https://opensource.org/licenses/MIT

