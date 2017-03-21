# (Beta!) fugue-user-iam-templates
User and installer IAM templates for Fugue.

We've created two policy documents that together contain the minimum required permissions to run the Fugue CLI:

* The installer policy allows only `install`, `upgrade`, and `uninstall`.
* The user policy allows only `init`, `history`, `kill`, `property`, `resume`, `run`, `status`, `suspend`, and `update`.

**Note:** These policies are in beta mode. While they aren't officially supported yet, you're welcome to try them out. If you find problems, let us know at support@fugue.co.

To gain administrative access – that is, if you're both the installer and the user – you can attach both policies to your IAM user so you have full access to all Fugue CLI commands.

For more details, see [the Fugue Docs site](https://beta-docs.fugue.co/user-guide-installation.html#aws-permissions-and-the-fugue-cli).
