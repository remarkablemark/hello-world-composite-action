# hello-world-composite-action

Custom GitHub Actions (Composite). Inspired by the [tutorial](https://docs.github.com/en/actions/creating-actions/creating-a-composite-action).

## Inputs

## `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

## `random-number`

A random number.

## Example usage

```yml
uses: remarkablemark/hello-world-composite-action@v1
with:
  who-to-greet: 'Mona the Octocat'
```

## License

[MIT](LICENSE)
