# AwsElasticacheCacheNode
```text
elements/aws/Database/AwsElasticacheCacheNode
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![AwsElasticacheCacheNode icon](../../../icons/aws/Database/AwsElasticacheCacheNode.png) | ![AwsElasticacheCacheNode element](AwsElasticacheCacheNode.element.png) | ![AwsElasticacheCacheNode card](AwsElasticacheCacheNode.card.png) |
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

' loads the AwsElasticacheCacheNode element
include('elements/aws/Database/AwsElasticacheCacheNode')
AwsElasticacheCacheNode('element', 'Elasticache Cache Node', 'an optional tech field')
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

' loads the AwsElasticacheCacheNode element
include('elements/aws/Database/AwsElasticacheCacheNode')
AwsElasticacheCacheNode('element', 'Elasticache Cache Node', 'an optional tech field')
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

' loads the AwsElasticacheCacheNode card
include('elements/aws/Database/AwsElasticacheCacheNode')
AwsElasticacheCacheNodeCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the AwsElasticacheCacheNode card
include('elements/aws/Database/AwsElasticacheCacheNode')
AwsElasticacheCacheNodeCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
