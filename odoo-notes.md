# How To Upgrade Module From Terminal in Odoo

```bash
./odoo-bin -d db_name -u module_name -c odoo.conf
```

Odoo provides a mechanism to help set up a new module, odoo-bin has a subcommand scaffold to create an empty module:

```bash
$ odoo-bin scaffold <module name> <where to put it>
```
