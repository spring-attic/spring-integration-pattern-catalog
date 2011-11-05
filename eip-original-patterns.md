Spring Integration from the Original Enterprise Integration Pattern Perspective
===============================================================================

## Integration Styles

 Original EIP Representation                                                  | Pattern Name                |Equivalent in Spring Integration                               
------------------------------------------------------------------------------|-----------------------------|--------------------------------
 [[http://eaipatterns.com/img/FileTransferIcon.gif]]                          | File Transfer               |
 [[http://eaipatterns.com/img/SharedDatabaseIcon.gif]]                        | Shared Database             |
 [[http://eaipatterns.com/img/EncapsulatedSynchronousIcon.gif]]               | Remote Procedure Invocation |
 [[http://eaipatterns.com/img/MessagingIcon.gif]]                             | Messaging                   |

## Messaging Systems

 Original EIP Representation                                                  | Pattern Name                |Equivalent in Spring Integration                               
------------------------------------------------------------------------------|-----------------------------|--------------------------------
 [[http://eaipatterns.com/img/ChannelIcon.gif]]                               | Message Channel             | [[/image/channel.png]]
 [[http://eaipatterns.com/img/MessageIcon.gif]]                               | Message                     |
 [[http://eaipatterns.com/img/PipesAndFiltersIcon.gif]]                       | Pipes and Filters           |
 [[http://eaipatterns.com/img/ContentBasedRouterIcon.gif]]                    | Message Router              | 
 [[http://eaipatterns.com/img/MessageTranslatorIcon.gif]]                     | Message Translator          | [[/image/transformer.png]]
 [[http://eaipatterns.com/img/MessageEndpointIcon.gif]]                       | Message Endpoint            |


## Messaging Channels

 Original EIP Representation                                                  | Pattern Name                |Equivalent in Spring Integration                               
------------------------------------------------------------------------------|-----------------------------|--------------------------------
[[http://eaipatterns.com/img/PointToPointIcon.gif]]                           | Point-to-Point Channel 
[[http://eaipatterns.com/img/PublishSubscribeIcon.gif]]                       | Publish-Subscribe Channel
[[http://eaipatterns.com/img/DatatypeChannelIcon.gif]]                        | Datatype Channel
[[http://eaipatterns.com/img/InvalidMessageChannelIcon.gif]]                  | Invalid Message Channel
[[http://eaipatterns.com/img/DeadLetterChannelIcon.gif]]                      | Dead Letter Channel
[[http://eaipatterns.com/img/GuaranteedMessagingIcon.gif]]                    | Guaranteed Delivery
[[http://eaipatterns.com/img/ChannelAdapterIcon.gif]]                         | Channel Adapter
[[http://eaipatterns.com/img/MessagingBridgeIcon.gif]]                        | Messaging Bridge
[[http://eaipatterns.com/img/MessageBusIcon.gif]]                             | Message Bus

## Message Construction

 Original EIP Representation                                                  | Pattern Name                |Equivalent in Spring Integration                               
------------------------------------------------------------------------------|-----------------------------|--------------------------------
[[http://eaipatterns.com/img/CommandMessageIcon.gif]]                         | Command Message
[[http://eaipatterns.com/img/DocumentMessageIcon.gif]]                        | Document Message
[[http://eaipatterns.com/img/EventMessageIcon.gif]]                           | Event Message
[[http://eaipatterns.com/img/RequestReplyIcon.gif]]                           | Request-Reply
[[http://eaipatterns.com/img/ReturnAddressIcon.gif]]                          | Return Address
[[http://eaipatterns.com/img/CorrelationIdentifierIcon.gif]]                  | Correlation Identifier
[[http://eaipatterns.com/img/MessageSequenceIcon.gif]]                        | Message Sequence
[[http://eaipatterns.com/img/MessageExpirationIcon.gif]]                      | Message Expiration
                                                                              | Format Indicator

## Message Routing

 Original EIP Representation                                                  | Pattern Name                |Equivalent in Spring Integration                               
------------------------------------------------------------------------------|-----------------------------|--------------------------------
[[http://eaipatterns.com/img/ContentBasedRouterIcon.gif]]                     | Content Based Router
[[http://eaipatterns.com/img/MessageFilterIcon.gif]]                          | Message Filter
[[http://eaipatterns.com/img/DynamicRouterIcon.gif]]                          | Dynamic Router
[[http://eaipatterns.com/img/RecipientListIcon.gif]]                          | Recipient List
[[http://eaipatterns.com/img/SplitterIcon.gif]]                               | Splitter
[[http://eaipatterns.com/img/AggregatorIcon.gif]]                             | Aggregator
[[http://eaipatterns.com/img/ResequencerIcon.gif]]                            | Resequencer
[[http://eaipatterns.com/img/DistributionAggregateIcon.gif]]                  | Composed Message Processor
                                                                              | Scatter-Gather
[[http://eaipatterns.com/img/RoutingTableIcon.gif]]                           | Routing Slip
[[http://eaipatterns.com/img/ProcessManagerIcon.gif]]                         | Process Manager
[[http://eaipatterns.com/img/MessageBrokerIcon.gif]]                          | Message Broker

## Message Transformation

 Original EIP Representation                                                  | Pattern Name                |Equivalent in Spring Integration                               
------------------------------------------------------------------------------|-----------------------------|--------------------------------
[[http://eaipatterns.com/img/EnvelopeWrapperIcon.gif]]                        | Envelope Wrapper
[[http://eaipatterns.com/img/DataEnricherIcon.gif]]                           | Content Enricher	
[[http://eaipatterns.com/img/ContentFilterIcon.gif]]                          | Content Filter
[[http://eaipatterns.com/img/StoreInLibraryIcon.gif]]                         | Claim Check
[[http://eaipatterns.com/img/NormalizerIcon.gif]]                             | Normalizer
                              | Canonical Data Model

## Messaging Endpoints

 Original EIP Representation                                                  | Pattern Name                |Equivalent in Spring Integration                               
------------------------------------------------------------------------------|-----------------------------|--------------------------------
[[http://eaipatterns.com/img/MessagingGatewayIcon.gif]]                       | Messaging Gateway
                                                                              | Messaging Mapper
[[http://eaipatterns.com/img/TransactionalClientIcon.gif]]                    | Transactional Client
[[http://eaipatterns.com/img/PollingConsumerIcon.gif]]                        | Polling Consumer
[[http://eaipatterns.com/img/EventDrivenConsumerIcon.gif]]                    | Event-Driven Consumer
[[http://eaipatterns.com/img/CompetingConsumersIcon.gif]]                     | Competing Consumers
[[http://eaipatterns.com/img/MessageDispatcherIcon.gif]]                      | Message Dispatcher
[[http://eaipatterns.com/img/MessageSelectorIcon.gif]]                        | Selective Consumer
[[http://eaipatterns.com/img/DurableSubscriptionIcon.gif]]                    | Durable Subscriber
                                                                              | Idempotent Receiver
[[http://eaipatterns.com/img/MessagingAdapterIcon.gif]]                       | Service Activator

							
## System Management

 Original EIP Representation                                                  | Pattern Name                |Equivalent in Spring Integration                               
------------------------------------------------------------------------------|-----------------------------|--------------------------------
[[http://eaipatterns.com/img/ControlBusIcon.gif]]                             | Control Bus
[[http://eaipatterns.com/img/DetourIcon.gif]]                                 | Detour
[[http://eaipatterns.com/img/WireTapIcon.gif]]                                | Wire Tap
                                                                              | Message History
[[http://eaipatterns.com/img/MessageStoreIcon.gif]]                           | Message Store
[[http://eaipatterns.com/img/SmartProxyIcon.gif]]                             | Smart Proxy
[[http://eaipatterns.com/img/TestMessageIcon.gif]]                            | Test Message
[[http://eaipatterns.com/img/ChannelPurgerIcon.gif]]                          | Channel Purger
