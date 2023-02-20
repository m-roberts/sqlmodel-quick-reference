# SQLModel Quick Reference

## Where did these files come from?

These files are taken from https://github.com/tiangolo/sqlmodel/blob/main/docs_src/tutorial. Each file is named after its directory. Its position is relative to where it features in the main docs.

I have applied syntax upgrading by running the following:

```shell
ruff --isolated . --select UP,F401 --fix
```

## TODO

Still need to confirm that all useful features can be inferred from these files. Some intermediate steps may be lost but useful.

## Notes on SQLModel

Provides [better editor support than SQLAlchemy](https://sqlmodel.tiangolo.com/tutorial/select/#sqlmodel-or-sqlalchemy-technical-details), with autocompletion and inline errors everywhere, even after getting data from a select.

SQLModel is designed to have the best developer experience in a [narrow set of very common use cases](https://sqlmodel.tiangolo.com/tutorial/select/#caveats-of-sqlmodel-flavor). ✨

You can still combine it with SQLAlchemy directly and use all the features of SQLAlchemy when you need to, including lower level more "pure" SQL constructs, exotic patterns, and even legacy ones. 🤓

## Other Resources

- A FastAPI/SQLModel [demo site](https://github.com/AlanSimpsonMe/FastAPI-SQLModel)
- Tutorial for [code structure](https://github.com/tiangolo/sqlmodel/blob/main/docs_src/tutorial/code_structure)
- Tutorial for [app testing](https://github.com/tiangolo/sqlmodel/blob/main/docs_src/tutorial/fastapi/app_testing)
