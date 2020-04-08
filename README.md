    ### File paths on windows
    ```
    val textFile = sc.textFile("g:\\spark-2.4.5-bin-hadoop2.7\\README.md")
    ...
    sortedCounts.saveAsTextFile("g:\\devSpark\\ReadMeWordCountViaApp")
    ```
    
    ### Submiting spark job
    ```
    spark-submit --class "main.WordCounter" --master "local[*]" "G:\devSpark\word-count\target\scala-2.11\word-count_2.11-0.1.jar"
    ```