# sharp-lambda-layer

Lambda layer for utilizing the [Sharp](http://sharp.pixelplumbing.com/en/latest/) image manipulation library

## Note:

It is important that the Sharp dependency is installed for Linux x64, which is what AWS Lambda runs on:

```sh
$ npm install --arch=x64 --platform=linux --target=10.15.0 sharp
```

http://sharp.pixelplumbing.com/en/latest/install/#aws-lambda

## Cloudformation export

Creates an export named `SharpLambdaLayer` that can be referenced within other CF templates.
