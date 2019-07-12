| Good |
| --- |
| Use Maven or Gradle wrappers. |
| Include a Cloud Foundry manifest file in your application repository. |
| Include a pipeline descriptor (sc-manifest.yml) in your app repository. |
| Create an empty version branch in your application repository. |
| Include artifact repository configuration in the pom.xml file. |
| Align your Cloud Foundry spaces with the Cloud Pipelines model (isolated test space and shared stage and prod spaces). |

| Better |
| --- |
| Include default, apicompatibility, smoke, and e2e profiles in the pom.xml file. |
| Organize tests accordingly in your application repository. |

| Best |
| --- |
| Use a database migration tool, such as Flyway. |
| Use contract-based API programming. |
