---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestBody := msgraphsdk.NewUser()
requestBody.SetAdditionalData(map[string]interface{}{
}
options := &msgraphsdk.UserRequestBuilderPatchOptions{
	Body: requestBody,
}
userId := "user-id"
graphClient.UsersById(&userId).Patch(options)


```