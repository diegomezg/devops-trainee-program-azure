## Delete and Restore a Blob Object 
**Soft Delete** was enabled as part of the configuration for the Storage Account so this task involves deleting a file from the bucket and attempting to restore the file afterwards. A sample file that was uploaded from a  previous exercise will be used for this activity

- **Step 1:** Navigate to the Storage Account and then to the blob container. Select the sample file and click on the "Delete" button to delete the file. Notice that the file is no longer visible in the blob container

- **Step 2:** Toggle the "Show deleted blobs" switch to display the deleted file. From the file options, select "undelete" to restore the deleted file to the blob container

![Deleted]()

Notice that status of the file in the blob container has changed to "Active"

![Active]()