[spring-plugin](../../index.md) / [org.rewedigital.dialog.spring.annotations](../index.md) / [FallbackIntentHandler](./index.md)

# FallbackIntentHandler

`@Target([AnnotationTarget.CLASS, AnnotationTarget.TYPE]) @Component annotation class FallbackIntentHandler`

Indicates that this class is an [FallbackIntentHandler](./index.md) and implements the
[org.rewedigital.dialog.handler.DialogflowIntentHandler](https://github.com/rewe-digital-incubator/dialog/blob/master/docs/core/org.rewedigital.dialog.handler/-dialogflow-intent-handler/index.md) interface.

[FallbackIntentHandler](./index.md) has the [Component](https://docs.spring.io/spring-framework/docs/current/javadoc-api/org/springframework/stereotype/Component.html) Annotation and will be autogenerated by Spring.
The [FallbackIntentHandler](./index.md) is a special kind of [IntentHandler](../-intent-handler/index.md) witch will be triggered
if the [org.rewedigital.dialog.resolver.RequestResolver](https://github.com/rewe-digital-incubator/dialog/blob/master/docs/core/org.rewedigital.dialog.resolver/-request-resolver/index.md) can't find a matching [IntentHandler](../-intent-handler/index.md)
for the incoming request. The [org.rewedigital.dialog.handler.DialogflowIntentHandler.canHandleDialogflowIntent](https://github.com/rewe-digital-incubator/dialog/blob/master/docs/core/org.rewedigital.dialog.handler/-dialogflow-intent-handler/can-handle-dialogflow-intent.md)
method will be ignored then.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `FallbackIntentHandler()`<br>Indicates that this class is an [FallbackIntentHandler](./index.md) and implements the [org.rewedigital.dialog.handler.DialogflowIntentHandler](https://github.com/rewe-digital-incubator/dialog/blob/master/docs/core/org.rewedigital.dialog.handler/-dialogflow-intent-handler/index.md) interface. |
