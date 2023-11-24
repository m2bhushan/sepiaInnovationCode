# sepiaInnovationCode
FrequencyQuestionCode
/*
 * As per problem-
   1 x: Insert x in your data structure.
   2 y: Delete one occurence of y from your data structure, if present.
   3 z: Check if any integer is present whose frequency is exactly . If yes, print 1 else 0.
 *  
 *  As per my understanding I'm explaining the logic-
 *  
 *  query  |  data               |  Point
 *  1   5  |  5 (will be removed)|  
 *  1   6  |  6                  |  
 *  3   2  |                     |  0
 *  1   10 |  10                 |  
 *  1   10 |  10                 |  
 *  1   6  |  6                  |  
 *  2   5  |                     |  
 *  3   2  |                     |  1
 *  Above for quesry 1 we have inserted 5,6,10,10,6 respectively in data structure, for quesry 2 we have to delete
 *  the occurance if present in ds so 5 will be removed from ds. And for query 3 the given z value is 2 and above
 *  we have 2 times 6 and 10 so it is equal to z value so the point we will give as 1.
 *  
 *  so for solving we have to go through dictionary approach and check the condition with above checkes as- 
 *      if query is 1 we have to insert value in ds
 *      if quesry is 2 we have to check if the occurance if available in our ds then we have to remove it.
 *      and if query is 3 we have to check if the z mean the occurance value is same then we will give point as 1 else 0.
 *
*/
