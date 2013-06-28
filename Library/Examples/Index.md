# Orchard examples



This list helps to find where to look if you need an example of something in Orchard, so you can look at it when you need to roll out your own similar solution. This is a selection only, not a full list (e.g. many module contain content parts).

Project links are only included if the module/theme is not bundled with the Orchard source. The Training Demo module is not linked every time, it's [under its own repository](https://orchardtrainingdemo.codeplex.com/).


## Modules

- Content item management:
	- Content field: Training Demo
	- Content manager usage from code: Orchard.Core.Contents (/Controllers), Training Demo
	- Content part: Training Demo
	- Content type migration: Orchard.Pages, Training Demo
	- Content type/content part settings: Orchard.Core.Common (/Settings)
- Events: Training Demo
- File handling: Orchard.Media, Training Demo
- Permissions:
	- Static: Orchard.Comments, Training Demo
	- Dynamic: Orchard.Core.Contents (DynamicPermissions)
- Projector providers:
	- Filter: Orchard.Projections, [Helpful Extensions](https://helpfulextensions.codeplex.com/SourceControl/latest#Extensions/Projections/)
	- Layout: Orchard.Projections
	- Sort criteria: Orchard.Projections
- Records (low-level database access): Training Demo
- Resources (static resources: css, js files, resource manifests and resource inclusions): Orchard.jQuery, Training Demo
- Search services from code: [Associativy Core](https://associativycore.codeplex.com/SourceControl/latest#Services/StandardNodeManager.cs)
- Site settings: [SH.GoogleAnalytics](https://github.com/ScharfHoldings/SH.GoogleAnalytics), Training Demo
- Token provider: Orchard.Tokens, [Helpful Extensions](https://helpfulextensions.codeplex.com/SourceControl/latest#Extensions/Tokens/)
- Unit tests: Training Demo, Orchard.Tests.Modules.Tags


## Themes

- Theme with settings: [Orchard Super Classic Theme](https://orchardsuperclassic.codeplex.com/)