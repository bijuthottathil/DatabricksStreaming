# Databricks Structured streaming

![image](https://github.com/user-attachments/assets/6fa49152-e6f1-4509-b08e-be80446bb3a9)

![image](https://github.com/user-attachments/assets/00523505-6898-482f-a851-c4b10791c7a7)

Streaming query is still running and waiting for data

![image](https://github.com/user-attachments/assets/2170648a-c646-48d9-8d0f-11268d35cd05)

Because of streaming query, it will be executed infinitely
![image](https://github.com/user-attachments/assets/a3f349a8-508b-47ba-be92-9418dcbabf96)

Dashboard will give visual view

![image](https://github.com/user-attachments/assets/4583a411-21fb-47a8-a579-843b9409f627)

Raw data also visible

![image](https://github.com/user-attachments/assets/69e0a0cd-e4fe-4178-8ec3-720ad9926fb9)

![image](https://github.com/user-attachments/assets/d6ef93b0-a4ce-481e-a765-3c0e3e2f986e)

now we  are using dataframe to write streaming query data to a storage

![image](https://github.com/user-attachments/assets/9bbdd52f-7998-45f1-8adc-62c987d88326)

![image](https://github.com/user-attachments/assets/223db625-276c-436a-ac43-8a078aef6581)

Queried target table

![image](https://github.com/user-attachments/assets/600052d8-9df8-442f-9d50-757366231ae3)

Next we will insert some data in books table and see how it is reflecting in streaming query

![image](https://github.com/user-attachments/assets/12ab494a-a8bf-49e0-b897-40bba1882ca3)
added one more batch

![image](https://github.com/user-attachments/assets/4becb2b5-d9cc-4a8f-b588-e1a4bc29f276)

streaming is still running and added data 

![image](https://github.com/user-attachments/assets/f6f0bb5f-f8e0-4579-8c50-bbe696e7574e)

If we query author_counts, you can see updated table records count

![image](https://github.com/user-attachments/assets/ee7fbfe0-24ae-44cb-a88e-e0f1c0de5fab)

No I cancelled streaming query . will see another scenario  to copy all available batch to destination

![image](https://github.com/user-attachments/assets/9d252e19-bca4-4a1b-9566-025fcd0e804e)

Here you can see, whatever available entries loaded to destination table using  .trigger(availableNow=True)

![image](https://github.com/user-attachments/assets/df000150-dd09-499b-9189-5c41578644e6)





