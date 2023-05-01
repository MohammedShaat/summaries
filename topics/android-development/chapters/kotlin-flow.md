# Kotlin Flow

## Flow collection
Flow is by default collected sequentially which means if the collector is slower than the producer then the producer is suspended until the collector has completed.

-But when we can modify this behavior by using various operators, including `buffer()`, `conflate()`, and `collectLatest()`.


* `buffer()` It allows the producer to continue in emitting even if the collector is slower by buffering the emitted elements.  
<br>
* `conflate()`: It drops the intermediate emitted elements if the collector is slower than the producer.
<br>
* `collectLatest()`: It cancels the previous collection if the collector is slower than the producer and there is a new emitted element.
<br>

## Flow vs. StateFlow
**Flow** is used toemit multiple values over time that can be buffered and consumed later.
On the other hand, **StateFlow** is used to keep one single value to use it as a state.

\- Also **Flow** is *cold*, meaning that it only emits values when there are collectors, otherwise it do nothing.
**StateFlow**, on the other hand, is *hot*, which means that it emits values even if there are no collectors.
<br>

## SharedFlow vs. LiveData
Both **SharedFlow** and **LiveData** hold state, the difference is that **SharedFlow** isn't lifecycle-aware, which means that it doesn't automatically cancel collectors when the activity or fragment isn't not in active satte (e.g., in the background), but it offers more operators (transformations).
<br>

## SharedFlow vs. Channel
**Channel** is used for one collector, and if there are multiple collectors then the event will be received by the first collector.
Also when sending an event and there is no collector the sender will be suspended until a collector becomes available.

**SharedFlow** is ued for multiple collectors.
When sending an event and there are no collectors then the event is lost by deafult, but we can configure it by passing `replay` with a value grater than zero, so that the event will be cached until collectors receive it.