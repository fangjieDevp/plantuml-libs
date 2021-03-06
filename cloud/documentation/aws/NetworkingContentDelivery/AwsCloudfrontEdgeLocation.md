# AwsCloudfrontEdgeLocation
```text
elements/aws/NetworkingContentDelivery/AwsCloudfrontEdgeLocation
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![AwsCloudfrontEdgeLocation icon](../../../icons/aws/NetworkingContentDelivery/AwsCloudfrontEdgeLocation.png) | ![AwsCloudfrontEdgeLocation element](AwsCloudfrontEdgeLocation.element.png) | ![AwsCloudfrontEdgeLocation card](AwsCloudfrontEdgeLocation.card.png) |
## Element
### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BRANCH="master"
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/" + $LIB_BRANCH + "/cloud"

' loads the library
!includeurl $LIB_BASE_LOCATION/library.puml

' loads the style
include('styles/aws')

' loads the AwsCloudfrontEdgeLocation element
include('elements/aws/NetworkingContentDelivery/AwsCloudfrontEdgeLocation')
AwsCloudfrontEdgeLocation('element', 'Cloudfront Edge Location', 'an optional tech field')
@enduml
```
### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../../"

' loads the library
!include ../../../library.puml

' loads the style
include('styles/aws')

' loads the AwsCloudfrontEdgeLocation element
include('elements/aws/NetworkingContentDelivery/AwsCloudfrontEdgeLocation')
AwsCloudfrontEdgeLocation('element', 'Cloudfront Edge Location', 'an optional tech field')
@enduml
```
## Card
### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BRANCH="master"
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/" + $LIB_BRANCH + "/cloud"

' loads the library
!includeurl $LIB_BASE_LOCATION/library.puml

' loads the style
include('styles/aws')

' loads the AwsCloudfrontEdgeLocation card
include('elements/aws/NetworkingContentDelivery/AwsCloudfrontEdgeLocation')
AwsCloudfrontEdgeLocationCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../../"

' loads the library
!include ../../../library.puml

' loads the style
include('styles/aws')

' loads the AwsCloudfrontEdgeLocation card
include('elements/aws/NetworkingContentDelivery/AwsCloudfrontEdgeLocation')
AwsCloudfrontEdgeLocationCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
