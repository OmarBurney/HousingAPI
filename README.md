# Housing Post Object

| column      | data class type | database type |
| ----------- | --------------- | ------------- |
| id          | Int             | INTEGER       |
| email       | String          | TEXT          |
| type        | String          | TEXT          |
| bed         | Int             | INTEGER       |
| bath        | Int             | INTEGER       |
| price       | Int             | INTEGER       |
| covidTested | String          | TEXT          |
| moveIn      | String          | TEXT          |
| location    | String          | TEXT          |
| desc        | String          | TEXT          |
| date        | String          | TEXT          |
| image       | String          | TEXT          |

# API Endpoints

| request type | endpoint            | returns                  |
| ------------ | ------------------- | ------------------------ |
| POST         | /images/upload      | Message or ImageUploaded |
| GET          | /images/{imagename} | Binary for Image         |
| POST         | /housing            | Message                  |
| GET          | /housing/all        | List\<Post>              |
| GET          | /housing/{id}       | Post                     |
