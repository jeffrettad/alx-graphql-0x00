## Episode Details by ID
Use this query to fetch the details of a specific episode using its ID. The query retrieves:
-id
-name
-air_date
-episide
# Example Query:
query{
    episode( id: 1){
        id 
        name
        air_date
        episode
    }
}
