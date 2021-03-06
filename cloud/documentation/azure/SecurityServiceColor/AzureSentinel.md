# AzureSentinel
```text
elements/azure/SecurityServiceColor/AzureSentinel
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![AzureSentinel icon](../../../icons/azure/SecurityServiceColor/AzureSentinel.png) | ![AzureSentinel element](AzureSentinel.element.png) | ![AzureSentinel card](AzureSentinel.card.png) |
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
include('styles/azure')

' loads the AzureSentinel element
include('elements/azure/SecurityServiceColor/AzureSentinel')
AzureSentinel('element', 'Sentinel', 'an optional tech field')
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
include('styles/azure')

' loads the AzureSentinel element
include('elements/azure/SecurityServiceColor/AzureSentinel')
AzureSentinel('element', 'Sentinel', 'an optional tech field')
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
include('styles/azure')

' loads the AzureSentinel card
include('elements/azure/SecurityServiceColor/AzureSentinel')
AzureSentinelCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
include('styles/azure')

' loads the AzureSentinel card
include('elements/azure/SecurityServiceColor/AzureSentinel')
AzureSentinelCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
