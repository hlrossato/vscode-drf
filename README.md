# Django REST Framework snippets for Visual Studio Code

A collection of snippets for Django REST Framework api views, serializers.

## Features

### Snippets for Serializers

|   Abbreviation                |  Type  |               Code - Description               |
| ----------------------------- | ------ | ---------------------------------------------- |
| serializer                    | class  | ``Serializer``                                 |
| smodelserializer              | class  | ``ModelSerializer``                            |
| hyperlinkedmodelserializer    | class  | ``HyperLinkedModelSerializer``                 |
| listserializer                | class  | ``ListSerializer``                             |
| sbool                         | field  | ``BooleanField``                               |
| snullbool                     | field  | ``NullBooleanField``                           |
| schar                         | field  | ``CharField``                                  |
| semail                        | field  | ``EmailField``                                 |
| sregex                        | field  | ``RegexField``                                 |
| sslug                         | field  | ``SlugField``                                  |
| surl                          | field  | ``URLField``                                   |
| suuid                         | field  | ``UUIDField``                                  |
| sfilepath                     | field  | ``FilePathField``                              |
| sip                           | field  | ``IPAddressField``                             |
| sint                          | field  | ``IntegerField``                               |
| sfloat                        | field  | ``FloatField``                                 |
| sdecimal                      | field  | ``DecimalField``                               |
| sdatetime                     | field  | ``DateTimeField``                              |
| sdate                         | field  | ``DateField``                                  |
| stime                         | field  | ``TimeField``                                  |
| sduration                     | field  | ``DurationField``                              |
| schoice                       | field  | ``ChoiceField``                                |
| smultiplechoices              | field  | ``MultipleChoicesField``                       |
| sfile                         | field  | ``FileField``                                  |
| simage                        | field  | ``ImageField``                                 |
| slist                         | field  | ``ListField``                                  |
| sdict                         | field  | ``DictField``                                  |
| shstore                       | field  | ``HStoreField``                                |
| sjson                         | field  | ``JSONField``                                  |
| sreadonly                     | field  | ``ReadOnlyField``                              |
| shidden                       | field  | ``HiddenField``                                |
| smodelfield                   | field  | ``ModelFieldField``                            |
| smethodfield                  | field  | ``MethodFieldField``                           |
| scustomfield                  | field  | ``CustomFieldField``                           |
| rfserializer                  | import | ``from rest_framework import serializers``     |

### Snippets for APIViews

|   Abbreviation                |  Type  |               Code - Description               |
| ----------------------------- | ------ | ---------------------------------------------- |
| createapiview                 | class  | ``CreateAPIView``                              |
| listapiview                   | class  | ``ListAPIView``                                |
| retrieveapiview               | class  | ``RetrieveAPIView``                            |
| destroyapiview                | class  | ``DestroyAPIView``                             |
| updateapiview                 | class  | ``UpdateAPIView``                              |
| listcreateapiview             | class  | ``ListCreateAPIView``                          |
| retrieveupdateapiview         | class  | ``RetrieveUpdateAPIView``                      |
| retrievedestroyapiview        | class  | ``RetrieveDestroyAPIView``                     |
| retrieveupdatedestroyapiview  | class  | ``RetrieveUpdateDestroyAPIView``               |
| rfapi                         | import  | ``from rest_framework.views import APIView``  |
| rfgeneric                     | import  | ``from rest_framework import generics``       |
| rfstatus                      | import  | ``from rest_framework import status``         |
| get_queryset                  | methods  | ``def get_queryset``                         |
| get_object                    | methods  | ``def get_object``                           |
| post                          | methods  | ``def post``                                 |
| get                           | methods  | ``def get``                                  |
| delete                        | methods  | ``def delete``                               |
| put                           | methods  | ``def put``                                  |
| patch                         | methods  | ``def patch``                                |

### Snippets for Viewset

|   Abbreviation                |  Type  |               Code - Description               |
| ----------------------------- | ------ | ---------------------------------------------- |
| modelviewset                  | class  | ``ModelViewSet``                               |
| readonlymodelviewset          | class  | ``ReadOnlyModelViewSet``                       |
| rmviewset                     | import  | ``from rest_framework import viewsets``       |
