# labelord

Global multi-project management of GitHub labels (MI-PYT@FIT CTU project)

----

This Python app allows user to do via CLI:

* List repositories
* List labels for given repository
* Run update/replace labels for multiple projects (labels are specified in configuration file or by template repo)

App allows you run master-to-master replication web server which works with GitHub webhooks and manage labels for multiple repositories in even simpler way (try `run_server` command and see landing page for more information)!


For more information please use `--help`.

This project is reference solution for Labelord tasks series in [cvut/MI-PYT](https://github.com/cvut/MI-PYT).

## Config

See included config file what are the options. You will need a personal GitHub token for using this application. You can get your token at https://github.com/settings/tokens. But be careful where you place it!


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for more details.
