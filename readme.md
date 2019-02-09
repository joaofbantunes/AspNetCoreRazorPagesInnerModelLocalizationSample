# AspNetCoreRazorPagesInnerModelLocalizationSample

Very small sample of how to localize DataAnnotations in models that are inside page model classes.

In this sample, we have the `IndexModel` which has an internal `InputModel`. To make its data annotations localized, the naming convention is for the resource file is `IndexModel+InputModel.CULTURE.resx`.