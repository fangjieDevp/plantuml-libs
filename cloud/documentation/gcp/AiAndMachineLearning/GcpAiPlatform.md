# GcpAiPlatform
```text
elements/gcp/AiAndMachineLearning/GcpAiPlatform
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![GcpAiPlatform icon](../../../icons/gcp/AiAndMachineLearning/GcpAiPlatform.png) | ![GcpAiPlatform element](GcpAiPlatform.element.png) | ![GcpAiPlatform card](GcpAiPlatform.card.png) |
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
include('styles/gcp')

' loads the GcpAiPlatform element
include('elements/gcp/AiAndMachineLearning/GcpAiPlatform')
GcpAiPlatform('element', 'Ai Platform', 'an optional tech field')
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
include('styles/gcp')

' loads the GcpAiPlatform element
include('elements/gcp/AiAndMachineLearning/GcpAiPlatform')
GcpAiPlatform('element', 'Ai Platform', 'an optional tech field')
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
include('styles/gcp')

' loads the GcpAiPlatform card
include('elements/gcp/AiAndMachineLearning/GcpAiPlatform')
GcpAiPlatformCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
include('styles/gcp')

' loads the GcpAiPlatform card
include('elements/gcp/AiAndMachineLearning/GcpAiPlatform')
GcpAiPlatformCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
