I chose Python as the language to discuss for the exercise.  

Looking at the most commonly used tools thorugh Google, it seems that `Flake8` and `Pylint` are the most common linters used, though recently the Rust-based `Ruff` has gained a lot of popularity due to its significantly faster speed.  

For testing frameworks `Pytest` appears to be by far the most commonly used. Another notable one is `PyUnit`/`Unittest` as it is a part of the standard Python library, though perhaps lacks some of the flexibility of other libraries.  

Some of the build tools include `PyBuilder`, `Poetry`, and `setuptools`. With build tools the best option is generally more down to the developer’s preference and specific needs.  

Alternatives for `Github Actions` and `Jenkins` could include `GitlabCI`, `CircleCI`, or `Azure Devops` to name just a few. However, there exists a long long list of other alternative tools as well, and it will come down to the user how tightly they want to manage their secrets, if they want to self-host, etc. to determine which is the best option.  

If the resources are available, a self-hosted environment would generally be better as it would allow for more control and ensure better security. However, as we do not know if the 6 developers on the team are the only workers available, and whether there is an engineer or CI/CD team with the ability to upkeep the setup, a cloud-based environment might be the better option as this takes away the load of maintaining the infrastructure. 

