# Devfile-yaml-editor

This extension has the goal of turning your current vscode project into a devfile and getting
you to try out Eclipse Che!

It does this by first, providing a command that allows you to generate a devfile for your current project.
You get to define your project name, your plugins [1], and your tooling containers.

Next, it brings yaml support via VSCode-YAML to provide you with an enhanced devfile editing experience,
so that every customization you want can be done before you even start a Che workspace.

![Devfile Generation](./demo/devfileGeneration.gif)

[1] - It tries to match your local vscode plugins against plugins that are already in the Che registry,
if it cannot find a perfect version match it will allow you to select the latest version of the plugin.
