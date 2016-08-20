# java-simplefacts


# API
* fluent
* dsl
* playground

when( Cnd ).success( Then ).fail( Then ).rule();

when( Cnd, State )
  .success()
  .fail()
  .rule();

when( Cnd ).choose( SwitchType ).option1( Then ).option2( Then ).others( Then ).rule();


rctx = RuleContext.create(Ctx);

