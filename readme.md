# Hello world docker

this action prints "Hello world" or "Hello" + the name of person to greet

## Inputs

## `Who-to-greet`
**Required** The name of the person to greet. Default `"World"`

## Outputs

## `time`

The time we greeted you

## Example usage
uses: actions/hello-world-docker-action@v1
with:
    who-to-greet: 'Mona the Octocat'