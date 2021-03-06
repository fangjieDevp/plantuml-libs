# MaterialsAssignmentReturned
```text
elements/materials/Action/MaterialsAssignmentReturned
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![MaterialsAssignmentReturned icon](../../../icons/materials/Action/MaterialsAssignmentReturned.png) | ![MaterialsAssignmentReturned element](MaterialsAssignmentReturned.element.png) | ![MaterialsAssignmentReturned card](MaterialsAssignmentReturned.card.png) |
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

' loads the MaterialsAssignmentReturned element
include('elements/materials/Action/MaterialsAssignmentReturned')
MaterialsAssignmentReturned('element', 'Assignment Returned', 'an optional tech field')
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

' loads the MaterialsAssignmentReturned element
include('elements/materials/Action/MaterialsAssignmentReturned')
MaterialsAssignmentReturned('element', 'Assignment Returned', 'an optional tech field')
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

' loads the MaterialsAssignmentReturned card
include('elements/materials/Action/MaterialsAssignmentReturned')
MaterialsAssignmentReturnedCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the MaterialsAssignmentReturned card
include('elements/materials/Action/MaterialsAssignmentReturned')
MaterialsAssignmentReturnedCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
