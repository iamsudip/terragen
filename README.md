# terragen (BROKEN/WIP)
Generate terraform code you don't like to write

# Commands

- terragen (Should generate outputs.tf, data.tf, variables.tf, doesn't generate tfvars)
- terragen variables
- [ ] Add more commands, there will be a magic mode, where you need to execute as `terragen` and it will know what needs to generate

# TODOs

- [x] Variables generation
- [x] Caller module code generation
- [x] Write to path/stdout (configurable)
- [ ] Usage documentation
- [ ] Configuration management via some config file
- [ ] Generate documentation automagically (basically download terraform documentation recursively, create local database, generate documentation code in variables.tf and outputs.tf)
- [ ] Parser for HCL, so that code parsing and generation is easy, right now it's powered by regex and normal python formatter.
- [ ] Make API more extensible to support all providers, basic functionality has been tested on AWS provider, should work fine with other major providers as well but doc generation needs work. As of now, discovered two resource naming patterns by hashicorp
- [ ] PyPI package
- [ ] Py-test integration
- [ ] Samples
