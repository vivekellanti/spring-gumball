# spring-gumball

Screenshots show successful build and deployment of the JAVA Ci with Gradle workflow. It didnt work the first time I used the professors gradles file. So, I reverted the gradle file back to the default, committed it, then changed and commited it to the professors gradle. Then, it finally worked
<img width="1512" alt="Screen Shot 2022-05-16 at 11 36 29 PM" src="https://user-images.githubusercontent.com/59064994/168744982-8cb49906-33d4-45c0-a65b-3fa905a3239b.png">
<img width="1512" alt="Screen Shot 2022-05-16 at 11 33 58 PM" src="https://user-images.githubusercontent.com/59064994/168744739-ba950c80-899f-4b95-b088-e6d81251b975.png">
<img width="1512" alt="Gradle build results image1" src="https://user-images.githubusercontent.com/59064994/168744900-73407228-a124-4acc-b694-c5d3f27e93c2.png">
<img width="1512" alt="Gradle build results image 2" src="https://user-images.githubusercontent.com/59064994/168744903-ee8287e2-276f-4867-9d87-0edffbcb00b7.png">

Creating service account and adding key. I had to make the service account under the owner rule for it to work.
<img width="1512" alt="Screen Shot 2022-05-16 at 11 46 34 PM" src="https://user-images.githubusercontent.com/59064994/168746786-d0ef748d-bbc0-4e91-9ef9-7bf73ad13ae8.png">
<img width="1512" alt="Screen Shot 2022-05-16 at 11 46 50 PM" src="https://user-images.githubusercontent.com/59064994/168746962-4677f2fd-42b0-4a32-9195-55359fb27690.png">

I created the following repository secrets (highlighted in green) under the production environment. The GKE_PROJECT held the projectID value from the json file that was generated once I created a key in the google kubernetes engine.  The GKE_SA_KEY held the value of all contents in the json file.
<img width="1288" alt="Screen Shot 2022-05-16 at 11 49 30 PM (2)" src="https://user-images.githubusercontent.com/59064994/168747579-a39e0c29-52a5-457f-ad67-7c09338d7615.png">

I created a release titled 1.2 and released it which triggered the GKE workflow to build and deploy. These screenshots showcase a successful release, deployment.
<img width="1512" alt="Screen Shot 2022-05-16 at 11 55 30 PM" src="https://user-images.githubusercontent.com/59064994/168748477-c4d8616d-e66f-4efa-9a10-0ecb1d6f4eab.png">
<img width="1512" alt="Screen Shot 2022-05-16 at 11 55 40 PM" src="https://user-images.githubusercontent.com/59064994/168748506-1cad1967-d104-4533-b7d6-79e0a022a962.png">
<img width="1512" alt="Screen Shot 2022-05-16 at 11 55 47 PM" src="https://user-images.githubusercontent.com/59064994/168748528-bd47c622-ac16-45a6-b4c6-c885cf62195d.png">
<img width="1512" alt="Screen Shot 2022-05-16 at 11 57 35 PM" src="https://user-images.githubusercontent.com/59064994/168748743-4919c945-6dd4-40c0-a568-6942f1cf8eac.png">
<img width="1512" alt="Screen Shot 2022-05-16 at 11 57 55 PM" src="https://user-images.githubusercontent.com/59064994/168748755-113f7389-bdc5-4dd9-9255-b7557e1c8623.png">

<img width="1512" alt="Screen Shot 2022-05-16 at 11 26 14 PM" src="https://user-images.githubusercontent.com/59064994/168745259-1b805f31-e1da-47f6-82d3-6ddc5c4f7126.png">
<img width="1512" alt="Screen Shot 2022-05-16 at 11 26 16 PM" src="https://user-images.githubusercontent.com/59064994/168745281-0b0087d8-cdbf-4544-af6c-c294f4a807e8.png">
Cluster being made
<img width="1288" alt="Screen Shot 2022-05-16 at 11 26 14 PM (2)" src="https://user-images.githubusercontent.com/59064994/168745326-f05f6cb0-8836-4f74-a376-000e192f12ce.png">

Spring-gumball-workload deployed
<img width="1512" alt="Screen Shot 2022-05-16 at 11 26 55 PM" src="https://user-images.githubusercontent.com/59064994/168745371-2a833a5b-305c-45c4-96f8-cedf5856f02a.png">


Spring-gumball service creation
<img width="1288" alt="Screen Shot 2022-05-16 at 11 40 06 PM (2)" src="https://user-images.githubusercontent.com/59064994/168745575-e2a4522f-6737-4f97-97d6-acd637302ef6.png">

Spring-gumball-lb ingress service created
<img width="1288" alt="Screen Shot 2022-05-16 at 11 40 39 PM (2)" src="https://user-images.githubusercontent.com/59064994/168745667-0785bf97-75cd-46df-9fc1-d204677f52b4.png">

This is what opens after clicking the frontend address "34.102.245.99", which is under the front end category in the spring-gumball-lb ingress deployment,

<img width="1512" alt="Screen Shot 2022-05-16 at 11 43 36 PM" src="https://user-images.githubusercontent.com/59064994/168746275-5ef441cb-a920-40c9-8a8d-37bf9b663195.png">

