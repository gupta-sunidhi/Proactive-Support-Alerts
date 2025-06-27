| Component              | Test Description                              | Expected Outcome                       |
| ---------------------- | --------------------------------------------- | -------------------------------------- |
| File Upload            | Upload valid JSON file                        | Clusters processed and displayed       |
| Threshold Alert        | Trigger alert with >= threshold similar cases | Email is sent via EmailJS              |
| Empty or Invalid Email | Leave email blank                             | Alert shown to user, no API call       |
| Model Embedding        | Test ticket vectorization                     | Embeddings array matches ticket count  |
| UI Update              | Check cluster display in output panel         | Cluster blocks show with ticket titles |
