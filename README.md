# Credit-Card-Fraud-Detection-Project
## The problem statement involved creating a predective model from the data that can catch fraudlent transaction in real time and decline them, getting started with the problem one can see that the data is kept in multiple files, initially i had a lot of work before moving ahead and creating the model such as getting and merging the data from multiple sources, then it can also be seen that most of the data contains lot of duplicate values and so on, hence a lot of data wrangling has to be done, so at the begining i wrangled around a lot with the data.
![Screenshot (77)](https://user-images.githubusercontent.com/116963622/216026690-ea0f8e1f-4eba-4629-a74e-09716ade91b2.png)
![Screenshot (78)](https://user-images.githubusercontent.com/116963622/216032414-bc8a4357-1328-4b85-a6f4-d60ae37fe04f.png)
![Screenshot (79)](https://user-images.githubusercontent.com/116963622/216032543-de66f585-0f74-4ecf-9ce6-a1d6d17535b2.png)
## once i was done with the data wrangling and data munging part i went ahead and connected all the data coming from multiple sources into one.
![Screenshot (80)](https://user-images.githubusercontent.com/116963622/216033367-35dd3686-1a16-4281-8112-89df94431664.png)
![Screenshot (81)](https://user-images.githubusercontent.com/116963622/216033474-6b4281c4-ba88-4f61-9335-8f45ac574921.png)
## then the data did not require that much EDA as the data is already in processed format but still with the help of Pandas-Profiling framework we did some minimal EDA.
![Screenshot (82)](https://user-images.githubusercontent.com/116963622/216034414-8619d38d-59e7-49d8-85b0-cd9992b2ea65.png)
![Screenshot (83)](https://user-images.githubusercontent.com/116963622/216034556-0a056d5f-0bcb-48d0-9592-6e391dc8c255.png)
![Screenshot (84)](https://user-images.githubusercontent.com/116963622/216034687-5aec0054-0979-4087-aca6-9a18e7d89ceb.png)
## once this was done i moved ahead and did perform preprocessing such as checking for multicolinearity, imbalanced data etc.
![Screenshot (85)](https://user-images.githubusercontent.com/116963622/216035325-7dcd9ba0-5489-45d9-92d0-238a16f19bae.png)
![Screenshot (86)](https://user-images.githubusercontent.com/116963622/216035548-b450396c-f358-4b10-9cec-b5ad7a24b242.png)
## however even with severe imbalance here in the data we were prohibited by the stakeholders from using resampling techniques, ensemble learning and other techniques to handle this problem, so here we had only one option left that is to use evaluation metrics other than accuracy such as confusion matrix, classification report etc. to gauge the performance of our model.
## hence we applied different models tested them and finally found out that the Bagging Classifier, Random Forest Classifier and the XG-Boost are the three algorithms that are providing us the best model that fits the data.
![Screenshot (87)](https://user-images.githubusercontent.com/116963622/216037598-fc283fb9-47f3-4e8b-99a5-7759d395dd98.png)
![Screenshot (88)](https://user-images.githubusercontent.com/116963622/216037803-9a6a4141-cd8c-494a-8ee8-15410adf0fdb.png)
![Screenshot (89)](https://user-images.githubusercontent.com/116963622/216037939-91c4451a-fd08-477e-a225-a6ed95c6fb22.png)
![Screenshot (90)](https://user-images.githubusercontent.com/116963622/216038052-82cb715d-5a55-4662-84c4-bc55479268c7.png)
![Screenshot (91)](https://user-images.githubusercontent.com/116963622/216038193-fbca088b-861e-4f06-a62b-c91186f2680e.png)
However the work did not end here, i wanted to use some advanced packages and algorithms on the data but my hardware was not enough for that kind of stuff so i exported the data and took the workflow to google colab to carry out rest of the stuff.
