# AzureIntuneMobileApplicationManagement
```text
elements/azure/FlatSymbols/CneIntune/AzureIntuneMobileApplicationManagement
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![AzureIntuneMobileApplicationManagement icon](../../../../icons/azure/FlatSymbols/CneIntune/AzureIntuneMobileApplicationManagement.png) | ![AzureIntuneMobileApplicationManagement element](AzureIntuneMobileApplicationManagement.element.png) | ![AzureIntuneMobileApplicationManagement card](AzureIntuneMobileApplicationManagement.card.png) |
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

' loads the AzureIntuneMobileApplicationManagement element
include('elements/azure/FlatSymbols/CneIntune/AzureIntuneMobileApplicationManagement')
AzureIntuneMobileApplicationManagement('element', 'Intune Mobile Application Management', 'an optional tech field')
@enduml
```
### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../../../"

' loads the library
!include ../../../../library.puml

' loads the style
include('styles/azure')

' loads the AzureIntuneMobileApplicationManagement element
include('elements/azure/FlatSymbols/CneIntune/AzureIntuneMobileApplicationManagement')
AzureIntuneMobileApplicationManagement('element', 'Intune Mobile Application Management', 'an optional tech field')
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

' loads the AzureIntuneMobileApplicationManagement card
include('elements/azure/FlatSymbols/CneIntune/AzureIntuneMobileApplicationManagement')
AzureIntuneMobileApplicationManagementCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../../../"

' loads the library
!include ../../../../library.puml

' loads the style
include('styles/azure')

' loads the AzureIntuneMobileApplicationManagement card
include('elements/azure/FlatSymbols/CneIntune/AzureIntuneMobileApplicationManagement')
AzureIntuneMobileApplicationManagementCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
