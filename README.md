This is a compiled list of terms to help you with naming things for you application. 

## OO terms

Object-oriented terms. 

#### Object

> A representation of something

Entity, Symbol

#### Mediator

> An object which transfers a message between a sender & a receiver

**Classes**: Notifier, Dispatcher, Bus, EventBus, MessageBus, Conductor, Router
**Emit Methods**: notify, emit, dispatch, execute, send
**Listen Methods**: on, addReceiver, addListener

#### Event

> An object which contains a payload emitted from another object

**Classes**: Message, Event, Envelop, Action
**Type Properties**: type, name, action
**Payload Properties**: data, body, payload, message

#### Observable

> An object which can be listened to for events

**Classes**: Observable, EventEmitter, EventDispatcher, Notifiable
**Listen Methods**: observe, addListener, addEventListener, on
**Unlisten Methods**: off, removeListener, removeEventListener

#### Observer

> An object which can receive messages from another object (observable, mediator)

**Classes**: Observer, EventListener, MessageListener

#### Others

> Other uncategorized names

Nouns: Model, ValueObject, Controller, Manager, Actor, DataTransferObject, DisplayObject, Service, Facade, Adapter

## Functional Terms


