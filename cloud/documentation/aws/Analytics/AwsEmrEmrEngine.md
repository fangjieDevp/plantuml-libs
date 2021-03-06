# AwsEmrEmrEngine
```text
elements/aws/Analytics/AwsEmrEmrEngine
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![AwsEmrEmrEngine icon](../../../icons/aws/Analytics/AwsEmrEmrEngine.png) | ![AwsEmrEmrEngine element](AwsEmrEmrEngine.element.png) | ![AwsEmrEmrEngine card](AwsEmrEmrEngine.card.png) |
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

' loads the AwsEmrEmrEngine element
include('elements/aws/Analytics/AwsEmrEmrEngine')
AwsEmrEmrEngine('element', 'Emr Emr Engine', 'an optional tech field')
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

' loads the AwsEmrEmrEngine element
include('elements/aws/Analytics/AwsEmrEmrEngine')
AwsEmrEmrEngine('element', 'Emr Emr Engine', 'an optional tech field')
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

' loads the AwsEmrEmrEngine card
include('elements/aws/Analytics/AwsEmrEmrEngine')
AwsEmrEmrEngineCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the AwsEmrEmrEngine card
include('elements/aws/Analytics/AwsEmrEmrEngine')
AwsEmrEmrEngineCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
