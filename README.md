# remove-aws-resources

Using this tool you can quickly cleanup AWS resources created by Webiny deploy process.

🚨 Use this tool at your own risk!! Authors of this tool are not responsible for any damage that may be caused by removal of your AWS resources. 🚨

Sometimes stack state gets messed up due to bugs in deployment/removal process and the easiest way to reset everything is to remove all the AWS resources that were created by the deploy process.

## Usage

Anywhere in your terminal run:

```bash
npx remove-aws-resources
```

The tool will use your AWS credentials, configured in `~/.aws/credentials` to load the relevant resources. You then get to choose which resources to delete.


In the current state, this tool is useful only to the users of [Webiny platform](https://www.webiny.com/). At Webiny, we use it on a daily basis, and it works great for what it was created - Webiny project cleanup.

## Contribute

If you find any issues, or would like to contribute to the tool, head over to https://github.com/webiny/remove-aws-resources. 

You can also find us on Slack at https://webiny.com/slack if you need help with your project or wnt to discuss improvements to this tool.
