When some sensitive parameters are still sent by your app to AppSignal, we will filter these out during processing. This means the data was sent to our servers, where we received and temporarily stored this "pre-processing data". We always use SSL to encrypt data moving between your apps and our servers.

AppSignal filters out the `password` and `password_confirmation` keys from the parameters during processing. These keys are not customizable. These filtered values are replaced with `[REMOVED]` (rather than `[FILTERED]`) to indicate these values were filtered in our processors rather than in your app. Only after this processing, your data is viewable on AppSignal.com. Before that, none of the potentially sent sensitive data is visible to any member of your organization on AppSignal.com. The pre-processing data is removed shortly after processing.