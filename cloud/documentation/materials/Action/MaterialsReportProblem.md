# MaterialsReportProblem
```text
elements/materials/Action/MaterialsReportProblem
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![MaterialsReportProblem icon](../../../icons/materials/Action/MaterialsReportProblem.png) | ![MaterialsReportProblem element](MaterialsReportProblem.element.png) | ![MaterialsReportProblem card](MaterialsReportProblem.card.png) |
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

' loads the MaterialsReportProblem element
include('elements/materials/Action/MaterialsReportProblem')
MaterialsReportProblem('element', 'Report Problem', 'an optional tech field')
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

' loads the MaterialsReportProblem element
include('elements/materials/Action/MaterialsReportProblem')
MaterialsReportProblem('element', 'Report Problem', 'an optional tech field')
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

' loads the MaterialsReportProblem card
include('elements/materials/Action/MaterialsReportProblem')
MaterialsReportProblemCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the MaterialsReportProblem card
include('elements/materials/Action/MaterialsReportProblem')
MaterialsReportProblemCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
