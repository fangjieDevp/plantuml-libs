# MaterialsViewCompact
```text
elements/materials/Image/MaterialsViewCompact
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![MaterialsViewCompact icon](../../../icons/materials/Image/MaterialsViewCompact.png) | ![MaterialsViewCompact element](MaterialsViewCompact.element.png) | ![MaterialsViewCompact card](MaterialsViewCompact.card.png) |
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
include('styles/materials')

' loads the MaterialsViewCompact element
include('elements/materials/Image/MaterialsViewCompact')
MaterialsViewCompact('element', 'View Compact', 'an optional tech field')
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
include('styles/materials')

' loads the MaterialsViewCompact element
include('elements/materials/Image/MaterialsViewCompact')
MaterialsViewCompact('element', 'View Compact', 'an optional tech field')
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
include('styles/materials')

' loads the MaterialsViewCompact card
include('elements/materials/Image/MaterialsViewCompact')
MaterialsViewCompactCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
include('styles/materials')

' loads the MaterialsViewCompact card
include('elements/materials/Image/MaterialsViewCompact')
MaterialsViewCompactCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
