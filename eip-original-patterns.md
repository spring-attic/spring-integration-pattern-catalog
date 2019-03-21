Spring Integration from the Original Enterprise Integration Pattern Perspective
===============================================================================

## Integration Styles

 Original EIP Representation                                                  | Pattern Name                |Equivalent in Spring Integration                               
------------------------------------------------------------------------------|-----------------------------|--------------------------------
 [[https://www.enterpriseintegrationpatterns.com/img/FileTransferIcon.gif]]                          | File Transfer               |
 [[https://www.enterpriseintegrationpatterns.com/img/SharedDatabaseIcon.gif]]                        | Shared Database             |
 [[https://www.enterpriseintegrationpatterns.com/img/EncapsulatedSynchronousIcon.gif]]               | Remote Procedure Invocation |
 [[https://www.enterpriseintegrationpatterns.com/img/MessagingIcon.gif]]                             | Messaging                   |

## Messaging Systems

 Original EIP Representation                                                  | Pattern Name                |Equivalent in Spring Integration                               
------------------------------------------------------------------------------|-----------------------------|--------------------------------
 [[https://www.enterpriseintegrationpatterns.com/img/ChannelIcon.gif]]                               | Message Channel             | [[/image/channel.png]]
 [[https://www.enterpriseintegrationpatterns.com/img/MessageIcon.gif]]                               | Message                     |
 [[https://www.enterpriseintegrationpatterns.com/img/PipesAndFiltersIcon.gif]]                       | Pipes and Filters           |
 [[https://www.enterpriseintegrationpatterns.com/img/ContentBasedRouterIcon.gif]]                    | Message Router              | 
 [[https://www.enterpriseintegrationpatterns.com/img/MessageTranslatorIcon.gif]]                     | Message Translator          | [[/image/transformer.png]]
 [[https://www.enterpriseintegrationpatterns.com/img/MessageEndpointIcon.gif]]                       | Message Endpoint            |


## Messaging Channels

 Original EIP Representation                                                  | Pattern Name                |Equivalent in Spring Integration                               
------------------------------------------------------------------------------|-----------------------------|--------------------------------
[[https://www.enterpriseintegrationpatterns.com/img/PointToPointIcon.gif]]                           | Point-to-Point Channel 
[[https://www.enterpriseintegrationpatterns.com/img/PublishSubscribeIcon.gif]]                       | Publish-Subscribe Channel
[[https://www.enterpriseintegrationpatterns.com/img/DatatypeChannelIcon.gif]]                        | Datatype Channel
[[https://www.enterpriseintegrationpatterns.com/img/InvalidMessageChannelIcon.gif]]                  | Invalid Message Channel
[[https://www.enterpriseintegrationpatterns.com/img/DeadLetterChannelIcon.gif]]                      | Dead Letter Channel
[[https://www.enterpriseintegrationpatterns.com/img/GuaranteedMessagingIcon.gif]]                    | Guaranteed Delivery
[[https://www.enterpriseintegrationpatterns.com/img/ChannelAdapterIcon.gif]]                         | Channel Adapter
[[https://www.enterpriseintegrationpatterns.com/img/MessagingBridgeIcon.gif]]                        | Messaging Bridge
[[https://www.enterpriseintegrationpatterns.com/img/MessageBusIcon.gif]]                             | Message Bus

## Message Construction

 Original EIP Representation                                                  | Pattern Name                |Equivalent in Spring Integration                               
------------------------------------------------------------------------------|-----------------------------|--------------------------------
[[https://www.enterpriseintegrationpatterns.com/img/CommandMessageIcon.gif]]                         | Command Message
[[https://www.enterpriseintegrationpatterns.com/img/DocumentMessageIcon.gif]]                        | Document Message
[[https://www.enterpriseintegrationpatterns.com/img/EventMessageIcon.gif]]                           | Event Message
[[https://www.enterpriseintegrationpatterns.com/img/RequestReplyIcon.gif]]                           | Request-Reply
[[https://www.enterpriseintegrationpatterns.com/img/ReturnAddressIcon.gif]]                          | Return Address
[[https://www.enterpriseintegrationpatterns.com/img/CorrelationIdentifierIcon.gif]]                  | Correlation Identifier
[[https://www.enterpriseintegrationpatterns.com/img/MessageSequenceIcon.gif]]                        | Message Sequence
[[https://www.enterpriseintegrationpatterns.com/img/MessageExpirationIcon.gif]]                      | Message Expiration
                                                                              | Format Indicator

## Message Routing

 Original EIP Representation                                                  | Pattern Name                |Equivalent in Spring Integration                               
------------------------------------------------------------------------------|-----------------------------|--------------------------------
[[https://www.enterpriseintegrationpatterns.com/img/ContentBasedRouterIcon.gif]]                     | Content Based Router
[[https://www.enterpriseintegrationpatterns.com/img/MessageFilterIcon.gif]]                          | Message Filter
[[https://www.enterpriseintegrationpatterns.com/img/DynamicRouterIcon.gif]]                          | Dynamic Router
[[https://www.enterpriseintegrationpatterns.com/img/RecipientListIcon.gif]]                          | Recipient List
[[https://www.enterpriseintegrationpatterns.com/img/SplitterIcon.gif]]                               | Splitter
[[https://www.enterpriseintegrationpatterns.com/img/AggregatorIcon.gif]]                             | Aggregator
[[https://www.enterpriseintegrationpatterns.com/img/ResequencerIcon.gif]]                            | Resequencer
[[https://www.enterpriseintegrationpatterns.com/img/DistributionAggregateIcon.gif]]                  | Composed Message Processor
                                                                              | Scatter-Gather
[[https://www.enterpriseintegrationpatterns.com/img/RoutingTableIcon.gif]]                           | Routing Slip
[[https://www.enterpriseintegrationpatterns.com/img/ProcessManagerIcon.gif]]                         | Process Manager
[[https://www.enterpriseintegrationpatterns.com/img/MessageBrokerIcon.gif]]                          | Message Broker

## Message Transformation

 Original EIP Representation                                                  | Pattern Name                |Equivalent in Spring Integration                               
------------------------------------------------------------------------------|-----------------------------|--------------------------------
[[https://www.enterpriseintegrationpatterns.com/img/EnvelopeWrapperIcon.gif]]                        | Envelope Wrapper
[[https://www.enterpriseintegrationpatterns.com/img/DataEnricherIcon.gif]]                           | Content Enricher	
[[https://www.enterpriseintegrationpatterns.com/img/ContentFilterIcon.gif]]                          | Content Filter
[[https://www.enterpriseintegrationpatterns.com/img/StoreInLibraryIcon.gif]]                         | Claim Check
[[https://www.enterpriseintegrationpatterns.com/img/NormalizerIcon.gif]]                             | Normalizer
                              | Canonical Data Model

## Messaging Endpoints

 Original EIP Representation                                                  | Pattern Name                |Equivalent in Spring Integration                               
------------------------------------------------------------------------------|-----------------------------|--------------------------------
[[https://www.enterpriseintegrationpatterns.com/img/MessagingGatewayIcon.gif]]                       | Messaging Gateway
                                                                              | Messaging Mapper
[[https://www.enterpriseintegrationpatterns.com/img/TransactionalClientIcon.gif]]                    | Transactional Client
[[https://www.enterpriseintegrationpatterns.com/img/PollingConsumerIcon.gif]]                        | Polling Consumer
[[https://www.enterpriseintegrationpatterns.com/img/EventDrivenConsumerIcon.gif]]                    | Event-Driven Consumer
[[https://www.enterpriseintegrationpatterns.com/img/CompetingConsumersIcon.gif]]                     | Competing Consumers
[[https://www.enterpriseintegrationpatterns.com/img/MessageDispatcherIcon.gif]]                      | Message Dispatcher
[[https://www.enterpriseintegrationpatterns.com/img/MessageSelectorIcon.gif]]                        | Selective Consumer
[[https://www.enterpriseintegrationpatterns.com/img/DurableSubscriptionIcon.gif]]                    | Durable Subscriber
                                                                              | Idempotent Receiver
[[https://www.enterpriseintegrationpatterns.com/img/MessagingAdapterIcon.gif]]                       | Service Activator

							
## System Management

 Original EIP Representation                                                  | Pattern Name                |Equivalent in Spring Integration                               
------------------------------------------------------------------------------|-----------------------------|--------------------------------
[[https://www.enterpriseintegrationpatterns.com/img/ControlBusIcon.gif]]                             | Control Bus
[[https://www.enterpriseintegrationpatterns.com/img/DetourIcon.gif]]                                 | Detour
[[https://www.enterpriseintegrationpatterns.com/img/WireTapIcon.gif]]                                | Wire Tap
                                                                              | Message History
[[https://www.enterpriseintegrationpatterns.com/img/MessageStoreIcon.gif]]                           | Message Store
[[https://www.enterpriseintegrationpatterns.com/img/SmartProxyIcon.gif]]                             | Smart Proxy
[[https://www.enterpriseintegrationpatterns.com/img/TestMessageIcon.gif]]                            | Test Message
[[https://www.enterpriseintegrationpatterns.com/img/ChannelPurgerIcon.gif]]                          | Channel Purger
