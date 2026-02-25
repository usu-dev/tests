# usu test suite

The official usu test suite.

## Passing

Within `cases/pass` there is a directory for each case containing:

- input `in.usu` file
- output `out.json` file

Implementations should be able to parse `in.usu` into a native `UsuNode` object which is serialized using only string values to the associated `out.json`.

## Failing

Within `cases/fail` there is a directory for each case containing:

- input `in.usu` file
- output `out.msg` file

Implementations should fail to parse `in.usu` and optionally can match error messages to `out.msg` (which are derived from [reference implementation](https://github.com/usu-dev/usu-nim)).

&nbsp;

<p align="center"><img src="https://raw.githubusercontent.com/usu-dev/usu/main/assets/footer.svg" width="100%"></p>
<p align="center">Copyright &copy; 2023-present <a href="https://github.com/usu-dev" target="_blank">Usu Org</a>
<a>
