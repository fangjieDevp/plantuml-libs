# GcpDeveloperPortal
```text
elements/gcp/ApiManagement/GcpDeveloperPortal
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![GcpDeveloperPortal icon](../../../icons/gcp/ApiManagement/GcpDeveloperPortal.png) | ![GcpDeveloperPortal element](GcpDeveloperPortal.element.png) | ![GcpDeveloperPortal card](GcpDeveloperPortal.card.png) |
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

' loads the GcpDeveloperPortal element
include('elements/gcp/ApiManagement/GcpDeveloperPortal')
GcpDeveloperPortal('element', 'Developer Portal', 'an optional tech field')
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

' loads the GcpDeveloperPortal element
include('elements/gcp/ApiManagement/GcpDeveloperPortal')
GcpDeveloperPortal('element', 'Developer Portal', 'an optional tech field')
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

' loads the GcpDeveloperPortal card
include('elements/gcp/ApiManagement/GcpDeveloperPortal')
GcpDeveloperPortalCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the GcpDeveloperPortal card
include('elements/gcp/ApiManagement/GcpDeveloperPortal')
GcpDeveloperPortalCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
